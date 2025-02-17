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
The price for each country varies, do check out our pricing list [here](https://moceanapi.com/pricing)

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
- Steps:
1) Complete the number registration form available [here](https://docs.google.com/document/d/1b-VJCcCGcNgHXgm2dmelWW6m0vsN6Kfg/edit) 
2) Proceed with the payment.
3) After your registration is accepted and approved, you’ll be able to send and receive SMS using your Toll Free Number.

13. **What is the expected timeframe for number approval?**
- The duration varies, but typically it takes approximately 2-3 weeks.

14. **I am currently having an US / Canada TFN / 10DLC from another provider. I want to use the same number on your platform. Is that possible?**
- Yes, it is possible. We would need a LoA (Letter of Agency) signed to allow us to take over the SMS part of the number. Please [contact us](mailto:support@moceanapi.com?cc=sookchin@moceansms.com) for further assistance.
  
15. **Why my SMS failed to deliver?**
- You may have set an invalid sender ID, alphanumeric sender ID must be less than 12 characters, and numeric sender ID must be less than 16 characters. Another common issue is you did not specify the correct phone number format including country code. Example: Country code 60 for country Malaysia, 60123456789
  
16. **I would like to send my content to the US and Canada, but it has been changed to 'Customer ABC just booked an appointment'. May I know why?**
 - This occurs because, during the trial period, your content is automatically replaced with that message. To comply with regulations, you will need to purchase a number and verify your use case in order to send your own content. You can download the necessary form [here](https://docs.google.com/document/d/1b-VJCcCGcNgHXgm2dmelWW6m0vsN6Kfg/edit), and we’ll assist you in obtaining a Toll-Free number. Once you have it, you’ll be able to send your content freely.

17. **I want to purchase SMS credits, how to top up my account?**
- Easy &amp; fast, just follow a few steps below:
1) Login to your account at [https://dashboard.moceanapi.com/login](https://dashboard.moceanapi.com/login) 
2) Go to Top Up page on left menu
3) Select Payment
4) Pay with credit card / PayPal
Your account will be credited instantly and enjoy texting!

18. **Why I cannot buy a Virtual Number?**
- This is due to your account is under trial mode or has insufficient balance. Please top up before proceeding with number purchase.

19. **Why I cannot get monday.com Notifications after receiving an SMS reply?**
- You will need to connect your Monday.com account with us. We have a video for you to follow along to connect your Monday.com account and MoceanAPI. Check it out [here](https://www.youtube.com/watch?v=P1DG6grBlQ0)

20. **Do I need a Virtual Number to send 1-Way SMS?**
- No, you don’t need a Virtual Number to send 1-Way SMS, unless you are sending SMS to recipients in the US &amp; Canada.

21. **Can I send SMS with shortener URL to United States (US)?**
- Public URL shorteners, such as bit.ly and TinyURL, are not allowed.
Please check [here](https://moceanapi.com/question/62) for more info. 

22. **What is forbidden message categories for SMS in the US/Canada?**
- The messaging use cases described [here](https://moceanapi.com/question/63) are strictly prohibited.
Even if your specific use case isn't explicitly listed as prohibited, certain types of message content may still face restrictions. For example, using shared or free public URL shorteners is not allowed and could result in filtering. Please make sure that any shortened URLs you use are company-branded.

23. **US Toll Free Number (TFN) SMS delivery features**

| Section| TOLL FREE|
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Introduction                 | A few years ago Operators started allowing SMS to be delivered via the toll free number pool that was previously only for voice calls. Toll free numbers are also 10 digits long but all start with one of the following dial codes: 1800, 1888, 1877, 1866, 1855, 1844 or 1833. This route allows for handset DLR (delivery receipt) instead of the less accurate gateway DLR provided on 10 DLC. The route also did not have a volume limit per sender like long codes do so it was ideal for business use. Additionally, the service comes with auto responders built in for STOP, HELP and CANCEL responses from mobile subscribers, and has a gateway maintained opt-out database per sender. The route currently has the same content restrictions as 10 DLC.  |
| Type of Number & Example | Toll-Free Number (Example: 18885555555)|                                                                                                                                                                |
| Suggested Use Cases | Low - Medium volumes, 2FA, Non-Marketing &amp; Marketing, Customer Service, Alert Notifications |
| Approval Process             | To send messages through this route, we must obtain approval from the toll-free gateway for our campaigns. Although they require less information than TCR for 10DLC, their content guidelines are still strict. If the campaign volume is less than 25,000 per month, we can proceed without official gateway approval, but we must adhere to all regulations, and our support department must review the verification form submitted. |
| Time to register             | 5-15 business days  |
| Canadian Reach               | Yes |
| 2-Way Possible               | Yes |
| Concatenated                 | Yes |
| Unicode                      | Yes |
| How to order                 | Download TFN registration form [here](https://docs.google.com/document/d/1b-VJCcCGcNgHXgm2dmelWW6m0vsN6Kfg/edit)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

24. **Can I use the same WhatsApp number on Monday.com and my WhatsApp mobile app to send messages to my customers?**
- No. Once a phone number is registered on the WhatsApp Business Platform for use with Monday.com, it can no longer be used on the WhatsApp mobile app.

**Did not find what you're looking for ?**

Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feature Request
Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feedback
Send feedback to our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).
