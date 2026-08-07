# Bill of Materials — Holding Cabinet (Proofer)

**Status:** Living doc — update as parts are selected. Once a full board
exists, prefer exporting BOM directly from KiCad and treat this file as a
narrative supplement (rationale/status), not the source of truth.

Status key: 🔒 Locked · 🟡 Open (narrowing) · ⬜ Deferred (pending test)

## MCU / Core

| Part | Status | Notes |
|---|---|---|
| STM32C031C6 | 🔒 | Production MCU |
| NUCLEO-L476RG (STM32L476) | 🔒 | Dev board only |

## Display

| Part | Status | Notes |
|---|---|---|
| Kingbright CA56-12EWA | 🔒 | Common-anode 4-digit 7-seg |
| AO3401A (P-MOSFET) | 🔒 | Digit-common high-side switching |
| MMBT3904 (NPN, SOT-23) | 🔒 | Per-segment channel driver |

## Heating

| Part | Status | Notes |
|---|---|---|
| Silicone rubber heater pad | 🔒 | On anodized aluminum base plate |
| Heater driver (SSR/MOSFET) | 🟡 | Not yet selected |

## Fan

| Part | Status | Notes |
|---|---|---|
| PWM-controlled DC muffin fan | 🔒 (approach) | Specific part TBD |
| Fan driver | 🟡 | Not yet selected |

## Sensing

| Part | Status | Notes |
|---|---|---|
| BME280 (temp/humidity) | 🟡 | Placement deferred to physical test |

## Connectivity (Models 3–4 only)

| Part | Status | Notes |
|---|---|---|
| Wi-Fi/BLE module | 🟡 | Narrowing — companion module owns stack, unmodified (see RISK-001 in firmware repo) |

## Enclosure

| Part | Status | Notes |
|---|---|---|
| PETG enclosure | 🔒 | Material only |
| Lid window (clear insert) | ⬜ | Material deferred |
| Feet | ⬜ | Design deferred |

## Power

| Part | Status | Notes |
|---|---|---|
| Power supply | ⬜ | Voltage/wattage deferred to physical test |
