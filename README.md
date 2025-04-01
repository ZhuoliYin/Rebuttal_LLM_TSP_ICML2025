# Rebuttal_LLM_TSP_ICML2025

## Supplement table for G2 to Reviewer fUe1
Although our primary goal is not to compete directly with LKH, our experiments show that by simply extending the runtime of LKH (i.e., increasing the number of runs) to align with LLM-TSP’s runtime, our method still yields competitive results, even without the aforementioned additional refactoring. Here we show two experimental examples:

| Algorithm | Instance | Latency | Objective Value |
|-----------|----------|---------|-----------------|
| LKH3      | u2319    | 315s    | 234683          |
| **LLM-TSP**   |  u2319       | 271s    | **234519**          |
| LKH3      | fl1577   | 219s    | 22261           |
| **LLM-TSP**   |   fl1577       | 202s    | **22253**           |
| | | | |


![](https://github.com/ZhuoliYin/Rebuttal_LLM_TSP_ICML2025/d1291_with_pad.jpg)

