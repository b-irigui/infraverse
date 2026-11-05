# GitLab CI: run a job on a specific runner

In GitLab, the machines that execute jobs are called **runners**. They can be **instance** runners (shared by every project), **group** runners or **project** runners.

If shared runners are enabled, jobs are picked up by any available runner. To send a job to a specific runner, give the runner one or more **tags** and reference them in `.gitlab-ci.yml`:

```yaml
build:
  tags:
    - docker
  script:
    - make
```

The job will only run on runners tagged with `docker`. If you list several tags, the runner must have **all** of them.

📖 Docs: [GitLab Runner](https://docs.gitlab.com/runner/) · [`tags` keyword](https://docs.gitlab.com/ci/yaml/#tags)

[⬅ Back to Infraverse](../../README.md#cicd)
