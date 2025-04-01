# Rebuttal_LLM_TSP_ICML2025

## Response to the Reviewer fUe1: Supplement table for G2
Although our primary goal is not to compete directly with LKH, our experiments show that by simply extending the runtime of LKH (i.e., increasing the number of runs) to align with LLM-TSP’s runtime, our method still yields competitive results, even without the aforementioned additional refactoring. Here we show two experimental examples:

Table 1: Additional comparison between LKH3 and LLM-TSP, with aligned runtime
| Algorithm | Instance | Latency | Objective Value |
|-----------|----------|---------|-----------------|
| LKH3      | u2319    | 315s    | 234683          |
| **LLM-TSP**   |  u2319       | 271s    | **234519**          |
| LKH3      | fl1577   | 219s    | 22261           |
| **LLM-TSP**   |   fl1577       | 202s    | **22253**           |
| | | | |


## Response to the Reviewer Ax2C: More insights into how the visual LLM selects regions
To further illustrate this process, we visualize the top-5 selected rectangles produced by LLM-TSP on the TSPLIB instance d1291. The visualizations show that the model flexibly focuses on both local clusters and inter-cluster boundaries.

Figure 1: First five subproblems selected by LLM-TSP on d1291

![](https://github.com/ZhuoliYin/Rebuttal_LLM_TSP_ICML2025/blob/main/d1291_with_pad.pdf)
