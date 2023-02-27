
## Firewall Actions

### Allow 
Allows the traffic to pass through the firewall.

### Block 
Blocks the traffic and generates a log entry and/or alert. 
"Send error msg to the src"

### Drop
Drops traffic without sending a response to the source, effectively blocking the traffic.

### Permit
Allows traffic to pass through the firewall.

### Close
Used to terminate network connection based on a specific rule.

### IP-conn
This action is used when the firewall allows traffic to pass through but the session is closed because the FortiGate didn't receive any reply packet.

### Monitor
Logs the traffic but doesn't block or allow it.


Understanding firewall actions is a critical skill for SOC analysts, as it can help you create effective firewall rules, analyze firewall logs, respond to security incidents, and develop security policies.