# E-commerce Conversion Funnel Analysis

## Project Overview

This project analyzes user behavior across an e-commerce conversion funnel to identify drop-off points, calculate conversion rates, detect bottlenecks, and provide recommendations for improving conversions.

The funnel stages analyzed are:

1. Visit
2. Product View
3. Add to Cart
4. Purchase

---

## Objectives

- Define the e-commerce conversion funnel stages.
- Analyze user drop-off at each stage.
- Calculate conversion rates between funnel stages.
- Identify bottlenecks in the conversion process.
- Provide actionable recommendations to improve conversions.
- Visualize funnel performance using charts.

---

## Business Questions

1. How many users visited the website?
2. How many users viewed products?
3. How many users added products to their cart?
4. How many users completed purchases?
5. Which funnel stage has the highest drop-off?
6. What are the conversion rates between stages?
7. How can the conversion rate be improved?

---

## Dataset Information

The dataset contains user interactions across four funnel stages:

- Visited
- Product View
- Add to Cart
- Purchased

Total Records: 1000 Users

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

---

## Project Structure

```text
Ecommerce_Funnel_Analysis
│
├── Ecommerce_Funnel_Analysis.ipynb
│
├── data
│   └── ecommerce_funnel.csv
│
├── outputs
│   ├── funnel_chart.png
│   └── conversion_rates_chart.png
│
├── README.md
│
└── requirements.txt
```

---

## Key Results

### Funnel Stage Counts

| Stage | Users |
|---------|---------:|
| Visit | 1000 |
| Product View | 816 |
| Add to Cart | 308 |
| Purchase | 85 |

### Conversion Rates

| Conversion Stage | Rate |
|------------------|---------:|
| Visit → Product View | 81.60% |
| Product View → Cart | 37.75% |
| Cart → Purchase | 27.60% |
| Overall Conversion | 8.50% |

---

## Bottleneck Analysis

The largest drop-off occurred between:

**Product View → Add to Cart**

Many users viewed products but did not proceed to add them to their cart, making this stage the primary bottleneck in the funnel.

---

## Recommendations

- Improve product descriptions and images.
- Display customer reviews and ratings.
- Offer discounts and promotional campaigns.
- Simplify the checkout process.
- Provide multiple payment options.
- Send cart abandonment reminder emails.

---

## Conclusion

The E-commerce Conversion Funnel Analysis successfully identified user behavior patterns and conversion bottlenecks across the sales funnel.

The analysis revealed that the Product View to Add to Cart stage had the highest user drop-off. By improving product presentation, building customer trust, and streamlining the checkout process, businesses can increase conversions and improve overall revenue.

---


Khushi Singh

Data Analysis Internship Project