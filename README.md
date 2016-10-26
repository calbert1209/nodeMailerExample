#### Sending an Email via Node.js

Recently I learned how crazy-simple it is to send an email using a Python script.  I wondered how hard it would be to do the same in node.js and JavaScript

The answer? Almost as simple. (_Everything_ you could ever need is already included Python.) With node.js you will need to flex your npm muscles.

##### This example uses:

- [nodemailer](https://nodemailer.com/) to do the heavy lifting
- [dotenv](https://www.npmjs.com/package/dotenv) to keep my deep, dark secrets hidden
- a sandbox account set up on [MailGun](http://www.mailgun.com/) 

If you don't already have a free account on MailGun, go get one! Their limits are similar to Gmail, and their system is set up for people who want to fiddle around. Gmail is not as easy to use for the same purposes.
