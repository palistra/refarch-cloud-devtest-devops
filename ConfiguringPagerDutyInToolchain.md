# Configure PagerDuty Integration

# Objective 
This lab show how to integrate your toolchain with PagerDuty so teams get notified when things go wrong so problems can be fixed faster and reduce downtime.

## Prerequisites
If you want to see email notifications from PagerDuty, you will need access to an eMail account.  Once the integration is created, you can check that account to accept the invitation to join PagerDuty and to see alerts from PagerDuty.

**Tasks**:
- [Task 1: Configure PagerDuty in Toolchain](#task-1-configure-pagerduty-in-toolchain)

## Task 1: Configure PagerDuty in Toolchain
As a developer or operations person, you may want to be notified of the status of code deployments.  One way to be alerted  is to integrate third-party tools such as [PagerDuty](https://www.pagerduty.com/).  IBM Bluemix has made it easy to add PagerDuty integration into a Toolchain so the teams such as development or operations are notified of the status of deployments.

**Note:** The PagerDuty integration feature is not created by, affiliated with, or supported by PagerDuty, Inc.
**Note:** These steps are to be used for the **Configure PagerDuty** steps in:

https://www.ibm.com/devops/method/tutorials/tutorial_toolchain_microservices_cd?task=1

1. In a seperate browser tab, enter the following URL: [http://ibm.biz/PagerDutyAPIKey]http://ibm.biz/PagerDutyAPIKey.
2. Copy the API key (the screenshot is a sample, the actual API key may be different)
![CreatePDIntegrationAPIKey](screenshots/CreatePDIntegrationAPIKey.png)
2. Return to the **Create a Toolchain** broswer tab.
3. On the toolchain's Overview page, click **PagerDuty**.
3. On the PagerDuty Configuration page:
   - Paste the API key you just copied into the API access key field (be careful of spaces)
   - Enter "devopslab" as the PagerDuty service name
   - Enter an email address you can access.  Leave the phone number blank.  PagerDuty has a place for you to enter your phone number if you want to receive text messages or receive phone calls.
![CreatePDIntegration](screenshots/CreatePDIntegration.png)
4. Click **Create**
5. You can access the eMail account to accept the PagerDuty invitation.

  ![CreatePDIntegrationInvite](screenshots/CreatePDIntegrationInvite.png)

6. You can enter your phone information into your PagerDuty account (if you have one).  If you do this, you will get text messages and/or phone calls, depending on where you entered your phone number.  Normal messaging rates apply.

  ![CreatePDIntegrationPhone](screenshots/CreatePDIntegrationPhone.png)

  The list of countries PagerDuty supports is at: [PagerDuty Country Support](https://support.pagerduty.com/hc/en-us/articles/202828860-Countries-PagerDuty-supports-for-SMS-and-phone-call-notifications)
