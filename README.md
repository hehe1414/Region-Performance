# Region Performance – Superstore

**Task 18 – Region Performance**
Veda Technology | Data Analytics Track | Level 1, Day 18

## About
I compared the four regions of the Sample Superstore dataset (2014-2017, 9,994 transactions) on both sales and profit, ranked them, and showed the result in a bar chart in Excel.

## Region summary
| Region | Total Sales | Total Profit | Profit Margin | Avg Discount | Sales Rank | Profit Rank |
|--------|------------|--------------|---------------|--------------|-----------|-------------|
| West | 725,458 | 108,418 | 14.9% | 10.9% | 1 | 1 |
| East | 678,781 | 91,523 | 13.5% | 14.5% | 2 | 2 |
| Central | 501,240 | 39,706 | 7.9% | 24.0% | 3 | 4 |
| South | 391,722 | 46,749 | 11.9% | 14.7% | 4 | 3 |
| **Total** | **2,297,201** | **286,397** | **12.5%** | | | |

## Chart
A clustered bar chart comparing Total Sales and Total Profit for each region.

## Findings
- **West is the best region.** It ranks first in both sales (725,458) and profit (108,418), has the best margin (14.9%), and gives the smallest average discount (10.9%).
- **East is a solid second** on both sales and profit.
- **Central is the problem region.** It ranks 3rd in sales (501,240) but last in profit (39,706). Its margin is only 7.9%, and it gives the highest average discount (24.0%), which probably eats its profit.
- **South is the smallest region by sales** (391,722), but it earns more profit than Central (46,749, margin 11.9%).

**Takeaway:** ranking by sales alone would hide that Central makes the least profit. Comparing both sales and profit gives a fairer picture.

## Files
- `Region_Performance.xlsx` – workbook with the Raw Data tab and the Region Performance tab (formulas, ranks and chart)
- `region_performance_screenshot.png` – screenshot of the Region Performance tab
- `README.md`

## Tools used
Microsoft Excel (SUMIFS, AVERAGEIFS, RANK, charts)

## Author
Rabia
