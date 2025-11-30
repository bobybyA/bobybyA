# Formspree Setup Instructions

To enable the contact form to send emails directly to bodybya9@gmail.com without opening any email client, follow these simple steps:

## Step 1: Create Formspree Account

1. Go to https://formspree.io/
2. Click **"Sign Up"** (it's free - 50 submissions/month on free plan)
3. Create an account with your email

## Step 2: Create a New Form

1. After logging in, click **"New Form"**
2. You'll see a form endpoint like: `https://formspree.io/f/xxxxxxxxxx`
3. Copy this endpoint URL

## Step 3: Update Your Code

1. Open `index.html`
2. Find this line in the form:
   ```html
   <form class="contact-form" id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
3. Replace `YOUR_FORM_ID` with your actual Formspree form ID (the `xxxxxxxxxx` part)

   Example:
   ```html
   <form class="contact-form" id="contactForm" action="https://formspree.io/f/mnopqrstuv" method="POST">
   ```

## Step 4: Configure Email Settings

1. In Formspree dashboard, go to your form settings
2. Under **"Email Notifications"**, make sure it's set to send to: **bodybya9@gmail.com**
3. The form already has a hidden field `_to` set to `bodybya9@gmail.com`, but you can also set it in Formspree settings

## Step 5: Test the Form

1. Save your changes
2. Push to GitHub
3. Test the form on your live website
4. Check bodybya9@gmail.com for the test email

## That's It!

Your form will now send emails directly to bodybya9@gmail.com when someone clicks "APPLY HERE" - no email client will open, and the submission happens instantly!

**Note:** On the free plan, Formspree requires email verification for the first submission. After that, all submissions go through automatically.

