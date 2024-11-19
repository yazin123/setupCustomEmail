# setupCustomEmail
Guidelines on how to setup customemail@yourdomain with a domain, cloudflare and zoho


Step 1 : Connect your domain to cloudflare by updating the nameserver (cloudflare is not required if you prefer to use the domain provider as default DNS manager)
Step 2 : Signup to Zoho mail Free version and update the DNS setup given by the zoho mail at the DNS manager. Also add your custom mail eg: hello@example.com
Step 3 : Go to your Gmail Account > Settings > Account and imports > under send mail as : click on  add another email address
Step 4 : In the Popup window, give your custom mail hello@example.com > next 
Step 5 : add the smtp server as mx.zoho.in, username as hello@example.com and password is the password you used to create the zoho mail. > next 
Step 6 : A verification mail will be received at the zoho mail. click verify link
Step 7 : good to go now
