# Attribution

This document provides detailed attribution for all data sources used in industries.org.ai.

## Data Sources

### NAICS (North American Industry Classification System) 2022

- **Source**: [U.S. Census Bureau NAICS](https://www.census.gov/naics/)
- **License**: Public Domain (U.S. Government Work)
- **Copyright**: U.S. Census Bureau, Statistics Canada, INEGI (Mexico)
- **Data Used**: 1,170 industry classifications with hierarchical codes
- **Attribution Required**: Yes (courtesy)
- **Changes Made**: Semantic structuring, MDX generation, cross-industry relationships

**Citation**:
```
North American Industry Classification System (NAICS) 2022
U.S. Census Bureau
https://www.census.gov/naics/
Public Domain
```

## How We Use This Data

The industries.org.ai ontology extends NAICS by:

1. **Hierarchical Structure**: 6-digit codes with sector → subsector → industry group → industry
2. **Cross-References**: Linking industries to occupations, processes, and products
3. **MDX Documentation**: Structured documentation with examples and use cases
4. **Business-as-Code Integration**: Enabling `$.Business.operates.in.Industry` patterns
5. **Economic Analysis**: Connecting GDP data, employment statistics, and market trends
6. **SDK Integration**: Seamless integration with sdk.do and the .org.ai ecosystem

## Our License

This derived work is licensed under Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). While the original NAICS data is in the Public Domain, we apply CC BY-SA 4.0 to our derived work to ensure attribution and that improvements remain open.

## Required Attribution

When using industries.org.ai, please include:

```
Based on industries.org.ai (https://industries.org.ai)
Data sourced from NAICS 2022 (https://www.census.gov/naics/)
U.S. Census Bureau
Licensed under CC BY-SA 4.0
```

## Acknowledgments

We are grateful to the U.S. Census Bureau, Statistics Canada, and INEGI for developing and maintaining NAICS, the standard used by Federal statistical agencies in classifying business establishments for the purpose of collecting, analyzing, and publishing statistical data related to the U.S. business economy.

NAICS was developed under the auspices of the Office of Management and Budget (OMB), and adopted in 1997 to replace the Standard Industrial Classification (SIC) system.

## Contact

For questions about attribution or licensing:
- Website: https://industries.org.ai
- GitHub: https://github.com/dot-org-ai/industries.org.ai/issues
- Community: https://github.com/dot-org-ai/community

## Updates

This attribution document is maintained alongside the industries.org.ai repository. Last updated: 2025-01-17
