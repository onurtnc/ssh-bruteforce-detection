## Incident Summary
Multiple failed SSH login attempts were detected from a single IP address
within a short time window.

## Analysis
The attacker attempted to authenticate as the root user repeatedly.
The frequency and pattern indicate an automated brute force attack.

## Impact
If successful, the attacker could gain unauthorized access to the server.

## Recommendation
- Block the attacking IP
- Disable root login over SSH
- Enforce key-based authentication

## Lessons Learned
This project improved my ability to detect suspicious authentication
patterns and think from a SOC analyst perspective.
