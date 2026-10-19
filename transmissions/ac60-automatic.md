# Aisin AC60E / AC60F 6-Speed Automatic

The most common gearbox behind the 1GD-FTV. Toyota markets it as "6-speed Super ECT".

- **AC60E**: 2WD
- **AC60F**: 4WD (transfer case bolts to the extension housing)

Applications with the 1GD: Hilux (8th gen), Fortuner (2nd gen), Land Cruiser Prado 150, Land Cruiser 70 (2023/24–), Hiace.

## Design

| Item | Detail | Source |
|---|---|---|
| Gears | 6 forward, 1 reverse | [Spec sheet] |
| Gear train | 3 planetary sets, 3 brake clutches, 2 rotating clutches, 1 one-way clutch | [Spec sheet] |
| Case | Three-piece: main case, removable bell housing, extension housing | [Spec sheet] |
| Solenoids | 7 total (4 full-flow linear: SL1–SL4, plus SLT, SLU and a shift solenoid) | [Spec sheet] |
| Solenoid resistance | SL1–SL4, SLT, SLU: 5–5.5 Ω | [Spec sheet] |
| Control | TCM uses input/output speed sensors and CAN data for line pressure, shift timing and lock-up | [Spec sheet] |

## Gear ratios

| Gear | Ratio |
|---|---|
| 1st | 3.600 |
| 2nd | 2.090 |
| 3rd | 1.488 |
| 4th | 1.000 |
| 5th | 0.687 |
| 6th | 0.580 |
| Reverse | 3.732 |

**[Unverified]**: these are the commonly quoted AC60 ratios, but no primary source was found. Check them against the Toyota repair manual.

## Fluid

| Item | Value | Source |
|---|---|---|
| Fluid | Toyota ATF WS (or an approved WS-grade equivalent such as Aisin ATF6+ FE WS) | [Spec sheet] / retailer |
| Level check | No dipstick. Check at the fill/overflow plug at a set fluid temperature (see repair manual) | [Community] |
| Service | Toyota calls WS "lifetime" fill, but owners who tow or go off-road commonly change it every 60,000–80,000 km | [Community] |

Never use Dexron or T-IV fluid in a WS transmission.

## Behaviour and common complaints

- **Durable.** Major internal failures are uncommon in stock vehicles.
- **"Busy" or laboring feel.** The TCM shifts up early and locks the converter by about 50 km/h (30 mph) to save fuel, so it can feel sluggish in traffic. **PWR/Sport mode** holds gears longer.
- **Heat when towing.** Converter slip at heavy load on long climbs raises fluid temperature. A transmission temperature gauge (via OBD) is worth having for towing. Use manual mode (S) to hold a lower gear and keep the converter locked.
- **TCM updates.** Check for the latest TCM software before diagnosing shift-quality problems.
- **Upgrades.** Aftermarket heavy-duty valve bodies (e.g. Nomad) firm up shifts and reduce slip when towing.

## Sources

- [Gears Magazine: The Toyota AC60E: Simpler Can Be Better!](https://gearsmagazine.com/magazine/the-toyota-ac60e-simpler-can-be-better/)
- [Gears Magazine: Diagnosing Toyota AC60 Issues](https://gearsmagazine.com/magazine/diagnosing-toyota-ac60-issues/)
- [Automatic Transmission (AU): AC60 Nomad valve body fitting instructions](https://automatictransmission.com.au/wp-content/uploads/2021/07/Aisin-AC60-Nomad-Valve-Body-Fitting-Instructions.pdf)
- [Roughtrax 4x4: Aisin ATF6+ FE WS fluid](https://www.roughtrax4x4.com/oil017-5-litres-aisin-automatic-transmission-fluid-atf6-fe-ws-grade.html)
