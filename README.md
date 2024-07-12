# Vietnam Lottery (XSMB) Analysis

Using GitHub Action to automatically fetch and analyze results of the Vietnam lottery daily.

Sử dụng GitHub Action để tự động hoá thu thập và phân tích kết quả xổ số hàng ngày của Việt Nam.

Download:

* [Full data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb.csv)
* [1-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_1_year.csv)
* [2-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_2_year.csv)
* [3-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_3_year.csv)
* [5-year data](https://raw.githubusercontent.com/khiemdoan/vietnam-lottery-xsmb-analysis/main/results/xsmb_5_year.csv)

| Lottery (Xổ số) | Loto (Lô tô) |
| :------------: | :----------: |
| <table><tr><td>Date (Ngày)</td><td>12-07-2024</td></tr><tr><td>Special (Giải dặc biệt)</td><td>92619</td></tr><tr><td>First (Giải nhất)</td><td>11319</td></tr><tr><td>Second (Giải nhì)</td><td>98199, 29744</td></tr><tr><td rowspan="2">Third (Giải ba)</td><td>27067, 11978, 08680</td></tr><tr><td>33893, 22152, 71172</td></tr><tr><td>Fourth (Giải tư)</td><td>8758, 2540, 6325, 1020</td></tr><tr><td rowspan="2">Fifth (Giải năm)</td><td>5737, 7614, 1159</td></tr><tr><td>3148, 1769, 5866</td></tr><tr><td>Sixth (Giải sáu)</td><td>359, 476, 412</td></tr><tr><td>Seventh (Giải bảy)</td><td>66, 36, 72, 06</td></tr></table> | <table><tr><td>First (Đầu)</td><td>Last (Đuôi)</td></tr><tr><td>0</td><td>6</td></tr><tr><td>1</td><td>2, 4, 9, 9</td></tr><tr><td>2</td><td>0, 5</td></tr><tr><td>3</td><td>6, 7</td></tr><tr><td>4</td><td>0, 4, 8</td></tr><tr><td>5</td><td>2, 8, 9, 9</td></tr><tr><td>6</td><td>6, 6, 7, 9</td></tr><tr><td>7</td><td>2, 2, 6, 8</td></tr><tr><td>8</td><td>0</td></tr><tr><td>9</td><td>3, 9</td></tr></table> |

<details>
  <summary><h2>Analysis of special prices (Phân tích kết quả xổ số)</h2></summary>
  <h3>Amount of day from last appearing (Số ngày từ lần xuất hiện cuối cùng)</h3>

  ![Delta](images/special_delta.jpg)

  <h3>Top 10 amount of day from last appearing (Top 10 số lâu chưa xuất hiện)</h3>

  ![Delta top 10](images/special_delta_top_10.jpg)
</details>

<details>
  <summary><h2>Analysis of one-year Loto results (Phân tích kết quả lô tô trong 1 năm)</h2></summary>

  Max: 125. Min: 67.

  Mean: 97.74. Standard deviation: 10.97.

  <h3>Detail (Chi tiết)</h3>

  ![Detail](images/heatmap.jpg)

  <h3>Top 10</h3>

  ![Top 10](images/top-10.jpg)

  <h3>Distribution (Phân bổ)</h3>

  ![Distribution](images/distribution.jpg)
</details>

<details>
  <summary><h3>Amount of day from last appearing (Số ngày từ lần xuất hiện cưới cùng)</h2></summary>

  ![Delta](images/delta.jpg)

  <h3>Top 10 amount of day from last appearing (Top 10 số lâu chưa xuất hiện)</h3>

  ![Delta top 10](images/delta_top_10.jpg)
</details>