WART
====

WhatsApp Registration Tool

![WART](https://f.cloud.github.com/assets/1610953/1016583/bfb519ec-0bfd-11e3-8c42-3b44f0014e90.png)

Uses WhatsApiNet library https://github.com/shirioko/WhatsAPINet

This tool is used to register new phonenumbers and can also be used to retrieve a new password for already registered numbers.

The registration identity is auto-generated by the program based on the phone number.

The optional (and highly recommended) password field is used as salt when generating the identity. This will generate a unique identity hash which cannot be replicated unless you know the password.

Leaving the password field blank will generate an identity hash of just the phone number, which can be easily replicated and is highly insecure.
