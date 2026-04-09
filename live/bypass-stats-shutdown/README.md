# Test

Check if statistics from capture-bypassed flows are gathered before a time out check.

Needs to be run with `--live` and `--out-if` cmd options with distinct interfaces. It is recommended to use loobpack between the two used interfaces.

Suricata shutdowns after `live-shutdown-after` seconds, configured in test.yaml.

## Pcap

One encrypted TCP flow -> input.pcap
