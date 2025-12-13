# Troubleshooting & Lessons Learned

## Suricata Service Failing to Start
Initial startup attempts failed due to incorrect network interface references. This was resolved by identifying the active interface and updating the configuration accordingly.

## Rule Loading Errors
Suricata failed validation when rule paths were misaligned with the active rule directory. Running configuration tests prior to service startup helped identify and correct these issues.

## Resource Constraints
Running Suricata on a low-memory virtual machine required careful configuration to maintain stability. Unnecessary features were avoided to ensure consistent operation.

## Key Takeaways
- Validate configurations before enabling services
- Confirm network interfaces in virtual environments
- Monitor system resources when deploying security tools
