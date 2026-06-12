# Home Lab 006 - Linux Log Analysis

## Objective

Learn how to inspect and analyze Linux system logs using command-line tools.

## Exercises

### Exercise 1 - System Log Investigation

Findings: 

- Reviewed recent Linux system logs using journalctl
- Identified multiple warning and failed events
- Observed AppArmor security denials
- Investigated SSH-related logs
- No failed SSH login attempts were found


## Lessons Learned

- Linux stores system activity in logs accessible through journalctl
- grep can quickly filter relevant security events
- Failed events do not always indicate an attack
- DENIED events often represent security controls working correctly
- SSH login activity can be investigated through system logs
