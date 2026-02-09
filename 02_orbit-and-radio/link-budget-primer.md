# Link Budget Primer (Non-exhaustive)

## 1. Purpose
A link budget accounts for gains and losses from transmitter to receiver to estimate feasibility and margin.

## 2. Minimal terms (conceptual)
| Term | Meaning | Note |
|---|---|---|
| EIRP | Effective isotropic radiated power | TX power + antenna gain |
| G/T | Receiver figure of merit | gain / noise temperature |
| FSPL | Free-space path loss | depends on frequency and distance |
| Misc losses | Atmospheric/pointing/etc. | environment and implementation |
| C/N0 | Carrier-to-noise density | key intermediate metric |
| Eb/N0 | Energy/bit to noise density | maps to BER/BLER |

## 3. D2D-specific constraint
Handsets impose:
- small antennas,
- limited TX power,
- random orientation,
which shifts complexity to satellite payload/beamforming to preserve usability.

## 4. References (starter)
- Dragorad Milovanović: New Space SatCom / NTN&D2D (project page)
