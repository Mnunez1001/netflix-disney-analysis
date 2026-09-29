## Current Analysis Direction

This project compares the content catalogs of Netflix and Disney+ using title information from Kaggle. The analysis examines catalog size, content type, release periods, production-country representation, and standardized broad genres.

The datasets represent catalog snapshots from approximately 2021. Therefore, the findings describe the supplied datasets and should not be interpreted as a comparison of the platforms' current catalogs.

## Primary Research Question

How do Netflix and Disney+ differ in the geographic and genre composition of their catalogs, and which content areas appear less represented on Disney+ relative to Netflix?

## Current Findings

### Catalog Size

Netflix contains 8,807 titles, while Disney+ contains 1,450. Netflix's catalog is approximately 6.1 times larger, so comparisons of catalog composition use percentages rather than raw title counts whenever possible.

### Content Type

The platforms have a similar movie-to-TV-show balance:

- Movies represent 69.62% of Netflix and 72.55% of Disney+.
- TV shows represent 30.38% of Netflix and 27.45% of Disney+.

### Release Periods

Disney+ has a median release year of 2011, compared with 2017 for Netflix. Disney+ contains a larger proportion of titles released before 2010, while Netflix is more concentrated in content released during the 2010s and 2020s.

### Geographic Representation

Netflix represents 122 known production countries, while Disney+ represents 47.

Using fractional country credit:

- The United States accounts for 87.93% of Disney+'s known-country catalog.
- The United States accounts for 39.98% of Netflix's known-country catalog.
- Disney+'s five leading production countries account for 96.77% of its known-country catalog.
- Netflix's five leading production countries account for 66.74% of its known-country catalog.

The largest representation differences appear in countries including India, Japan, the United Kingdom, South Korea, Spain, France, and Mexico.

## Preliminary Recommendation

Disney+ content-strategy leaders should investigate targeted international content expansion, particularly in countries that are substantially less represented in its catalog than in Netflix's. Any acquisition or production decision should also consider audience demand, licensing costs, brand alignment, and market-specific research that are not included in these datasets.

## Role of Genre Analysis

Genre will serve as supporting evidence for the geographic story. Netflix and Disney+ use substantially different genre-labeling systems, so their original labels cannot be compared directly.

The next phase will create a documented cross-platform genre taxonomy. Genre results will be used to determine whether Disney+'s geographic concentration is accompanied by meaningful differences in content categories.

## Important Limitations

- The `country` field represents production origin, not every country where a title was available to stream.
- The datasets do not include viewership, subscriber behavior, revenue, acquisition costs, licensing feasibility, or content quality.
- A smaller percentage does not automatically prove unmet demand.
- A title may have multiple countries and genres.
- Country analysis uses fractional credit to prevent international co-productions from being counted as complete titles for every participating country.
- Genre comparisons require a documented standardization process because the platforms use different terminology.