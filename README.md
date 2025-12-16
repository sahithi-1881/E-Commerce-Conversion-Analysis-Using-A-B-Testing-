
# 📈 A/B Testing: Landing Page Conversion Analysis

A data-driven experiment to evaluate user behavior and conversion performance

<img width="826" height="487" alt="image" src="https://github.com/user-attachments/assets/c57cec64-5e66-40e6-8c91-cf758580fd57" />


# 📍 The Context

For digital products and marketing teams, even small changes to a landing page can significantly impact user conversion.
This project simulates a real-world A/B testing scenario where multiple landing page variants are tested to understand which design performs best in driving conversions.

The goal was to move beyond intuition and use statistical evidence to support product decisions.

# ⚠️ The Business Question

The core questions driving this analysis were:

Do different landing page variants lead to different conversion rates?

Are observed differences statistically significant or due to random chance?

Do conversion patterns vary by device type, age group, traffic source, or coupon usage?

Which variant should be recommended for rollout?

# 🔎 The Approach

I analyzed session-level data containing:

Landing page variant assignment

Conversion outcomes

User attributes (device, age group, traffic source)

Engagement metrics (time spent, pages visited)

Revenue for converted sessions

The workflow included:

1. Cleaning and validating raw data

2. Exploratory analysis of traffic and conversion distributions

3. Statistical hypothesis testing to compare variants

4. Segmented analysis to uncover behavioral differences across user groups

# 🧪 Experiment Design

Control and treatment variants were compared using conversion rate as the primary metric

A Chi-square test of independence was used to detect overall differences in conversion behavior

Z-tests for proportions were applied for pairwise comparisons between variants

Results were validated across multiple user segments to ensure consistency

# 📊 Key Insights

Some of the most important findings included:

Conversion rates varied across landing page variants, but not all differences were statistically significant

Device type and traffic source influenced conversion behavior more strongly than page design alone

Users who spent more time and visited more pages were significantly more likely to convert

Coupon usage showed a noticeable lift in conversion rates across variants

These insights highlight the importance of combining statistical testing with behavioral segmentation.

# 📈 Outcome & Recommendation

Based on statistical results and segmented analysis:

Only variants with statistically significant conversion improvements should be considered for rollout

Product decisions should account for user context (device, source, engagement), not just overall averages

The experiment framework can be reused for future tests to support continuous optimization

This analysis demonstrates how A/B testing can reduce decision risk and support evidence-based product changes.

# 🛠 Tools & Technologies

Python (Pandas, NumPy)

Statistical testing (Chi-square test, Z-test for proportions)

Visualization (Matplotlib, Seaborn)

SQL-style analytics using DuckDB
