# README: Feature Description for the Updated Dataset

## Overview
This document describes the features in the updated dataset after performing feature engineering.

## Features

1. **PersPerFam** - The average number of persons per family.
2. **PctHousLess3BR** - The percentage of houses with less than 3 bedrooms.
3. **householdsize** - The average size of a household.
4. **NumIlleg** - The number of children born out of wedlock.
5. **state** - A numerical identifier for the state (please confirm if this is categorical or numerical).
6. **PersPerRentOccHous** - The number of persons per rented occupied house.
7. **PctHousOwnOcc** - The percentage of houses that are owner-occupied.
8. **PctWorkMomYoungKids** - The percentage of working mothers with young children.
9. **MedRentPctHousInc** - The median rent as a percentage of household income.
10. **NumUnderPov** - The number of individuals living under the poverty line.

## Newly Created Features

11. **PctHousOwnOcc_PctHousLess3BR** - The ratio of owner-occupied houses to houses with less than 3 bedrooms.
12. **PersPerFam_householdsize** - The ratio of persons per family to average household size.
13. **NumUnderPov_householdsize** - The ratio of the number of individuals under poverty to household size.
14. **NumIlleg_PctWorkMomYoungKids** - The ratio of the number of children born out of wedlock to the percentage of working mothers with young children.
15. **MedRentPctHousInc_PctHousOwnOcc** - The interaction term between median rent percentage of household income and owner-occupied houses percentage.
16. **PersPerRentOccHous_PctWorkMomYoungKids** - The interaction term between persons per rented occupied house and working mothers with young children percentage.

## Notes
- If any of the descriptions above are incorrect or need clarification, please provide additional details.

