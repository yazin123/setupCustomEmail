# Custom Email Setup Guide with Cloudflare and Zoho Mail

## Prerequisites
- A domain name
- Cloudflare account (optional)
- Zoho Mail account
- Gmail account (for sending emails)

## Step-by-Step Setup

### Step 1: Domain DNS Configuration
- Connect your domain to Cloudflare by updating the nameservers
- *Note: Cloudflare is optional; you can use your domain provider's DNS management*

### Step 2: Zoho Mail Setup
1. Sign up for Zoho Mail (Free version)
2. Update DNS settings provided by Zoho Mail in your DNS manager
3. Add your custom email address (e.g., hello@example.com)

### Step 3: Gmail Configuration
1. Open Gmail and go to Settings
2. Navigate to "Accounts and Import"
3. Click "Add another email address" under "Send mail as"

### Step 4: Add Custom Email to Gmail
1. In the popup window, enter your custom email (hello@example.com)
2. Click "Next"

### Step 5: SMTP Server Configuration
1. Enter SMTP server details:
   - SMTP Server: mx.zoho.in
   - Username: hello@example.com
   - Password: Your Zoho Mail account password
2. Click "Next"

### Step 6: Verification
- Check your Zoho Mail inbox for a verification email
- Click the verification link

### Step 7: Confirmation
- Your custom email is now set up and ready to use in Gmail

## Troubleshooting
- Ensure DNS settings are correctly configured
- Verify SMTP server details
- Check spam folder if verification email is not received

## Additional Tips
- Keep your Zoho Mail account credentials secure
- Regularly check email forwarding and sending settings
