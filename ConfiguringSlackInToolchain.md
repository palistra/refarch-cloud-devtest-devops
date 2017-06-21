# Configure Slack Integration

# Objective
This lab show how to integrate your toolchain with Slack to collaborate with your team and receive notifications about your test and deployment activities.

## Prerequisites
You need the personal Slack ID you used in **Getting Ready for the DevTest DevOps Lab**.

**Tasks**:
- [Task 1: Configure Slack in Toolchain](#task-1-configure-slack-in-toolchain)

## Task 1: Configure Slack in Toolchain

**Note:** These steps are to be used for the **Configure Slack** steps in:

https://www.ibm.com/devops/method/tutorials/tutorial_toolchain_microservices_cd?task=1

1 In a seperate browser tab, enter the following URL: [http://ibm.biz/SlackWebhooks]http://ibm.biz/SlackWebHooks.
2. Copy the relevant Slack webhook URL based on the location of your training.
![CreateSlackIntegrationWebhooks](screenshots/CreateSlackIntegrationWebhooks.png)
They are also listed below if you prefer to type.

- madrid_demolab_devops    https://hooks.slack.com/services/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
- montp_demolab_devops     https://hooks.slack.com/services/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
- dallas_demolab_devops    https://hooks.slack.com/services/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
- ny_demolab_devops        https://hooks.slack.com/services/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

2. Return to the **Create a Toolchain** broswer tab.
3. On the toolchain's Overview page, click **Slack**.
3. On the Slack Configuration page:
   - Paste the SLack webhook URL API key you just copied into the Slack webhook field
   - Enter the relevant channel based on the location of your training into the Slack channel field.
     - madrid_demolab_devops
     - montp_demolab_devops
     - dallas_demolab_devops
     - ny_demolab_devops
   - Enter **BluemixDevOpsLab** as the Slack team name.

![CreateSlackIntegration](screenshots/CreateSlackIntegration.png)
