# 2021 Formula 1 Finale — Abu Dhabi Grand Prix (Yas Marina) Research Brief

## Event Overview
- **Event:** 2021 Abu Dhabi Grand Prix
- **Round:** 22 of the 2021 Formula 1 season (season-closing race)
- **Circuit:** Yas Marina Circuit (circuitId: yas_marina)
- **Location:** Abu Dhabi, UAE (lat 24.4672, long 54.6031)
- **Race Date:** 2021-12-12 (13:00:00Z per the data source)
- **Constructor of the season:** (Red Bull — Max Verstappen champion)

## Race Session
- **Session:** Race
- **Session key:** Not returned by the historical sessions endpoint for 2021 (the getHistoricalSessions oracle returned no 2021 sessions; weather/telemetry probes for 2021-era keys returned no data). The race date is confirmed as 2021-12-12 (13:00:00Z) by both the race calendar and the classified race results.
- **Meeting/venue:** Yas Marina Circuit, Abu Dhabi, UAE

## Classified Race Results (Round 22, 2021)
| Pos | Driver | Constructor | Car # | Points | Time/Gap | Grid | Laps |
|-----|--------|-------------|-------|--------|----------|------|------|
| 1 | Max Verstappen | Red Bull | 33 | 26 | 1:30:17.345 | 1 | 58 |
| 2 | Lewis Hamilton | Mercedes | 44 | 18 | +2.256 | 2 | 58 |
| 3 | Carlos Sainz | Ferrari | 55 | 15 | +5.173 | 5 | 58 |
| 4 | Yuki Tsunoda | AlphaTauri | 22 | 12 | +5.692 | 8 | 58 |
| 5 | Pierre Gasly | AlphaTauri | 10 | 10 | +6.531 | 12 | 58 |
| 6 | Valtteri Bottas | Mercedes | 77 | 8 | +7.463 | 6 | 58 |
| 7 | Lando Norris | McLaren | 1 | 6 | +59.200 | 3 | 58 |
| 8 | Fernando Alonso | Alpine | 14 | 4 | +1:01.708 | 11 | 58 |
| 9 | Esteban Ocon | Alpine | 31 | 2 | +1:04.026 | 9 | 58 |
| 10 | Charles Leclerc | Ferrari | 16 | 1 | +1:06.057 | 7 | 58 |
| 11 | Sebastian Vettel | Aston Martin | 5 | 0 | +1:07.527 | 15 | 58 |
| 12 | Daniel Ricciardo | McLaren | 3 | 0 | +1 Lap | 10 | 57 |

- Race distance: 58 of 58 laps; Fastest lap: Max Verstappen, lap 39, 1:26.103 (rank 1)
- Verstappen won on the final lap, creating the notorious last-lap debate with Hamilton (who had led until Lap 53) — the title was decided by the closing laps.

## Podium — Finishing Order
1. **Max Verstappen** (Red Bull) — 26 points
2. **Lewis Hamilton** (Mercedes) — 18 points
3. **Carlos Sainz** (Ferrari) — 15 points

## Driver Profiles (as reported by the profile lookup)

### Lewis Hamilton
- **Driver ID:** hamilton
- **Permanent number:** 44
- **Three-letter code:** HAM
- **Nationality:** British
- **Date of birth:** 1985-01-07
- **Profile link:** http://en.wikipedia.org/wiki/Lewis_Hamilton

### Max Verstappen
- **Driver ID:** verstappen (max_verstappen in results)
- **Permanent number:** 3
- **Three-letter code:** VER
- **Nationality:** Dutch
- **Date of birth:** 1997-09-30
- **Profile link:** http://en.wikipedia.org/wiki/Max_Verstappen
- Note: the getDriverInfo lookup for "verstappen" returns a data quirk (Jos Verstappen, DOB 1972-03-04); the race-results lookup for max_verstappen gives the correct Max Verstappen data (permanent number 3, code VER, Dutch, DOB 1997-09-30).

### Sergio Pérez
- **Driver ID:** perez
- **Permanent number:** 11
- **Three-letter code:** PER
- **Nationality:** Mexican
- **Date of birth:** 1990-01-26
- **Profile link:** http://en.wikipedia.org/wiki/Sergio_P%C3%A9rez

## Research Trail Summary
- Race calendar (2021): Round 22 = Abu Dhabi GP, Yas Marina, 2021-12-12
- Classified results (year 2021, round 22): P1 Verstappen 26pts (1:30:17.345), P2 Hamilton 18pts (+2.256), P3 Sainz 15pts (+5.173)
- Lap times (hamilton, 2021 R22): laps 1-14 ~1:28.x position 1; lap 15 ~1:48.755 position 2 (interruption); laps 16-30 ~1:27.x position 1-2
- Circuit info: yas_marina — Yas Marina Circuit, Abu Dhabi, UAE

*Sources: F1 data source (getRaceCalendar, getHistoricRaceResults, getDriverInfo, getDriverInformation, getLapTimes, getCircuitInfo, getHistoricalSessions, getWeatherData, getRaceControlMessages, getTeamRadio, getCarData).*
