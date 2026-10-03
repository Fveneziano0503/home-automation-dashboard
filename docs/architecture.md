# Architecture

Current: local browser controls → simulated device-state functions → activity log → JSON export. No hardware, credentials, network discovery, server, or durable storage.

Planned: user-authorized device integrations → verified device capabilities and online state → requested commands → observed results → durable activity. Physical device state must be confirmed by the connected provider rather than inferred from a button click. Offline and failed commands should remain visible. Routine behavior should be configurable per device before controlling real hardware.
