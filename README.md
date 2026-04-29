A/B Testing — Statistical Analysis Guide

This project provides a practical and structured walkthrough of A/B testing using statistical methods. It focuses on how to evaluate whether two variations (such as product designs, ads, or layouts) produce significantly different outcomes. The notebook demonstrates both theoretical understanding and hands-on implementation using Python, making it useful for data analysts, product managers, and anyone interested in experimentation.

The analysis begins with discrete metrics, such as click-through rate, where outcomes are binary (e.g., clicked vs not clicked). Using simulated data, the project explains how to construct contingency tables and apply statistical tests to determine significance. It covers Fisher’s Exact Test, which computes an exact p-value and is ideal for small sample sizes, ensuring accurate hypothesis testing. It also introduces Pearson’s Chi-Squared Test, which is more efficient for larger datasets and provides an approximate but scalable solution.

The notebook then transitions into continuous metrics, such as revenue per user, where outcomes are numeric rather than binary. In this section, multiple statistical techniques are explored, including the Z-test, Student’s t-test, and Welch’s t-test, each suited for different assumptions about variance and sample size. Additionally, it includes the Mann-Whitney U test, a non-parametric alternative that does not assume normal distribution, making it robust for real-world datasets.

Beyond applying tests, the project emphasizes understanding the difference between data distributions and statistical distributions, helping users interpret results more accurately. Visualization tools such as Matplotlib are used to support analysis and make statistical concepts easier to grasp.

Overall, this project serves as a complete guide to A/B testing, combining statistical theory with practical implementation. It demonstrates how to choose the right test based on data type and sample size, interpret p-values, and make data-driven decisions confidently.
