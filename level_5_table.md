# level5
<b>IEC 61400-26-1 (2019) optional level 5 suggestions</b>

The IEC document has a few optional level 5 subcategories. This list is thought to be a possible 'max case' allowing ALL availability definition to be compared side by side with no ambiguity.  Where the IEC has 3 idenitiers, we've included 4 below to explicitly indentify losses that exist at a site and whether or not they are considered under the parent availability loss.

A - available <br>
U - unavailable<br>
N - not used in definition<br>
X - not a possible loss at a specific site

| IEC Level 4      | Level 5 max case   | Owner  | OEM    | DNV WIL |         | Example Client |
| :-------------- | :---------------- | :----: | :----: | :-----: | :-----: | :------------: |
| Full Performance <br>(IAOSFP)| no sub category    | A      |A       |A        |         | A              |
| Partial Performance <br>(IAOSPP)| 2.1 Derated internal – OEM operational requirement (temp/TI/etc.)    | A      |A       |A        |         | A              |
|    | 2.2 Derated external – noise   | A      |A       |A        |         |X             |
|    | 2.3 Derated external – grid curtailment   | A      |A       |A        |         | A              |
|    | 2.4 Degraded physical condition (blade issues, other)  | A      |A       |A        |         | A              |
|    | 2.5 Degraded environmental condition (icing, soiling)   | A      |A       |A        |         | A              |
|    | 2.6 Control-related – high wind hysteresis   | A      |A       |A        |         | A              |
|    | 2.7 Control-related – improper setting, inefficient algorithm | A      |A       |A        |         | A              |
|    | 2.8 Control-related – plant-level control (wake or load mgmt.)   | A      |A       |A        |         | X             |
| Ready Standby <br>(IAOSRS)   | 3. Ready to function (not used at the turbine level)  | A      |A       |X        |         | X              |
| Technical Standby <br>(IAOOSTS)   | 4.1 Automated maintenance: Cable unwind, pitch testing, etc.  | U      |A       |U       |         | A              |
|    | 4.2 Recovery from IAOOSEN after condition clears | U      |A       |U/N        |         | A              |
|  Out of Environmental Spec (IAOOSEN)  | 5.1 Calm winds  | U      |A       |  N       |       | N   |
|    | 5.2 High winds   | U      |A       | N      |         | N              |
|    | 5.3 Icing offline  | U      |A       | N/U      |         | U              |
|    | 5.4 Common lightning event  | U      |A       | U/N      |         | A              |
|    | 5.5 High temperature   | U      |A       | N      |         | N             |
|    | 5.6 Low temperature   | U      |A       | N      |         | N              |
|    | 5.7 Other environmental   | U      |A       | N      |         | N              |
| Requested Shutdown <br> (IAOOSRS) | 6.1 Owner-directed shutdown <br>– visit / training / other   | U      |A       | U     |         | U             |
|  | 6.2 OEM-directed non-maintenance shutdown <br>– visit/ training/ other  | U      |A       | U      |         | U             |
|  | 6.3 OEM-directed wind sector/load management | U      |A       | U      |         | X              |
|  | 6.4 Grid operator (curtailed non- reimbursed)  | U      |A       | N      |         | X              |
|  | 6.5 Grid operator (curtailed reimbursed) | U      |A       | N      |         | X              |
|  | 6.6 Noise  | U      |A       | N      |         | X             |
|  | 6.7 Avian or other biological  | U      |A       | N      |         | X             |
| Out of Electrical Specification (IAOOSEL)   | 7.1 BOP electrical issue (BOP availability) | U      |A       | N      |         | U             |
|   | 7.2 Grid electrical issue (grid availability) | U      |A       | N      |         | U             |
| Scheduled Maintenance (IANOSM)  | 8.1 Monthly/quarterly| U      |N       | U     |         | U             |
|   | 8.2 Annual/ semi annual | U      |N       | U      |         | U              |
|   | 8.3 Startup / EOW | U      |N      | U      |         | U              |
|   | 8.4 Other | U      |N       | U      |         | U              |
| Planned Corrective Action (IANOPCA)  | 9.1 Action to correct Forced Outage, once scheduled and parts on hand | U      |U      | U      |         | U              |
|   | 9.2 Retrofit/upgrade charge to owner | U      |U       | U     |         | U             |
|   | 9.3 Retrofit/upgrade charge to OEM | U      |U       | U     |         | U              |
| Forced Outage (IANOFO)  | 10.1 Response delay | U      |U      |U      |         | U             |
|   | 10.2 Diagnostic time & awaiting parts (under normal conditions) | U      |U       | U     |         | U             |
|   | 10.3 Logistical delay | U      | N      | U      |         | U              |
|   | 10.4 Failure repair | U      | N      | U      |         | U             |
| Suspended (IANOS)  | 11.1 Awaiting parts – supply issue (for sched., planned, or forced) | U      |N       | U     |         | X             |
|   | 11.2 Awaiting serial defect resolution (for planned corrective) | U      |N      | U     |         | X             |
|   | 11.3 Other reason incl. site access | U      |N       | U/N      |         |X              |
|  Force Majeure (IAFM) | 12.1 Weather Event - Tornado, Hurricane | U      |N      | N      |         | N             |
|  | 12.2 Fire – equipment, general area| U      |N      | N      |         | N              |
|  | 12.3 Earthquake, flood | U      |N      | N      |         | N              |
|  | 12.4 Pandemic / Epidemic| U      |N       | N      |         | N             |
|  | 12.5 Civil Unrest| U      |N       | N      |         | N             |
|  | 12.6 Extreme lightning event | U      |N       | N      |         | N              |
|  | 12.7 Other “Act of God” or insured events | U      |N      | N      |         | N              |
| Information Unavailable (IU) | 13.1 No communications / missing datapoint | N     |N       | U/N      |         | U              |
| | 13.2 Spurious reading | N      |N       | U/N      |         | N              |

