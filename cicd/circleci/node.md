# CircleCI: run a job on a specific machine

In CircleCI, a job runs on an **executor** (`docker`, `machine`, `macos`, …). The size and type of machine is set with `resource_class`.

To run a job on **your own infrastructure**, install a **self-hosted runner** and point the job's `resource_class` at the runner's namespace/name:

```yaml
version: 2.1

workflows:
  testing:
    jobs:
      - runner-test

jobs:
  runner-test:
    machine: true
    resource_class: your-namespace/your-resource-class
    steps:
      - run: echo "Hi, I'm running on a self-hosted runner!"
```

📖 Docs: [CircleCI documentation](https://circleci.com/docs/) (see *Self-hosted runners* and *Configuring a resource class*)

[⬅ Back to Infraverse](../../README.md#cicd)
