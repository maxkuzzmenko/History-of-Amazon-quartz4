Im Jahr **2006** veröffentlichte AWS den **Simple Storage Service (S3)**, der das Problem der sicheren und einfach verwaltbaren Datenspeicherung löste.

Wenige Monate später folgte die **Elastic Compute Cloud (EC2)**, die Kunden per Knopfdruck sofortigen Zugang zu Rechenleistung verschaffte.

Beide Dienste funktionieren nach dem **Pay-as-you-go**-Prinzip – man zahlt nur für das, was man tatsächlich nutzt.
S3 und EC2 gehören bis heute zu den meistgenutzten Cloud-Diensten weltweit und helfen kleinen wie großen Unternehmen gleichermaßen.

Beispielhafte **S3 Standard**-Preise in der Region **Frankfurt**:

| Speichermenge        | Preis                 |
| -------------------- | --------------------- |
| Erste 50 TB / Monat  | ```0,0245$ pro GB``` |
| Nächste 450 TB / Mon.| ```0,0235$ pro GB``` |
| Über 500 TB / Monat  | ```0,0225$ pro GB``` |
50 GB Speicher = 50 * 0,0245\$ / Monat = **1,225\$ / Monat**
  

Beispielhafte **EC2**-Preise ebenfalls in der Region Frankfurt:

| Instanzname         | Preis pro Stunde | vCPU | Arbeitsspeicher | Netzwerkleistung |
| ------------------- | ---------------- | ---- | --------------- | ---------------- |
| t4g.nano            | ``0,0048$``     | 2    | 0,5 GiB         | Bis 5 Gigabit    |
| t4g.micro           | ``0,0096$``     | 2    | 1 GiB           | Bis 5 Gigabit    |
| u7in-24tb.224xlarge | ``326,6006$``   | 896  | 24.576 GiB      | 200 Gigabit      |

Ein ganzer Monat **t4g.nano** (24/7) kostet *(ca.)*:<br>
0,0048\$ / Stunde * 24 * 30 = **3,456\$ / Monat**

Diese Rechenleistung reicht für die meisten jungen Start-ups aus
