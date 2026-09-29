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

## Emerging Story

The analysis indicates that Netflix and Disney+ follow different catalog strategies:

- Netflix has a catalog approximately **6.1 times larger** than Disney+'s catalog.
- The two platforms have a relatively similar balance of movies and television shows.
- Netflix's catalog is generally newer, with a median release year of **2017**, compared with **2011** for Disney+.
- Netflix represents substantially more countries: **122 countries**, compared with **47 countries** for Disney+.
- Disney+'s catalog is much more geographically concentrated in the United States.
- Disney+ specializes in children and family, animation, action and adventure, and science fiction and fantasy.
- Netflix has greater representation in drama, crime and thriller, romance, and horror.

These findings suggest that Netflix uses scale, variety, and international breadth as major competitive strengths. Disney+ uses a more focused strategy centered on family entertainment, animation, recognizable franchises, adventure, and fantasy.

## Genre Standardization

The original datasets use different genre vocabularies. To make a valid comparison possible, the original labels were converted into documented broad genre categories through a genre crosswalk.

Mapping coverage was high for both platforms:

| Platform | Total Titles | Mapped Titles | Coverage |
|---|---:|---:|---:|
| Disney+ | 1,450 | 1,444 | 99.59% |
| Netflix | 8,807 | 8,725 | 99.07% |

Because titles may have multiple genres, the genre analysis measures the percentage of titles associated with each category. Percentages across genres therefore do not add to 100%.

## Principal Genre Findings

Disney+'s largest relative strengths are:

| Broad Genre | Disney+ | Netflix | Disney+ Gap |
|---|---:|---:|---:|
| Children and Family | 62.83% | 13.14% | +49.69 pp |
| Animation and Anime | 37.38% | 2.80% | +34.58 pp |
| Action and Adventure | 32.07% | 11.66% | +20.41 pp |
| Science Fiction and Fantasy | 19.38% | 3.71% | +15.67 pp |

Netflix's largest relative strengths are:

| Broad Genre | Disney+ | Netflix | Netflix Gap |
|---|---:|---:|---:|
| Drama | 24.76% | 36.22% | +11.46 pp |
| Crime, Mystery, and Thriller | 2.34% | 13.17% | +10.83 pp |
| Romance | 1.59% | 11.20% | +9.61 pp |
| Horror | 0.00% | 4.91% | +4.91 pp |

A sensitivity analysis produced a correlation of **0.905** between the primary and alternative genre measures, providing additional support for the major conclusions.

## Proposed Recommendation

Disney+ should investigate targeted international catalog expansion while preserving its differentiated family-oriented brand.

Instead of attempting to reproduce the entire Netflix catalog strategy, Disney+ could prioritize selected countries where its catalog representation is currently limited and acquire content that complements its strengths in family, animation, adventure, fantasy, and franchise-based entertainment.

This is an evidence-supported proposal for further investigation rather than proof of subscriber demand. Audience preferences, licensing costs, content availability, and expected returns would need to be examined before making a final investment decision.

## Final Visual Story

The presentation will develop the story in three stages:

1. **Catalog profile:** size, content type, and release history
2. **International diversity:** geographic concentration and country representation gaps
3. **Content identity:** standardized genre strengths and weaknesses

The final message is that the two platforms are differentiated not simply by catalog size, but by geographic reach and content identity.

## Important Limitations

- The datasets represent catalog snapshots rather than complete historical records.
- Titles may have multiple countries and genres.
- Standardized genre categories simplify some distinctions in the original labels.
- Catalog composition should not be treated as direct evidence of audience demand.
- The `country` field represents production origin, not every country where a title was available to stream.
- The datasets do not include viewership, subscriber behavior, revenue, acquisition costs, licensing feasibility, or content quality.
- A smaller percentage does not automatically prove unmet demand.
- A title may have multiple countries and genres.
- Country analysis uses fractional credit to prevent international co-productions from being counted as complete titles for every participating country.
- Genre comparisons require a documented standardization process because the platforms use different terminology.