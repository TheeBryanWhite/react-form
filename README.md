# Component: React Form
This is a fully-functional boilerplate contact form for use in React and Gatsby projects. It features a basic honeypot spam filter measure and validation for empty fields, email addresses, and phone numbers.

# Serverless
There is a configuration file in the `./siler-mailer` folder that is ready to deploy, if you're into that sort of thing.

# AWS Lambda
There is a node mailer function in the `./site-mailer` folder that requires a couple of tweaks (e.g. recipient email addresses) but is also ready to deploy to a Lambda function. No testing is necessary when used in conjunction with the form component.
