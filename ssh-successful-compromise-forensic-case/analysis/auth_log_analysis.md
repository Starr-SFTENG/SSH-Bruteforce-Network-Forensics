# Authentication Log Analysis

## Confirmed Unauthorized Login

The following log entry confirms successful SSH authentication:

Accepted password for testuser from 192.168.56.102 port 49752 ssh2

- Username: testuser
- Source IP: 192.168.56.102
- Authentication method: Password
- Timestamp: 2025-12-24 12:48:32 UTC

## Session Lifecycle

- Session opened: 12:48:32
- Session closed: 12:58:07
- Session duration: ~9 minutes 35 seconds

## Privilege Escalation Attempts

The attacker attempted privilege escalation:

testuser : user NOT in sudoers ; COMMAND=/usr/bin/su  
testuser : user NOT in sudoers ; COMMAND=/usr/sbin/adduser backdoor

Result:
- Privilege escalation failed
- No evidence of successful root access
- Backdoor user creation attempt denied

## Conclusion

The logs confirm a successful SSH compromise with post-authentication activity.
