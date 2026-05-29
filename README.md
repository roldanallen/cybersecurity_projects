## Host-Based Event Analysis
Windows Security Event Log auditing intercepted the behavior perfectly, recording 10 consecutive instances of Event ID 4625.

![Windows Event Viewer displaying Audit Failures](event_viewer.png)

---

## Visibility & Telemetry Gap Analysis
Because the traffic stayed internal, standard Npcap bindings failed to capture application-layer SMB2 protocol handshakes.

![Wireshark interface showing missing SMB2 packets](wireshark.png)
