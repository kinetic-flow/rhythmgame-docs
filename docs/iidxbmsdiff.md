# IIDX LR2 beatoraja differences 

==Gauge types==

Notes

* T = Total value in BMS
* n = number of notes
* a = a function of total note count in IIDX, but depends on chart
* all units in %

{| class="wikitable" 
|-
! 
! PGREAT
! GREAT
! GOOD
! BAD
! POOR
! 空POOR
! Low Life Adj ※0
|-
| Beatoraja/AEASY
| T/n
| T/n
| T/n/2
| -1.5
| -3
| -0.5
| -
|-
| IIDX/AEASY
| a
| a
| a/2
| -3.2
| -4.8
| -1.6
| -
|-
|
|
|
|
|
|
|
|
|-
| Beatoraja/EASY
| T/n
| T/n
| T/n/2
| -1.5
| -4.5
| -1
| -
|-
| LR2/EASY
| (T/n)*1.2
| (T/n)*1.2
| (T/n)*0.6
| -3.2
| -4.8
| -1.6
| -
|-
| IIDX/EASY
| a
| a
| a/2
| -1.6
| -4.8
| -1.6
| -
|-
|
|
|
|
|
|
|
|
|-
| Beatoraja/NORMAL
| T/n
| T/n
| T/n/2
| -3
| -6
| -2
| -
|-
| LR2/NORMAL
| T/n
| T/n
| T/n/2
| -4
| -6
| -2
| -
|-
| IIDX/NORMAL
| a
| a
| a/2
| -2
| -6
| -2
| -
|-
|
|
|
|
|
|
|
|
|-
| Beatoraja/HARD
| 0.15 ※2
| 0.12 ※2
| 0.03 ※2
| -5
| -10
| -5
| Yes
|-
| LR2/HARD
| 0.1
| 0.1
| 0.05
| -6 ※1
| -10 ※1
| -2 ※1
| Yes
|-
| IIDX/HARD
| 0.16
| 0.16
| 0
| -5
| -9
| -5
| Yes
|-
|
|
|
|
|
|
|
|
|-
| Beatoraja/EXH
| 0.15 ※2
| 0.06 ※2
| 0
| -8
| -16
| -8
| No
|-
| IIDX/EXH
| 0.16
| 0.16
| 0
| -10
| -18
| -10
| No
|-
|
|
|
|
|
|
|
|
|-
| Beatoraja/DAN ※3
| 0.15
| 0.12
| 0.06
| -1.5
| -3
| -1.5
| Yes
|-
| LR2/DAN
| 0.1
| 0.1
| 0.05
| -2
| -3
| -2
| Yes
|-
| IIDX/DAN
| 0.16
| 0.16
| 0.04
| -1.5
| -2.5
| -1.5
| Yes
|-
|
|
|
|
|
|
|
|
|-
| IIDX/EXDAN
| 0.16
| 0.16
| 0.04
| -3.0
| -5.0
| -3.0
| No
|-
| Beatoraja/EXDAN
| 0.15
| 0.12
| 0.03
| -3
| -6
| -3
| No
|-
| Beatoraja/EXHDAN
| 0.15
| 0.08
| 0
| -5
| -10
| -5
| No
|-
|}

These are for 7key and 14key modes; other modes in beatoraja have different values.
* ※0 When the gauge is low, the rate of decrease is lowered; see the two sections below.
* ※1 In LR2, low T and low n leads to increased damage when on hard gauge
* ※2 In beatoraja, exhard and hard gauge increases at a lower rate when total is lower (under 250). If T is under 100 (like ★4Liberte) the gauge never increases.
* ※3 Very important: most DAN courses are tagged with gauge_lr2 to force enable beatoraja to use the LR2 DAN gauge instead.

===Hard gauge adjustment===

{| class="wikitable" style="text-align:center;"
{| class="wikitable" style="text-align:center;"
|-
! Remaining life
! colspan="3" | LR2
! colspan="3" | IIDX
! colspan="3" | beatoraja
|-
|- style="text-align:left;"
| 
| BD
| PR
| 空P
| BD
| PR
| 空P
| BD
| PR
| 空P
|-
| style="text-align:right;" | 60+
| rowspan="3" | -6
| rowspan="3" | -10
| rowspan="3" | -2
| rowspan="3" | -5
| rowspan="3" | -9
| rowspan="3" | -5
| -5
| -10
| -5
|-
| style="text-align:right;" | 50
| -4
| -8
| -4
|-
| style="text-align:right;" | 40
| -3.5
| -7
| -3.5
|-
| style="text-align:right;" | 30
| rowspan="3" | -3.6
| rowspan="3" | -6
| rowspan="3" | -1.2
| rowspan="3" | -2.5
| rowspan="3" | -4.5
| rowspan="3" | -2.5
| -3
| -6
| -3
|-
| style="text-align:right;" | 20
| -2.5
| -5
| -2.5
|-
| style="text-align:right;" | 10
| -2
| -4
| -2
|}

* In IIDX and LR2, the gauge decreases at a lower rate when the gauge is at or below 30%
* In beatoraja, this is more of a gradual decrease from 50% and down

===DAN gauge adjustment===

{| class="wikitable" 
|- style="text-align:center;"
! rowspan="2" style="text-align:left;" | Remaining Life
! colspan="3" | LR2
! colspan="3" | IIDX
! colspan="3" | Beatoraja
|- style="text-align:center;"
| BD
| PR
| 空P
| BD
| PR
| 空P
| BD
| PR
| 空P
|-
| >30
| -2
| -3
| -2
| -1.5
| -2.5
| -1.5
| -1.5
| -3
| -1.5
|-
| <30
| rowspan="6" | -1.2
| rowspan="6" | -1.8
| rowspan="6" | -1.2
| rowspan="6" | -0.75
| rowspan="6" | -1.25
| rowspan="6" | -0.75
| -1.5
| -3
| -1.5
|-
| 25
| -1.2
| -2.4
| -1.2
|-
| 20
| -1.05
| -2.1
| -1.05
|-
| 15
| -0.9
| -1.8
| -0.9
|-
| 10
| -0.75
| -1.5
| -0.75
|-
| 5
| -0.6
| -1.2
| -0.6
|}

* Again, most DAN courses are tagged to enable LR2 DAN gauge in beatoraja.

==Timing window==

{| class="wikitable" 
|-
! 
! PG
! GR
! GD
! BD
! PR
|-
| LR2 easy
| ±21
| ±60
| ±120
| ±200
| +1000
|-
| LR2 normal
| ±18
| ±40
| ±100
| ±200
| +1000
|-
| LR2 hard
| ±15
| ±30
| ±60
| ±200
| +1000
|-
| LR2 very hard
| ±8
| ±24
| ±40
| ±200
| +1000
|-
| beatoraja easy (notes)
| ±20
| ±60
| ±150
| +220 -280
| +500 -150
|-
| beatoraja easy (turntable)
| ±30
| ±70
| ±160
| +230 -290
| +500 -160
|-
| IIDX (most charts)
| ±16.67
| ±33.33
| ±116.67
| ±250
| ? (needs update)
|}

All units in milliseconds. Positive means before the note, negative is after the note.

Special rules for beatoraja easy judge:
* long notes: significantly larger ({-120, 120}, {-160, 160}, {-200, 200}, {-280, 220}})
* long scratch notes: add -10 +10 to each end of long note window
* For other judge windows: VERYEASY is 25% wider than EASY, NORMAL is 25% narrower, HARD is 50% narrower, and so on.
* In beatoraja, empty poors are possible after a note. (This exists in IIDX , but not LR2)

==Now what?==

If you only care about EX-score, beatoraja is slightly harder, since its PGREAT window is 4ms narrower.

If you are playing BMS DAN courses, the gauge differences are small since beatoraja will switch to LR2 gauge (for "fairness"). Timing is different though; with a wider GOOD window you are more likely to survive the DAN gauge.

If you are playing difficulty tables, your experience will differ from others, since difficulty tables are rated using LR2. Tables are usually rated on easy or normal gauge. Even if you ignore the differences in timing, no direct comparison can be made between LR2 groove gauge and beatoraja groove gauge, since their calculation methods are different. On survival gauges though, beatoraja is always easier than LR2, so you should keep that in mind.

If you like to use LR2 timing and gauge for everything, check out [https://github.com/wcko87/lr2oraja/ LR2oraja ].

==References==

https://lntakeshi.hateblo.jp/entry/2017/05/19/002127

https://github.com/exch-bms2/beatoraja/blob/master/src/bms/player/beatoraja/play/GaugeProperty.java

https://github.com/exch-bms2/beatoraja/blob/master/src/bms/player/beatoraja/play/GrooveGauge.java

https://github.com/exch-bms2/beatoraja/blob/master/src/bms/player/beatoraja/play/JudgeProperty.java

https://ch.nicovideo.jp/mirai_s_bemani_blog/blomaga/ar1389382

https://twitter.com/n13092s/status/908795911286878208

http://stairway.sakura.ne.jp/bms/delay.htm#input


