# Bamboo: run a job on a specific agent

In Bamboo, the place where a job executes is called an **agent**. There are three kinds:

1. **Local agents** – run on the Bamboo server itself
2. **Remote agents** – run on separate machines and connect to the server
3. **Elastic agents** – on-demand Amazon EC2 instances

By default, a job runs on any available agent whose **capabilities** satisfy the job's **requirements** (for example, a specific JDK or executable). To pin a job to particular machines, either add a custom requirement that only those agents have, or **dedicate** the agents to the plan or job.

📖 Docs: [Bamboo agents and capabilities](https://confluence.atlassian.com/bamboo/agents-and-capabilities-289277114.html) · [Dedicating an agent](https://confluence.atlassian.com/bamboo/dedicating-an-agent-629015108.html)

[⬅ Back to Infraverse](../../README.md#cicd)
