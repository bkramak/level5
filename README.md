# level5
IEC 61400-26-1 (2019) optional level 5 suggestions


placeholder github site to record suggested level 5 categories

| IEC Level 4      | Level 5 max case   | Owner  | OEM    | DNV WIL |         | Example Client |
| :-------------- | :---------------- | :----: | :----: | :-----: | :-----: | :------------: |
| Full Performance <br>(IAOSFP)| no sub category    | A      |A       |A        |         | A              |
| Partial Performance <br>(IAOSPP)| 2.1 Derated internal – OEM operational requirement (temp/TI/etc.)    | A      |A       |A        |         | A              |
|    | 2.2 Derated external – noise   | A      |A       |A        |         | A              |
|    | 2.3 Derated external – grid curtailment   | A      |A       |A        |         | A              |
|    | 2.4 Degraded physical condition (blade issues, other)  | A      |A       |A        |         | A              |
|    | 2.5 Degraded environmental condition (icing, soiling)   | A      |A       |A        |         | A              |
|    | 2.6 Control-related – high wind hysteresis   | A      |A       |A        |         | A              |
|    | 2.7 Control-related – improper setting, inefficient algorithm | A      |A       |A        |         | A              |
|    | 2.8 Control-related – plant-level control (wake or load mgmt.)   | A      |A       |A        |         | A              |
| Ready Standby <br>(IAOSRS)   | 3. Ready to function (not used at the turbine level)  | A      |A       |X        |         | X              |
| Technical Standby <br>(IAOOSTS)   | 4.1 Automated maintenance: Cable unwind, pitch testing, etc.  | U      |A       |U       |         | A              |
|    | 4.2 Recovery from IAOOSEN after condition clears | U      |A       |U/N        |         | A              |
|  Out of Environmental Spec (IAOOSEN)  | 5.1 Calm winds  | A      |A       |  N       |       | A   |
|    | 5.2 High winds   | U      |A       | N      |         | A              |
|    | 5.3 Icing offline  | U      |A       | N      |         | A              |
|    | 5.4 Common lightning event  | U      |A       | N      |         | A              |
|    | 5.5 High temperature   | U      |A       | N      |         | A              |
|    | 5.6 Low temperature   | U      |A       | N      |         | A              |
|    | 5.7 Other environmental   | U      |A       | N      |         | A              |
| Requested Shutdown <br> (IAOOSRS) | 6.1 Owner-directed shutdown <br>– visit / training / other   | U      |A       | N      |         | A              |
|  | 6.2 OEM-directed non-maintenance shutdown <br>– visit/ training/ other  | U      |A       | N      |         | A              |
|  | 6.3 OEM-directed wind sector/load management | U      |A       | N      |         | A              |
|  | 6.4 Grid operator (curtailed non- reimbursed)  | U      |A       | N      |         | A              |
|  | 6.5 Grid operator (curtailed reimbursed) | U      |A       | N      |         | A              |
|  | 6.6 Noise  | U      |A       | N      |         | A              |
|  | 6.7 Avian or other biological  | U      |A       | N      |         | A              |
| Out of Electrical Specification (IAOOSEL)   | 7.1 BOP electrical issue (BOP availability) | U      |A       | N      |         | A              |
|   | 7.2 Grid electrical issue (grid availability) | U      |A       | N      |         | A              |
| Scheduled Maintenance (IANOSM)  | 8.1 Monthly/quarterly| U      |A       | N      |         | A              |
|   | 8.2 Annual/ semi annual | U      |A       | N      |         | A              |
|   | 8.3 Startup / EOW | U      |A       | N      |         | A              |
|   | 8.4 Other | U      |A       | N      |         | A              |
| Planned Corrective Action (IANOPCA)  | 9.1 Action to correct Forced Outage, once scheduled and parts on hand | U      |A       | N      |         | A              |
|   | 9.2 Retrofit/upgrade charge to owner | U      |A       | N      |         | A              |
|   | 9.3 Retrofit/upgrade charge to OEM | U      |A       | N      |         | A              |
| Forced Outage (IANOFO)  | 10.1 Response delay | U      |A       | N      |         | A              |
|   | 10.2 Diagnostic time & awaiting parts (under normal conditions) | U      |A       | N      |         | A              |
|   | 10.3 Logistical delay | U      |A       | N      |         | A              |
|   | 10.4 Failure repair | U      |A       | N      |         | A              |
| Suspended (IANOS)  | 11.1 Awaiting parts – supply issue (for sched., planned, or forced) | U      |A       | N      |         | A              |
|   | 11.2 Awaiting serial defect resolution (for planned corrective) | U      |A       | N      |         | A              |
|   | 11.3 Other reason incl. site access | U      |A       | N      |         | A              |
|  Force Majeure (IAFM) | 12.1 Weather Event - Tornado, Hurricane | U      |N      | N      |         | N             |
|  | 12.2 Fire – equipment, general area| U      |N      | N      |         | N              |
|  | 12.3 Earthquake, flood | U      |N      | N      |         | N              |
|  | 12.4 Pandemic / Epidemic| U      |N       | N      |         | N             |
|  | 12.5 Civil Unrest| U      |N       | N      |         | N             |
|  | 12.6 Extreme lightning event | U      |N       | N      |         | N              |
|  | 12.7 Other “Act of God” or insured events | U      |N      | N      |         | N              |
| Information Unavailable (IU) | 13.1 No communications / missing datapoint | N     |N       | U/N      |         | N              |
| | 13.2 Spurious reading | N      |N       | U/N      |         | N              |

