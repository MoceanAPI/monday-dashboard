# Mocean monday.com SMS Broadcast User Documentation

## Looking for other documentation ?
- [MoceanAPI - SMS Broadcast Documentation](https://moceanapi.github.io/monday-dashboard/)  (Current)
- [MoceanAPI - Send SMS Documentation](https://moceanapi.github.io/monday-item/)
- [MoceanAPI - SMS Automation Documentation](https://moceanapi.github.io/monday-automation/)
- [SMS Sender ID Country List](https://moceanapi.github.io/monday/)

## Contents
- [Installation](#installation)
- [Usage](#usage)
    - [Send SMS to specific phone numbers](#send-sms-to-specific-phone-numbers)
    - [Send SMS to Board Items](#send-sms-to-board-items)
- [Whitelist IP Address](#whitelist-ip-address)
- [Frequently Asked Questions](#faq)
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

![image](https://user-images.githubusercontent.com/24620178/153548258-163372e1-5050-44db-99b9-a544878f947e.png)

1. Select `Send to board filtered by status criteria/value` from the `Send Type` dropdown list.
2. Choose the `Board` you would like to send SMS to
3. Select the `Column` you would like to filter by.
4. Select the `Criteria` you would like to send SMS to
5. Select the `Phone Column` to send SMS to and compose your SMS
6. (Optional) You can configure keywords to personalise your SMS

![image](https://user-images.githubusercontent.com/24620178/206367524-c0d4e85d-f35c-4ab6-871f-733830cbd3a0.png)

7. (Optional) Preview your SMS to see what your users will get before sending the SMS

![image](https://user-images.githubusercontent.com/24620178/206367607-4ce1bf68-33ec-41c7-a825-7867bc2c0189.png)

## Whitelist IP Address

For added security, you should whitelist `192.168.4.1` IP address in your [MoceanAPI Dashboard](https://dashboard.moceanapi.com)

To do so, follow these steps

1. Go to [MoceanAPI Dashboard](https://dashboard.moceanapi.com/user/apisetting)
2. Navigate to **API Account** 
3. Key in **`192.168.4.1`** into **Allow IP** field

![image](https://user-images.githubusercontent.com/24620178/200761674-1ccb6e6c-2d7b-499d-bef6-ee47a3e2a624.png)

## FAQ
1. Can I get Test Credits ?

You can get 20 FREE credits and credits are valid for 14 days. Subject to approval.

2. Can I send international messages?

Yes. We are an international SMS provider. You can send out SMS both locally and internationally based on our price list.

3. What is the maximum characters per SMS I can put into the message?

160 characters for a normal text message, 70 characters for a Unicode text message (Arabic, Chinese, and etc)

4. Is there a limit to how many numbers I can send at one time?

There is no limit on numbers to be sent in one go.

5. What format does my phone number need to be in?

Mobile phone numbers need to be entered in international formatting with the country code and without spaces, plus signs or leading zeros.

**Did not find what you're looking for ?**

Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feature Request
Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feedback
Send feedback to our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).
