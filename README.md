# Zendesk with Nexmo SMS
<img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image1.png" width=200>

## Introduction

Zendesk with [Nexmo SMS](https://nexmo.com/sms) app will allow Zendesk users to send SMS to the requester on various stages/events of their ticket on Zendesk. Using this app, Zendesk’s users can configure the event as well as SMS text.

## Use case

1.  Send SMS on new ticket creation to requester.

2.  Send SMS on updating a ticket to requester.

3.  Various such events where ticket requester can be informed for change or update in the ticket status.

## Prerequisites 
-   Zendesk subscription.

-   Zendesk admin credentials

-   This app requires [Nexmo](https://nexmo.com/) subscription and corresponding Nexmo API keys (Keys and Secret). To access the API keys, see appendix section.

-   To configure this app you need internet connectivity.

## Features 

-   **Custom messaging text:** Allows user to customize the SMS text as per need.

-   **Custom placeholder or fields**: While drafting the custom message user can insert custom placeholders or fields.

-   **Enable and disable** SMS functionality

## Steps to install the Zendesk with Nexmo SMS

1.  Login into the Zendesk portal with admin credentials.

2.  On dashboard, click on the gear icon in bottom left and select **Manage** under the “APPS” heading.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image3.png" width=600>

3.  Click on **Upload App**.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image4.png" width=600>

4.  Give this installation a name and choose the downloaded zip file and click on **Upload**.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image5.png" width=600>

5.  A pop up will appear with **T&C**, click on upload.

6.  Provide Nexmo API Key, Secret, From Number and click on **Install**.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image6.png">

7.  App will get installed and listed under **Manage Apps section.**


## Steps to use the Zendesk with Nexmo SMS

1.  Login into the Zendesk portal with admin credentials.

2.  Click on **Triggers** in side menu under **BUSINESS RULES** heading.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image8.png" height=400>

3.  Click on **add trigger**

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image9.png" width=600>

4.  You can create a trigger for any event that is mentioned here. For example let us create a trigger when a ticket is created.

    Select “Ticket: is” from the drop down.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image10.png" width=600>

5.  Select **Created** from the second drop down as shown in the image below:

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image11.png" width=400>

6.  Now in **Perform these actions** section**,** choose **Notifications: Notify target** from first drop down and **Nexmo SMSs** from the second drop down as shown in the image below:

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image12.png" width=600>

7.  Type the message you want to send. Use placeholder wherever you need.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image13.png">

8.  If you want to see all the available placeholders, click on **View available placeholders** button.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image14.png">

9.  When you are done, click on **Create Trigger** from bottom right. Your trigger is created and will be shown in active triggers list.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image15.png" width=600>

10. Now when you create a new ticket the SMS will be fired on requestor phone number.

11. You can create ticket by clicking **Add** from the top menu and then on ticket and provide relevant details. Make sure the requester has saved their phone number in profile.

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image16.png" height=200>

## Appendix

## Nexmo API Keys

-   To access the Nexmo keys, go to <https://www.nexmo.com/> and Sign-in.

-   On the top right corner, click on the “**Api Settings**”.

-   Key and Secret will display in the top bar as shown in the below image:

    <img src="https://github.com/AdvaiyaLabs/Zendesk-with-Nexmo-SMS/blob/master/docs/image17.png" width=600>