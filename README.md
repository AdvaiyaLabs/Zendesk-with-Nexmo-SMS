# Zendesk with Nexmo SMS
![](./media/image1.png)

![](./media/image2.png)

## Introduction

Zendesk with nexmo SMS app will allow Zendesk users to send SMS to the requester on various stages/events of their ticket on Zendesk. Using this app, Zendesk’s users can configure the event as well as SMS text.

## Use case

1.  Send SMS on new ticket creation to requester.

2.  Send SMS on updating a ticket to requester.

3.  Various such events where ticket requester can be informed for change or update in the ticket status.

## Prerequisites 
-   Zendesk subscription.

-   Zendesk admin credentials

-   This app requires Nexmo subscription and corresponding Nexmo API keys (Keys and Secret). To access the API keys, see appendix section.

-   To configure this app you need internet connectivity.

## Features 

-   **Custom messaging text:** Allows user to customize the SMS text as per need.

-   **Custom placeholder or fields**: While drafting the custom message user can insert custom placeholders or fields.

-   **Enable and disable** SMS functionality

## Steps to install the Zendesk with nexmo SMS

1.  <span id="_Toc432770622" class="anchor"></span>Login into the Zendesk portal with admin credentials.

2.  On dashboard, click on the gear icon in bottom left and select **Manage** under the “APPS” heading.

    ![](./media/image3.png)

3.  Click on **Upload App**.

    ![](./media/image4.png)

4.  Give this installation a name and choose the zip file and click on **Upload**.

    ![](./media/image5.png)

5.  A pop up will appear with **T&C**, click on upload.

6.  Provide Nexmo API Key, Secret, From Number and click on **Install**.

    ![](./media/image6.png)

7.  App will get installed and listed under **Manage Apps section.**

    ![](./media/image7.png)

## Steps to use the Zendesk with nexmo SMS

1.  Login into the Zendesk portal with admin credentials.

2.  Click on **Triggers** in side menu under **BUSINESS RULES** heading.

    ![](./media/image8.png)

3.  Click on **add trigger**

    ![](./media/image9.png)

4.  You can create a trigger for any event that is mentioned here. For example let us create a trigger when a ticket is created.

    Select “Ticket: is” from the drop down.

    ![](./media/image10.png)

5.  Select **Created** from the second drop down as shown in the image below:

    ![](./media/image11.png)

6.  Now in **Perform these actions** section**,** choose **Notifications: Notify target** from first drop down and **Nexmo SMSs** from the second drop down as shown in the image below:

    ![](./media/image12.png)

7.  Type the message you want to send. Use placeholder wherever you need.

    ![](./media/image13.png)

8.  **If you want to see all the available placeholders, click on View available placeholders** button.

    ![](./media/image14.png)

9.  When you are done, click on **Create Trigger** from bottom right. Your trigger is created and will be shown in active triggers list.

    ![](./media/image15.png)

10. Now when you create a new ticket the SMS will be fired on requestor phone number.

11. You can create ticket by clicking **Add** from the top menu and then on ticket and provide relevant details. Make sure the requester has saved their phone number in profile.

    ![](./media/image16.png)

## Appendix

## Nexmo API Keys

-   To access the Nexmo keys, go to <https://www.nexmo.com/> and Sign-in.

-   On the top right corner, click on the “**Api Settings**”.

-   Key and Secret will display in the top bar as shown in the below image:

> ![](./media/image17.png)
