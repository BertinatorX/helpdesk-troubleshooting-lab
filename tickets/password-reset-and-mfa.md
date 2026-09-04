# Practice Ticket: Password Reset and MFA

## Ticket summary

User changed their password, can't sign in, and is also getting MFA prompts.

## User impact

User can't get into email or any work apps.

## Environment

- Account: Standard user account
- Service: Email and cloud applications
- Device: Work laptop and mobile phone

## Initial questions

1. When was the password changed?
2. Is the user able to sign in from any device?
3. Is MFA available on the registered phone or app?
4. Is there an account lockout message?

## Troubleshooting steps

1. Verified user identity according to support policy.
2. Checked whether the account was locked.
3. Confirmed the user was using the updated password.
4. Confirmed MFA device availability.
5. Guided the user through sign-in on one device.
6. Verified access to email and one business application.

## Resolution

Nothing exotic here, the user got in after confirming the correct password and MFA prompt.

## Verification

The user opened email and got into the applications they need, so I called it fixed.

## Escalation notes

Escalate if the MFA device is lost, suspicious login activity shows up, or account recovery needs administrator approval.

## User-facing response

Your account access has been restored. Please continue using your updated password and approve MFA prompts only when you are actively signing in.

## What I learned

I think account tickets need security awareness as much as troubleshooting, and you can't skip either side. Identity verification and MFA handling aren't places to improvise, both should follow policy. Overall an easy ticket technically, but cutting corners on the security side would be the real mistake.
