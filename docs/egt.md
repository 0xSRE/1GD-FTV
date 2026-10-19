# Exhaust Gas Temperature (EGT)

> **Status:** Toyota does not publish an EGT limit for the 1GD-FTV. The ECU protects the engine itself by pulling fuel and limiting power. The limits below are community and tuner guidance for towing and modified engines.

## Factory EGT sensors

Depending on emissions level, the 1GD-FTV has thermistor-type exhaust temperature sensors at:

1. Before the DOC (oxidation catalyst)
2. Before the DPF
3. After the DPF
4. After the SCR catalyst (Euro 6 only)

On a stock vehicle you can read these sensors with an OBD2 app or scanner that supports Toyota enhanced PIDs. They are all **downstream of the turbo**, so they read lower than the manifold (pre-turbo) temperature.

## Where the probe sits matters

| Probe location | Reads | Notes |
|---|---|---|
| **Pre-turbo** (exhaust manifold) | Highest | Best indicator of piston and turbine stress. Usual spot for an aftermarket EGT gauge |
| **Post-turbo** (dump pipe / before DOC) | About 140–195 °C (250–350 °F) lower than pre-turbo under load | Where the factory sensors are. Lags during transients |

Always say which location an EGT number refers to.

## Guidance (pre-turbo probe)

| Range | Meaning | Source |
|---|---|---|
| Below 550 °C | Normal driving, light load | [Community] |
| 550–650 °C | Highway cruising, moderate towing. Fine to sustain | [Community] |
| 650–700 °C | Heavy towing or long climbs. Watch it. Back off or change down a gear if it keeps rising | [Community] |
| Above 720 °C | Upper limit commonly quoted for sustained running. Ease off | [Community] |
| Above 750 °C | Only acceptable for short bursts. Repeated or long exposure risks turbine, piston and manifold damage | [Community] |

Post-turbo readings will be roughly 150–200 °C lower than these at the same load.

### Reducing EGT

- **Change down a gear.** Higher rpm with less throttle runs cooler than lugging at low rpm with full throttle.
- **Use less throttle** on long climbs.
- **Keep intake air and intercooler airflow clear.** Dirty intercooler fins or a boost leak (such as a split hose or the known loose boost sensor hose) mean less air and hotter exhaust.
- **Check tunes carefully.** Extra fuel without extra air is the most common cause of high EGT on modified 1GDs.
- **Cool down before shutting off.** Idle 30–60 s after high EGT so the turbo bearings aren't heat-soaked.

## DPF regeneration temperatures

On Euro 5 and Euro 6 engines, high exhaust temperatures during regeneration are normal and intended:

| Item | Value | Source |
|---|---|---|
| Active regeneration temperature (at DPF) | About 600–700 °C | [Spec sheet] |
| How it is done | Extra post-injections plus a separate exhaust fuel injector (the fifth injector) | [Spec sheet] |
| Passive regeneration | Happens on its own during sustained high-load or highway driving | [Spec sheet] |

During active regeneration, the pre-DPF and post-DPF sensors will read well above normal cruising values. **This is not an over-temperature fault.** Don't stop the engine in the middle of a regeneration if you can avoid it. If regeneration keeps failing, the DPF warning light flashes and the ECU goes into limp mode (see [known-issues.md](known-issues.md)).

## Sources

- [Toyota-Club: GD engine FAQ](https://toyota-club.net/files/faq/15-10-20_faq_gd-engine_eng.htm): sensor locations, regeneration temperatures
- [HP Academy: What is a safe EGT for my diesel engine?](https://hpacademy.com/technical-articles/what-is-a-safe-egt): pre- vs post-turbo offset
- [NissanPatrol.com.au: EGT safe temps](https://www.nissanpatrol.com.au/forums/archive/index.php/t-11949.html): community limits
