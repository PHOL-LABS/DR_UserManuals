# Mk2 Pinout Reference

This guide captures the dual-connector pin assignments used by Replica Gen One dashboards. Mk2 installations typically use the white and black connectors shown here. Verify connector orientation and wire colors before final assembly.

## White connector

| Pin | Assignment |
| --- | --- |
| 1 | Blinker output, tied to ground for the indicator lamp. |
| 2 | Frei — not connected. |
| 3 | Terminal 58, positive supply for the panel backlight. |
| 4 | Resistive coolant temperature sensor input. |
| 5 | Resistive fuel level sensor input. |
| 6 | Ground return. |
| 7 | Additional ground return. |
| 8 | Terminal 1 engine-speed signal (coil, distributor, or other waveform up to 12 V with possible 300 V spikes). |
| 9 | MFA mode line used to change MFA functions. |
| 10 | UNR permanent positive supply (unused on Replica Gen One short, main supply on Replica Next short). |
| 11 | MFA temperature “+” lead for the ambient sensor (Replica Next short). |
| 12 | MFA oil temperature sensor lead (Replica Next short only). |
| 13 | KL 56a high-beam indicator input (+12 V active). |

## Black connector

| Pin | Assignment |
| --- | --- |
| 1 | Terminal 15 switched +12 V from the ignition switch. |
| 2–4 | Not connected. |
| 5 | Handbrake indicator input (active low). |
| 6 | KL 61 generator warning lamp drive with 120 Ω excitation resistor. |
| 7 | Oil pressure switch, 0.3 bar. |
| 8 | Oil pressure switch, 1.8 bar. |
| 9 | Not used. |
| 10 | Glow-plug indicator input (+12 V active, diesel only). |
| 11 | Hall sensor input for optional speed sensors. |
| 12 | MFA block selection line. |
| 13 | MFA reset line. |
