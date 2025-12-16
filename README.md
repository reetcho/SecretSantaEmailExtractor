# Secret Santa Email Generator (Jupyter Notebook)

This is a simple Jupyter Notebook to create a Secret Santa through email. It allows you to add all participants’ names and their email addresses, and it automatically assigns a receiver for each participant. Then, it sends an email to each participant with the name of their assigned receiver.

## How to use

- In the first three cells you can:
  - Set the email address you will use to send all the emails
  - Set the message that will be sent via email
  - Add the names and email addresses of all the participants

- For sending the emails, it is **recommended to use a Gmail address**. Simply entering the email and password will not work. To make it work:
  - Go to Manage your Google Account → Security & Sign-in
  - Enable **2-factor authentication**
  - Create an **App Password**
  - Google will provide a password in this format: `"aaaa bbbb cccc dddd"`
  - **Remove the spaces** to get: `"aaaabbbbccccdddd"`
  - Use this password in the code to log in to the email

- After setting the email credentials, set the email message and the names and emails of participants. You are now ready to run the notebook and send the Secret Santa emails!

## Note

- If any of the participants’ email addresses are incorrect, the sending email account will receive a message saying the email could not be delivered.  
- Make sure all participants’ names are unique to avoid confusion when assigning Secret Santa pairings.
