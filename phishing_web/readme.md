# Phishing Awareness Educational Project

This project is designed to simulate a phishing attack for educational purposes. The objective is to raise awareness about phishing and demonstrate how attackers might try to deceive users into providing their sensitive information. This project includes a fake email phishing attempt and a webpage that collects username and password details using a webhook.

## Project Overview

### Fake Email Phishing

A fake phishing email was created to mimic a typical phishing attack. The email urges recipients to verify their account information by clicking on a link that leads to a phishing webpage.

### Phishing Webpage

The phishing webpage is designed to look like a legitimate login page. When users enter their username and password, these details are captured and sent to a webhook URL.

### Webhook Integration

A webhook is used to collect the submitted username and password. This allows the demonstration of how sensitive information can be captured during a phishing attack.

## Project Components

1. **Fake Phishing Email**
    - A sample email text that mimics a phishing attempt.
    - The email includes a link to the phishing webpage.

2. **Phishing Webpage**
    - An HTML page designed to look like a legitimate login page.
    - CSS for styling the page to make it visually appealing and realistic.

3. **Webhook Integration**
    - A form on the phishing webpage that submits user data to a specified webhook URL.
    - Captures and logs the username and password entered by the user.

## How It Works

1. **Create the Phishing Email**
    - A sample phishing email is crafted to look authentic and convincing.
    - The email contains a link to the phishing webpage.

2. **Set Up the Phishing Webpage**
    - The webpage is hosted on GitHub Pages at the following URL: [Phishing Page](https://malsaleh88.github.io/phishing.io/).
    - The form action in the HTML is set to send a POST request to the webhook URL.

3. **Capture Data with Webhook**
    - The webhook URL is configured to receive the form data (username and password).
    - When a user submits the form, the data is sent to the webhook and logged for demonstration purposes.

### Sample Email Content

![email](https://github.com/malsaleh88/BXL-k4MK4r-2/assets/141853984/4095bb04-3561-4d47-9253-5ccd4fe5f7a8)



![facebook png](https://github.com/malsaleh88/BXL-k4MK4r-2/assets/141853984/066d86f0-dde7-4705-a4c7-ad50d1bd9d81)

![pass](https://github.com/malsaleh88/BXL-k4MK4r-2/assets/141853984/d7533f77-5a8e-443c-9c6a-ee19e04dda7f)

![webhookfff](https://github.com/malsaleh88/BXL-k4MK4r-2/assets/141853984/510c00ab-9e7e-40da-af77-f5c10c328cbc)



## Try It!

You can try it via this [website link](https://malsaleh88.github.io/phishing.io/). Don't put your actual credentials (-_-).

