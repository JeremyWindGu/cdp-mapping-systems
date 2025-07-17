# Event GeoJSON Annotation Guide

Below is a list of concerts, plays, exhibitions, and sports events I've watched or followed.

| Performance | Venue Name | Venue Location | Start Time | End Time | Lowest Price (CNY) | Highest Price (CNY) | Estimated Attendance |
|---|---|---|---|---|---|---|---|
| Play 'Art' | Jasmine Theater | 247 Beihai Road, Huangpu District | 2025-02-27 19:30 | 2025-02-27 21:30 | ¥80 | ¥580 | 550 |
| Opera 'The Dream of Splendor' | Shanghai Grand Theater | 300 Renmin Avenue (East Nanjing Road, People’s Square) | 2025-03-28 19:30 | 2025-03-28 21:30 | ¥80 | ¥880 | 1800 |
| Play 'Before the Court' 2.0 Edition | Shanghai Grand Theater | 300 Renmin Avenue (East Nanjing Road, People’s Square) | 2025-04-04 19:30 | 2025-04-04 21:30 | ¥180 | ¥580 | 1700 |
| Play 'The Metamorphosis' (Kafka) | Shanghai Dramatic Arts Center | 288 Anfu Road, Xuhui District | 2025-02-15 19:30 | 2025-02-15 21:30 | ¥180 | ¥480 | 650 |
| Play 'The Deer and the Cauldron' | Shanghai Dramatic Arts Center | 288 Anfu Road, Xuhui District | 2025-03-05 19:30 | 2025-03-05 21:30 | ¥180 | ¥580 | 650 |
| Musical 'The Snowstorm Temple' | Shanghai Dramatic Arts Center | 288 Anfu Road, Xuhui District | 2025-04-10 19:30 | 2025-04-10 21:30 | ¥180 | ¥680 | 700 |
| Play 'The End of the Rainbow' | Shanghai Dramatic Arts Center | 288 Anfu Road, Xuhui District | 2025-05-02 19:30 | 2025-05-02 21:30 | ¥180 | ¥580 | 600 |
| Play 'The Three Musketeers' | Shanghai Dramatic Arts Center | 288 Anfu Road, Xuhui District | 2025-05-15 19:30 | 2025-05-15 21:30 | ¥180 | ¥580 | 650 |
| Opera 'Tristan und Isolde' | Shanghai Opera House Grand Theater | 300 Renmin Avenue, Huangpu District | 2025-05-05 19:30 | 2025-05-05 21:30 | ¥180 | ¥980 | 1800 |
| Opera 'Falstaff' | Shanghai Opera House Grand Theater | 300 Renmin Avenue, Huangpu District | 2025-05-12 19:30 | 2025-05-12 21:30 | ¥180 | ¥980 | 1800 |
| Opera 'The Woman’s Heart' (Semi-Staged) | Shanghai Opera House Grand Theater | 300 Renmin Avenue, Huangpu District | 2025-04-20 19:30 | 2025-04-20 21:30 | ¥180 | ¥880 | 1800 |
| Dance Drama 'Peacock' | Oriental Art Center Opera Hall | 425 Dingxiang Road, Pudong New Area | 2025-05-28 19:15 | 2025-05-28 21:15 | ¥180 | ¥1080 | 900 |
| Dance Drama 'The Phantom of the Opera' (Flamenco) | Shanghai Grand Theater | 300 Renmin Avenue, Huangpu District | 2025-02-01 19:30 | 2025-02-01 21:30 | ¥80 | ¥880 | 1800 |

## Association Method

- **Spatial Mapping**  
  Map each venue’s coordinates to the nearest 1–2 metro stations.

- **Time Window**  
  Extract metro entry/exit volume fluctuations in a 1–2 hour window before and after each event.

- **Data Source**  
  Metro entry/exit volume dataset from https://data.sh.gov.cn/view/detail/index.html?type=jk&&id=2153&&dataset_name=%5Bobject%20HTMLHeadingElement%5D (access pending).

## Potential Insights

1. Relationship between post-event exit peaks and event scale.

2. Comparative impact of different event types (concerts vs. sports) on surrounding station flows.
