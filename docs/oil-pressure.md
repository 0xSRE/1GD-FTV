# Oil Pressure and Lubrication

## Oil pressure

> **Status:** No Toyota repair manual figure for the 1GD-FTV has been confirmed yet. The values below are the best available references. Replace them with the TIS figures once you have them (Engine Mechanical → Lubrication → Oil Pressure inspection).

Toyota usually gives oil pressure as two numbers, both measured with the engine at normal operating temperature (oil about 80 °C):

1. a **minimum at idle**
2. a **range at 3,000 rpm**

| Condition | Value | Source |
|---|---|---|
| Hot idle | 29 kPa (0.3 kgf/cm², 4.3 psi) **or more** | [Unverified]: Toyota repair-manual figure quoted on a forum; engine not named |
| 3,000 rpm, hot | 245–490 kPa (2.5–5.0 kgf/cm², 36–71 psi) | [Unverified]: same source |
| Hot idle, aftermarket gauge | About 140–200 kPa (20–30 psi) | [Community]: typical Toyota diesel owner readings |
| Cruising, hot | About 240–275 kPa (35–40 psi) | [Community] |

### Reading the numbers

- **Cold oil reads high.** Pressure falls as the oil warms up. Compare readings only once the engine is at full temperature.
- **2020-on engines have a two-stage oil pump.** The ECU switches the pump between low- and high-pressure modes (for example, to run the piston oil jets under load). Pressure changing at constant rpm can be normal on these engines.
- **The dash warning light is a pressure switch, not a gauge.** It only comes on when pressure is near zero. If you want real numbers, fit a mechanical or electronic gauge at the oil pressure switch port, and check it against a known-good mechanical gauge.
- **Spurious P052477 low-oil-pressure code (2020-on):** Toyota fixed a false low-pressure DTC by reflashing the ECU's detection threshold (TSB EG-00545T-TME). Check that before replacing parts. See [known-issues.md](known-issues.md).

### When to worry

- The oil warning light comes on while the engine is running: **stop the engine straight away.**
- Hot idle pressure is clearly lower than your engine's usual baseline, or below the factory idle minimum.
- Pressure at 3,000 rpm is below the factory range.
- Pressure drops over time. Likely causes are fuel dilution (frequent DPF regeneration on short trips thins the oil), the wrong viscosity, a blocked pickup, or worn bearings.

The best thing you can do is **record your own baseline** while the engine is healthy: hot idle and 3,000 rpm, at a known oil temperature.

## Oil specification and capacity

| Item | Value | Source |
|---|---|---|
| Capacity (drain and refill with filter) | About 7.5 L | [Unverified]: single spec-sheet source; varies by model and sump |
| Viscosity, DPF engines | 0W-30 (5W-30 in some markets) | [Spec sheet] / owner's manual |
| Oil type, DPF / Euro 5–6 engines | **Low-ash** oil: ACEA C2/C3 or JASO DL-1 | Owner's manual. Confirm for your market |
| Oil type, non-DPF markets | Higher-ash diesel oils (e.g. API CF-4 or later) may be allowed. Check the owner's manual | Owner's manual |

Using a high-ash oil in a DPF engine speeds up DPF ash loading. Check the owner's manual for your VIN and market. It is the authoritative source for oil grade and capacity.

## Lubrication hardware

- Trochoid oil pump, gear-driven from the crankshaft.
- Engine oil cooler on the front of the block.
- Piston cooling oil jets. On the 2020 update they run when the pump is in high-pressure mode.
- Water- and oil-cooled turbo. Let the engine idle for 30–60 s after hard running or towing before shutting it down.

## Sources

- [Toyota-Club: GD engine FAQ](https://toyota-club.net/files/faq/15-10-20_faq_gd-engine_eng.htm): oil pump design, TSB EG-00545T-TME
- [ToyotaNation: Interesting Oil Pressure Info](https://www.toyotanation.com/threads/interesting-oil-pressure-info.371927/): quoted repair-manual figures
- [Sensorgal: Prado 1GD-FTV oil pressure switch](https://www.sensorgal.com/oil-pressure-switch-for-landcruiser-prado-1kzte-1g)
- [NewHilux.net: oil pressure thread](https://www.newhilux.net/phpbb/viewtopic.php?t=14894)
- [Papa's Road Trip: normal oil pressure at idle](https://papasroadtrip.com/normal-oil-pressure-at-idle/)
- [MyMotorList: Toyota 1GD-FTV](https://mymotorlist.com/engines/toyota/1gd-ftv/): oil capacity
