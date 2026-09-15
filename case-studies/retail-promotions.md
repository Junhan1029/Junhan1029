# Retail Promotion Incrementality

**August 2026 | YBIGTA Data Analysis project | Project lead**

[Original team repository](https://github.com/wisebell77/YBIGTA_project2)

## Problem

Higher sales during a promotion can reflect additional demand, discounts on purchases that would happen anyway, or purchases brought forward from later weeks. Those explanations imply different spending decisions.

## My contribution

I led the project and owned the upstream incrementality analysis. I defined treatment using flyer exposure rather than the discount realized on a purchase, constructed household-category purchase opportunities including zero-purchase observations, and estimated effects with household-category fixed effects.

I examined follow-on purchases and cross-category effects to move from an average sales lift to category-level allocation rules. Team members conducted complementary customer and category analyses; those analyses remain credited in the original repository.

## Output

A reproducible analytical pipeline, reports and decision rules for comparing promotion opportunities. The work used dunnhumby's The Complete Journey dataset; it was an academic analysis, not a retailer deployment.

## Limits

The data are observational. Fixed effects do not remove every source of selection bias. Product cost is not directly observed, so revenue-based proxies should not be described as measured profit. Data definitions, treatment coverage and follow-up windows materially affect the interpretation.

Use the original repository for code and contributor history. Obtain data from its original provider under the applicable terms rather than assuming this profile redistributes it.

[Back to profile](../README.md) · [Explore the code](../docs/code-guide.md)
