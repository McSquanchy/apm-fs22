# Results

| SEARCH_TEXT                  | Optimization                 | Repetitions | Average   | Min       | Max       | CPU Usage  |
| ---------------------------- | ---------------------------- | ----------- | --------- | --------- | --------- | ---------- |
| default - "woman friend cat" | **none**                     | 30          | 2230.4 ms | 2072.2 ms | 3525.0 ms | 1 Core@23% |
| default - "woman friend cat" | none                         | 10          | 2321.1 ms | 2058.0 ms | 3762.6 ms | 1 Core@23% |
| default - "woman friend cat" | none                         | 50          | 2367.5 ms | 2020.0 ms | 8696.4 ms | 1 Core@23% |
| 20 words                     | none                         | 10          | 3027.7 ms | 2395.9 ms | 6826.7 ms | 1 Core@23% |
| 20 words                     | none                         | 30          | 2487.9 ms | 2344.5 ms | 3864.3 ms | 1 Core@23% |
| 20 words                     | none                         | 10          | 3027.7 ms | 2395.9 ms | 6826.7 ms | 1 Core@23% |
| 20 words                     | none                         | 50          | 2851.5 ms | 2352.3 ms | 7974.1 ms | 1 Core@23% |
| 50 words                     | none                         | 50          | 3214.9 ms | 3003.6 ms | 4689.4 ms | 1 Core@25% |
| 50 words                     | parallelStream in findInText | 50          | 2339.7 ms | 2181.1 ms | 5894.7 ms | 4Cores@40% |
|                              |                              |             |           |           |           |            |
