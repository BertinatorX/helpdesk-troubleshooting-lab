# Practice Ticket: DNS Resolution Issue

## Ticket summary

User can connect to the network but cannot open websites by name.

## User impact

The user cannot access web applications needed for daily work.

## Environment

- Device: Laptop
- Network: Office Wi-Fi
- Symptoms: Can ping an IP address but cannot load websites by domain name

## Initial questions

1. Are other websites affected?
2. Is anyone else nearby having the same issue?
3. Does the issue happen on wired and wireless connections?
4. Did the device recently connect to a VPN?

## Troubleshooting steps

1. Confirmed network connection.
2. Tested IP connectivity with `ping 1.1.1.1`.
3. Tested DNS resolution with `nslookup example.com`.
4. Checked DNS server settings.
5. Flushed DNS cache.
6. Retested domain lookup and website access.

## Resolution

The issue was resolved after correcting DNS settings and refreshing the DNS cache.

## Verification

The user confirmed that websites loaded normally after the fix.

## Escalation notes

If DNS still failed, escalate with IP configuration, DNS server address, error messages, and whether other users were affected.

## User-facing response

I found that the laptop had network connectivity but was not resolving website names correctly. I refreshed the DNS settings and confirmed that websites now load normally.

## What I learned

Testing IP connectivity separately from DNS resolution helps isolate whether the issue is general network access or name resolution.
