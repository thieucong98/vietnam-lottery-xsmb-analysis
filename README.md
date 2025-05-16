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
| <table><tr><td>Date (Ngày)</td><td>16-05-2025</td></tr><tr><td>Special (Giải dặc biệt)</td><td>27987</td></tr><tr><td>First (Giải nhất)</td><td>50566</td></tr><tr><td>Second (Giải nhì)</td><td>36556, 02620</td></tr><tr><td rowspan="2">Third (Giải ba)</td><td>84084, 81082, 21383</td></tr><tr><td>82811, 03629, 39655</td></tr><tr><td>Fourth (Giải tư)</td><td>0625, 2144, 7783, 0032</td></tr><tr><td rowspan="2">Fifth (Giải năm)</td><td>5555, 1526, 2338</td></tr><tr><td>0876, 9404, 0578</td></tr><tr><td>Sixth (Giải sáu)</td><td>357, 669, 682</td></tr><tr><td>Seventh (Giải bảy)</td><td>99, 04, 91, 52</td></tr></table> | <table><tr><td>First (Đầu)</td><td>Last (Đuôi)</td></tr><tr><td>0</td><td>4, 4</td></tr><tr><td>1</td><td>1</td></tr><tr><td>2</td><td>0, 5, 6, 9</td></tr><tr><td>3</td><td>2, 8</td></tr><tr><td>4</td><td>4</td></tr><tr><td>5</td><td>2, 5, 5, 6, 7</td></tr><tr><td>6</td><td>6, 9</td></tr><tr><td>7</td><td>6, 8</td></tr><tr><td>8</td><td>2, 2, 3, 3, 4, 7</td></tr><tr><td>9</td><td>1, 9</td></tr></table> |

<details>
  <summary><h2>Analysis of special prices (Phân tích kết quả xổ số)</h2></summary>
  <h3>Amount of day from last appearing (Số ngày từ lần xuất hiện cuối cùng)</h3>

  ![Delta](images/special_delta.jpg)

  <h3>Top 10 amount of day from last appearing (Top 10 số lâu chưa xuất hiện)</h3>

  ![Delta top 10](images/special_delta_top_10.jpg)
</details>

<details>
  <summary><h2>Analysis of one-year Loto results (Phân tích kết quả lô tô trong 1 năm)</h2></summary>

  Max: 121. Min: 64.

  Mean: 97.47. Standard deviation: 10.27.

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