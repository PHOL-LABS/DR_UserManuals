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

## CE2 cluster pinout

| Cluster Pin | Function | Color (A2) |
| --- | --- | --- |
| T28/01 | Outside Air Temperature Sensor Ground | Blue/White |
| T28/02 | Coolant Level Low (1990+ only) | Violet (1989) or Red/White |
| T28/03 | Ground | Brown |
| T28/04 | MFA Switch- Reset | Gray |
| T28/05 | MFA Switch Ground, Ground for Sensors | Brown/White |
| T28/06 | MFA Switch- Function | Green/White |
| T28/07 | Speed Sensor Output | Violet |
| T28/08 | High Oil Pressure Signal | Yellow |
| T28/09 | Low Oil pressure Signal | Red/White |
| T28/10 | Tachometer | Green |
| T28/11 | MFA/Clock Constant Power | Red |
| T28/12 | Dash Lights | Gray |
| T28/13 | Start/Run Power, Fuse 16 | Black |
| T28/15 | MFA Switch- Mode | Black |
| T28/16 | Battery Light | Blue |
| T28/17 | Engine Oil Temperature | Black/White |
| T28/19 | Outside Air Temperature Sensor | Violet |
| T28/20 | Glow Plug Indicator | Green/White |
| T28/21 | Fuel Level | Blue |
| T28/23 | Coolant Temperature Sensor | Yellow/Red |
| T28/24 | Turn Signal Light | Green |
| T28/25 | High Beam Indicator Light | Blue/White |
