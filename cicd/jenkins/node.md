# Jenkins: run a job on a specific node

In Jenkins, the machines that execute builds are called **agents** (older docs call them "slaves"; the controller was formerly called "master"). You can target an agent by **name** or by **label**, and the syntax depends on the pipeline type.

## Declarative pipeline

Run on any agent that has the label `virtual`:

```groovy
pipeline {
    agent { label 'virtual' }
    stages {
        stage('Build') {
            steps {
                sh 'make'
            }
        }
    }
}
```

You can also pick an agent per stage by setting `agent` inside a `stage` block, and use `agent none` at the top level.

## Scripted pipeline

Run on the agent named `some_node`:

```groovy
node('some_node') {
    sh 'make'
}
```

Run on any agent with the label `virtual` (labels can be combined, e.g. `'linux && docker'`):

```groovy
node('virtual') {
    sh 'make'
}
```

📖 Docs: [Using agents](https://www.jenkins.io/doc/book/using/using-agents/) · [Pipeline syntax: agent](https://www.jenkins.io/doc/book/pipeline/syntax/#agent)

[⬅ Back to Infraverse](../../README.md#cicd)
