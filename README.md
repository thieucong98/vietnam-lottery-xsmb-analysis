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
| <table><tr><td>Date (Ngày)</td><td>07-06-2025</td></tr><tr><td>Special (Giải dặc biệt)</td><td>67142</td></tr><tr><td>First (Giải nhất)</td><td>07086</td></tr><tr><td>Second (Giải nhì)</td><td>93134, 69606</td></tr><tr><td rowspan="2">Third (Giải ba)</td><td>86057, 32814, 53612</td></tr><tr><td>19401, 58367, 93916</td></tr><tr><td>Fourth (Giải tư)</td><td>0419, 7118, 3279, 7158</td></tr><tr><td rowspan="2">Fifth (Giải năm)</td><td>8814, 9538, 0314</td></tr><tr><td>3723, 9201, 4619</td></tr><tr><td>Sixth (Giải sáu)</td><td>589, 226, 061</td></tr><tr><td>Seventh (Giải bảy)</td><td>79, 52, 82, 61</td></tr></table> | <table><tr><td>First (Đầu)</td><td>Last (Đuôi)</td></tr><tr><td>0</td><td>1, 1, 6</td></tr><tr><td>1</td><td>2, 4, 4, 4, 6, 8, 9, 9</td></tr><tr><td>2</td><td>3, 6</td></tr><tr><td>3</td><td>4, 8</td></tr><tr><td>4</td><td>2</td></tr><tr><td>5</td><td>2, 7, 8</td></tr><tr><td>6</td><td>1, 1, 7</td></tr><tr><td>7</td><td>9, 9</td></tr><tr><td>8</td><td>2, 6, 9</td></tr><tr><td>9</td><td>-</td></tr></table> |

<details>
  <summary><h2>Analysis of special prices (Phân tích kết quả xổ số)</h2></summary>
  <h3>Amount of day from last appearing (Số ngày từ lần xuất hiện cuối cùng)</h3>

  ![Delta](images/special_delta.jpg)

  <h3>Top 10 amount of day from last appearing (Top 10 số lâu chưa xuất hiện)</h3>

  ![Delta top 10](images/special_delta_top_10.jpg)
</details>

<details>
  <summary><h2>Analysis of one-year Loto results (Phân tích kết quả lô tô trong 1 năm)</h2></summary>

  Max: 119. Min: 71.

  Mean: 97.47. Standard deviation: 9.59.

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