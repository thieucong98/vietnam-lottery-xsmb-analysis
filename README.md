# Vietnam Lottery (XSMB) Analysis

Using GitHub Action to automatically fetch and analyze results of the Vietnam lottery daily.

Download:

* [Full data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb.csv)
* [1-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_1_year.csv)
* [2-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_2_year.csv)
* [3-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_3_year.csv)
* [5-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_5_year.csv)

| Lotery      | Loto |
| :-----------: | :-----------: |
| <table><tr><td>Date</td><td>13-03-2024</td></tr><tr><td>Special</td><td>91753</td></tr><tr><td>First</td><td>54579</td></tr><tr><td>Second</td><td>90984, 68978</td></tr><tr><td rowspan="2">Third</td><td>89663, 79417, 27577</td></tr><tr><td>20491, 00134, 75715</td></tr><tr><td>Fourth</td><td>7980, 7928, 8166, 1878</td></tr><tr><td rowspan="2">Fifth</td><td>7965, 9154, 7803</td></tr><tr><td>5279, 9350, 3131</td></tr><tr><td>Sixth</td><td>472, 053, 360</td></tr><tr><td>Seventh</td><td>43, 74, 60, 49</td></tr></table> | <table><tr><td>First</td><td>Last</td></tr><tr><td>0</td><td>3</td></tr><tr><td>1</td><td>5, 7</td></tr><tr><td>2</td><td>8</td></tr><tr><td>3</td><td>1, 4</td></tr><tr><td>4</td><td>3, 9</td></tr><tr><td>5</td><td>0, 3, 3, 4</td></tr><tr><td>6</td><td>0, 0, 3, 5, 6</td></tr><tr><td>7</td><td>2, 4, 7, 8, 8, 9, 9</td></tr><tr><td>8</td><td>0, 4</td></tr><tr><td>9</td><td>1</td></tr></table> |


<h2>Analysis of special prices</h2>

<h3>Amount of day from last appearing</h3>

![Delta](images/special_delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/special_delta_top_10.jpg)

<h2>Analysis of one-year results</h2>

Max: 119. Min: 79.

Mean: 97.74. Standard deviation: 8.82.

<h3>Detail</h3>

![Detail](images/heatmap.jpg)

<h3>Top 10</h3>

![Top 10](images/top-10.jpg)

<h3>Distribution</h3>

![Distribution](images/distribution.jpg)

<h2>Amount of day from last appearing</h2>

![Delta](images/delta.jpg)

<h3>Top 10 amount of day from last appearing</h3>

![Delta top 10](images/delta_top_10.jpg)