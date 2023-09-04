# cifido2rp

This is a demonstration Node.js application that shows consumption of basic user and FIDO2 APIs from a cloud identity tenant.

A modified version of the original from https://github.com/sbweeden/cifido2rp

This version is a complete passwordless example. Instead of using a username/password for authentication, it uses emailaddress/OTP as first authentication. If the user does not already exist in IBM Security Verify SaaS, he/she will automatically be created, but will not receive an initial password.

Once the user is logged in, he/she can add a passkey to their account.
