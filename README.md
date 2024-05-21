# Mocean monday.com SMS Broadcast User Documentation

## Looking for other documentation ?
- [MoceanAPI - SMS Broadcast Documentation](https://github.com/MoceanAPI/monday-dashboard)  (Current)
- [MoceanAPI - Send SMS Documentation](https://github.com/MoceanAPI/monday-item/)
- [MoceanAPI - Omnichannel Messaging](https://github.com/MoceanAPI/monday-omnichannel)
- [MoceanAPI - SMS Automation Documentation](https://github.com/MoceanAPI/monday-automation/)
- [SMS Sender ID Country List](https://moceanapi.github.io/monday/)

## Contents
- [Installation](#installation)
- [Usage](#usage)
    - [Send SMS to specific phone numbers](#send-sms-to-specific-phone-numbers)
    - [Send SMS to Board Items](#send-sms-to-board-items)
    - [Send SMS to Board Items from a virtual number](#send-sms-to-board-items-from-a-virtual-number)
- [Whitelist IP Address](#whitelist-ip-address)
- [Frequently Asked Questions (FAQ)](#faq)
- [Feature Request](#feature-request)
- [Feedback](#feedback)

## Installation

1. If you don't already have a dashboard created, go ahead and create a dashboard in `monday.com`
2. Select the dashboard and click on `Add Widget` and select `Apps`
![image](https://user-images.githubusercontent.com/24620178/153533091-f1e61325-b6e6-4771-b6ae-4c2097437e62.png)
3. Search for `Mocean` in the search bar and install the `MoceanAPI - SMS Broadcast`
![image](https://user-images.githubusercontent.com/24620178/153551069-c098d07a-c57d-4f9a-b304-98309d438554.png)
4. After installing the widget, you will need to `Authenticate` your account
![image](https://user-images.githubusercontent.com/24620178/153541647-1d1bb726-cdc3-475a-8da0-1504ff583614.png)
5. Enter your Mocean API Credentials and the sender
![image](https://user-images.githubusercontent.com/24620178/206361812-183b24e8-8a89-4044-8b4a-ae32fee3320b.png)
6. After you've successfully authenticated, you will be redirected back to `monday.com`

## Usage
### Send SMS to specific phone numbers

1. To send SMS to specific phone numbers, select `Send to specific phone numbers` from the `Send Type` dropdown list
2. Enter the phone numbers you'd like to send to
3. Compose the SMS you'd like to send.
![image](https://user-images.githubusercontent.com/24620178/206366203-d39691fb-ae2c-4a86-a2e3-aacefa07a2e7.png)

### Send SMS to Board Items
0. This is the sample board items we have imported from `monday.com`
![image](https://user-images.githubusercontent.com/24620178/206368766-bcd9b2df-e1a7-49e4-99e2-01032749fccb.png)
1. Select `Send to board filtered by status criteria/value` from the `Send Type` dropdown list.
2. Choose the `Board` you would like to send SMS to
3. Select the `Column` you would like to filter by.
4. Select the `Criteria` you would like to send SMS to
5. Select the `Phone Column` to send SMS to and compose your SMS
6. (Optional) You can configure keywords to personalise your SMS
![image](https://user-images.githubusercontent.com/24620178/206367524-c0d4e85d-f35c-4ab6-871f-733830cbd3a0.png)
7. (Optional) Preview your SMS to see what your users will get before sending the SMS
![image](https://user-images.githubusercontent.com/24620178/206367607-4ce1bf68-33ec-41c7-a825-7867bc2c0189.png)

### Send SMS to Board Items from a virtual number

1. If you don't already own a virtual number, get one [here](https://github.com/Moceanapi/monday-two-way/#buy-a-virtual-number)
2. Select the `Virtual number` you'd like to send SMS from.
3. Choose the `Board` you would like to send SMS to
4. Select the `Column` you would like to filter by.
5. Select the `Criteria` you would like to send SMS to
6. Select the `Phone Column` to send SMS to
7. Select the `Person Column` you'd like to notify on every SMS reply and compose your SMS
8. (Optional) You can configure keywords to personalise your SMS

![image](https://user-images.githubusercontent.com/24620178/220554748-be449ff8-70b4-4fba-9052-5dd063b50a6c.png)

## Whitelist IP Address

For added security, you should whitelist `192.168.4.1` IP address in your [MoceanAPI Dashboard](https://dashboard.moceanapi.com)

To do so, follow these steps

1. Go to [MoceanAPI Dashboard](https://dashboard.moceanapi.com/user/apisetting)
2. Navigate to **API Account** 
3. Key in **`192.168.4.1`** into **Allow IP** field

![image](https://user-images.githubusercontent.com/24620178/200761674-1ccb6e6c-2d7b-499d-bef6-ee47a3e2a624.png)

## FAQ
1. **Can I get Test Credits ?**
- You can get 20 FREE credits. Please note that once you make a top-up, the free credits will be removed.

2. **What means by 20 credits, 1 credit = EUR 1?**
- No, during the trial period, 1 credit equals 1 SMS. So, with 20 credits, you can test 20 SMS.

3. **Can I request more trial credits?**
- Yes, of course! If you&#39;d like to test further, feel free to request from us.

4. **Can I send international messages?**
- Yes. We are an international SMS provider. You can send out SMS both locally and internationally.
The price for each country varies, do check out our pricing list here (link to
https://moceanapi.com/pricing)

5. **What is the maximum characters per SMS I can put into the message?**
- English messages can be up to 160 characters, while for Unicode text messages (including Arabic,
Chinese, etc.), the limit is 70 characters.

6. **Do you support long message content?**
- Yes, you can send long message content and your credit will be deducted based on the length of the message content.

7. **Is there a limit to how many numbers I can send at one time?**
- There is no limit on numbers to be sent in one go.

8. **What format does my phone number need to be in?**
- Mobile phone numbers need to be entered in international formatting with the country code and without spaces, plus signs or leading zeros. Example: Country code 60 for country Malaysia, 60123456789

9. **What is the character limit for the sender/sender ID?**
- The alpha sender ID can be a maximum of 11 characters, while the numeric sender can consist of up to 15 digits.

10. **I attempted to send messages to US numbers, but they failed to be delivered. Why?**
- Message content that is not registered will result in a failure. To comply with US regulations, it’s essential to buy a number and undergo a use case verification before you can send SMS to your customers.

11. **Can I utilize my personal mobile or landline number as the sender for SMS to the US?**
- No, it’s necessary to purchase a dedicated number, such as a Toll-Free Number, and complete the use case verification process.

12. **How do I go about obtaining or purchasing a Toll Free Number in the US/Canada?**
1) Complete the number registration form available [here](https://docs.google.com/document/d/1I37LP5jF4fnpno9FUcvcQ0p06oGtOqhZ/edit) 
2) Proceed with the payment.
3) After your registration is accepted and approved, you’ll be able to send and receive SMS using your Toll Free Number.

13. **What is the expected timeframe for number approval?**
- Yes, it is possible. We would need a LoA (Letter of Agency) signed to allow us to take over the SMS part of the number.

14. **I am currently having a TFN / 10DLC from another provider. I want to use the same number in your platform. Is that possible?**
- Yes, it is possible. We would need a LoA (Letter of Agency) signed to allow us to take over the SMS part of the number.

15. **Why my SMS failed to deliver?**
- You may have set an invalid sender ID, alphanumeric sender ID must be less than 12 characters, and numeric sender ID must be less than 16 characters. Another common issue is you did not specify the correct phone number format including country code. Example: Country code 60 for country Malaysia, 60123456789

16. **I want to purchase SMS credits, how to top up my account?**
- Easy &amp; fast, just follow a few steps below:
1) Login to your account at [https://dashboard.moceanapi.com/login](https://dashboard.moceanapi.com/login) 
2) Go to Top Up page on left menu
3) Select Payment
4) Pay with credit card / PayPal
Your account will be credited instantly and enjoy texting!

17. **Why I cannot buy a Virtual Number?**
- This is due to your account is under trial mode or has insufficient balance. Please top up before proceeding with number purchase.

18. **Why I cannot get monday.com Notifications after receiving an SMS reply?**
- You will need to connect your Monday.com account with us. We have a video for you to follow along to connect your Monday.com account and MoceanAPI. Check it out [here](https://www.youtube.com/watch?v=P1DG6grBlQ0)

19. **Do I need a Virtual Number to send 1-Way SMS?**
- No, you don’t need a Virtual Number to send 1-Way SMS, unless you are sending SMS to recipients in the US &amp; Canada.


### SMS Compliance in United States (US)

1. **SMS Compliance Guidelines**
- Below are some general guidelines / best practices you can follow:
<ins>Obtain proper consent</ins>: You must obtain consent from the mobile subscriber before sending any SMS messages. The consent should be opt-in and clearly disclose the frequency and nature of messages.
<ins>Include opt-out instructions</ins>: Every SMS message should include clear and easy-to-follow instructions on how to opt-out of receiving further messages.
<ins>Provide customer support</ins>: Your SMS messaging program should include customer support options for subscribers to receive assistance
<ins>Comply with content restrictions</ins>: SMS messages should comply with all content restrictions and regulations

2. **Campaigns Prohibited:**
- Loan advertisements except for messages from direct lenders for secured loans
- Payday loans
- Credit repair
- Debt relief
- Pharmacy/Cannabis/Tobacco/Vape
- ED
- Work from home, 'secret shopper' and similar advertising campaigns
- Gambling/sweepstakes
- Cryptocurrencies
- Lead generation campaigns that indicate the sharing of collected information with third parties

3. **Messaging Prohibited:**
- Message streams that result in excessive complaints or STOP commands typically indicate an unwanted message campaign and will not be allowed to continue.
- Phishing: Messages that attempt to obtain sensitive information, such as usernames, passwords, or financial information, through fraudulent means are strictly prohibited.
- Fraud or scams: Messages that deceive subscribers by promoting fraudulent or misleading offers, schemes, or scams are not allowed.
- Messages that use deceptive marketing practices or false claims to promote products or services are prohibited.
- Messages that distribute malware or direct subscribers to download apps from non-secure locations are strictly prohibited.
- Loan, debt consolidation, debt relief, and student loan programs from any enterprise that cannot grant the loan themselves: Enterprises that cannot grant loans themselves are not allowed to promote loan, debt consolidation, debt relief, and student loan programs.
- Affiliate lead generation for these financial programs is also prohibited.

4. **US SMS Delivery Option**
   
| Section| 10DLC | TOLL FREE| DEDICATED SHORT CODE|
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Introduction                 | 10DLC is just the new name for sending primarily 1-way A2P messages over local long codes. In the past using local long codes was primarily for 2-way conversational traffic (P2P) but companies were using it for 1-way traffic as well. If you wanted to send any kind of volume of messages via long codes (more than a few hundred a day) you had to use a pool of senders because velocity filters would treat high volumes of messages coming from one sender as SPAM and automatically block the sender. Now with 10DLC registration you can send higher volumes of messages from a single sender. This works really well for sending under about 2,000 messages per day and if you or your customer wants a local sender in their area. External vetting is also available for an additional fee to get more than 2,000 messages per day per sender.  | A few years ago Operators started allowing SMS to be delivered via the toll free number pool that was previously only for voice calls. Toll free numbers are also 10 digits long but all start with one of the following dial codes: 1800, 1888, 1877, 1866, 1855, 1844 or 1833. This route allows for handset DLR (delivery receipt) instead of the less accurate gateway DLR provided on 10 DLC. The route also did not have a volume limit per sender like long codes do so it was ideal for business use. Additionally, the service comes with auto responders built in for STOP, HELP and CANCEL responses from mobile subscribers, and has a gateway maintained opt-out database per sender. The route currently has the same content restrictions as 10 DLC. | In the USA a short code is a dedicated 5 or 6 digit sender ID assigned to a specific brand for a specific purpose or campaign. A good example is a bank sending one time codes to their customers for 2 factor authentication. This is the most premium SMS service in the USA as it has handset DLR and goes through a lengthy vetting process. There are several requirements to get one of these codes approved, they take about 1-2 months to get fully approved and have significant monthly and setup fees, so they are typically used by larger corporations with very high volume sending. Client needs to show opt-in process and be able to handle auto responders for HELP/STOP/CANCEL as well as maintain opt-out database per campaign.  |
| Type of Number &amp; Example | Long Number (Example: 13458677777)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Toll-Free Number (Example: 18885555555)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 5 or 6 digit Short Code (Example: 12345)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Suggested Use Cases          | High volumes, Marketing, 2FA, Alerts, 2FA, Notifications, Customer Care, Alerts, Higher Education, Low Volume Mixed, Marketing, Polling and Voting, Public Service Announcement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Low - Medium volumes, 2FA, Non-Marketing &amp; Marketing, Customer Service, Alert Notifications                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | High Volume School/Flight/Appt reminders                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Approval Process             | To send messages via this route, it is necessary to register brands and campaigns with TCR (The Campaign Registry) as required by the Operators and interconnected gateways. TCR is an independent registry authorized to register brands and campaigns with T-Mobile and AT&amp;T. Although Verizon, the other major USA operator, is currently not participating, registration requirements are not as strict at this time. Clients must show their opt-in process and ability to handle auto responders for HELP/STOP/CANCEL and maintain opt-out databases per campaign.                                                                                                                                                                                                                                                                                  | To send messages through this route, we must obtain approval from the toll-free gateway for our campaigns. Although they require less information than TCR for 10DLC, their content guidelines are still strict. If the campaign volume is less than 25,000 per month, we can proceed without official gateway approval, but we must adhere to all regulations, and our support department must review the verification form submitted.                                                                                                                                                                                                                                                                                                                             | To send messages through this route, we must obtain campaign approval from the Operators.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Time to register             | 2-7 business days                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 5-15 business days                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 1-2 months                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Canadian Reach               | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | No (User must purchase a Canadian Short Code)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 2-Way Possible               | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Concatenated                 | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Unicode                      | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| How to order                 | Email your request to [sales@moceanapi.com](mailto:sales@moceanapi.com)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Download TFN registration form [here](https://docs.google.com/document/d/1I37LP5jF4fnpno9FUcvcQ0p06oGtOqhZ/edit?usp=sharing&ouid=115964922142813966781&rtpof=true&sd=true)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Email your request to [sales@moceanapi.com](mailto:sales@moceanapi.com)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |


**Did not find what you're looking for ?**

Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feature Request
Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feedback
Send feedback to our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).
