# Practice Ticket: DNS Resolution Issue

## Ticket summary

User is on the network but can't open websites by name.

## User impact

The user can't get to the web applications they need for daily work.

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

Fixed by correcting the DNS settings and refreshing the DNS cache, nothing more was needed.

## Verification

The user confirmed websites loaded normally after the fix.

## Escalation notes

If DNS still failed after that, I'd escalate with the IP configuration, DNS server address, error messages, and whether other users were affected.

## User-facing response

I found that the laptop had network connectivity but was not resolving website names correctly. I refreshed the DNS settings and confirmed that websites now load normally.

## What I learned

Testing IP connectivity separately from DNS resolution is what made this one quick. Ping to an IP worked and names didn't, so I knew the network itself was fine and the problem was name resolution.
