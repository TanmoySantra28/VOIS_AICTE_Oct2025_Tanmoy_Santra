```
Loading Airbnb NYC Dataset...
Dataset loaded successfully!
Dataset shape: (102599, 26)

=== DATASET OVERVIEW ===
Total records: 102599
Total columns: 26

Column names:
1. id
2. NAME
3. host id
4. host_identity_verified
5. host name
6. neighbourhood group
7. neighbourhood
8. lat
9. long
10. country
11. country code
12. instant_bookable
13. cancellation_policy
14. room type
15. Construction year
16. price
17. service fee
18. minimum nights
19. number of reviews
20. last review
21. reviews per month
22. review rate number
23. calculated host listings count
24. availability 365
25. house_rules
26. license

=== DATA QUALITY CHECK ===
Missing values per column:
• NAME: 270 (0.26%)
• host_identity_verified: 289 (0.28%)
• host name: 408 (0.40%)
• neighbourhood group: 29 (0.03%)
• neighbourhood: 16 (0.02%)
• lat: 8 (0.01%)
• long: 8 (0.01%)
• country: 532 (0.52%)
• country code: 131 (0.13%)
• instant_bookable: 105 (0.10%)
• cancellation_policy: 76 (0.07%)
• Construction year: 214 (0.21%)
• price: 247 (0.24%)
• service fee: 273 (0.27%)
• minimum nights: 409 (0.40%)
• number of reviews: 183 (0.18%)
• last review: 15893 (15.49%)
• reviews per month: 15879 (15.48%)
• review rate number: 326 (0.32%)
• calculated host listings count: 319 (0.31%)
• availability 365: 448 (0.44%)
• house_rules: 54843 (53.45%)
• license: 102597 (100.00%)

=== DATA CLEANING ===
Data cleaning completed!

================================================================================
AIRBNB NYC DATA ANALYSIS - RESEARCH QUESTIONS
================================================================================

QUESTION 1: What are the different property types in the Dataset?
------------------------------------------------------------
Property Types Distribution:
• Entire home/apt: 53701 listings (52.34%)
• Private room: 46556 listings (45.38%)
• Shared room: 2226 listings (2.17%)
• Hotel room: 116 listings (0.11%)

QUESTION 2: Which neighbourhood group has the highest number of listings?
------------------------------------------------------------
Neighbourhood Groups by Listing Count:
1. Manhattan: 43792 listings
2. Brooklyn: 41842 listings
3. Queens: 13267 listings
4. Bronx: 2712 listings
5. Staten Island: 955 listings
6. brookln: 1 listings
7. manhatan: 1 listings

Answer: Manhattan has the highest number of listings (43792 listings)

QUESTION 3: Which neighbourhood group has the highest average prices?
------------------------------------------------------------
Average Prices by Neighbourhood Group:
• Queens: $630.21 (based on 13234 listings)
• Bronx: $627.77 (based on 2705 listings)
• Brooklyn: $626.56 (based on 41749 listings)
• Staten Island: $624.49 (based on 952 listings)
• Manhattan: $622.44 (based on 43682 listings)
• brookln: $580.0 (based on 1 listings)
• manhatan: $460.0 (based on 1 listings)

Answer: Queens has the highest average price ($630.21)

QUESTION 4: Is there a relationship between construction year and price?
------------------------------------------------------------
Correlation between Construction Year and Price: -0.0038

Average Prices by Construction Decade:
• 2000s: $627.45 (based on 35932 listings)
• 2010s: $623.49 (based on 50919 listings)
• 2020s: $626.59 (based on 15291 listings)

Answer: Negative correlation (-0.0038)

QUESTION 5: Who are the top 10 hosts by calculated host listing count?
------------------------------------------------------------
Top 10 Hosts by Listing Count:
1. Blueground: 332 listings
2. Blueground: 332 listings
3. Blueground: 332 listings
4. Blueground: 332 listings
5. Blueground: 332 listings
6. Blueground: 332 listings
7. Blueground: 332 listings
8. Blueground: 332 listings
9. Blueground: 332 listings
10. Blueground: 332 listings

QUESTION 6: Are hosts with verified identities more likely to receive positive reviews?
------------------------------------------------------------
Review Ratings by Verification Status:
• Unconfirmed: 3.272/5 (based on 51029 reviews)
• Verified: 3.287/5 (based on 50969 reviews)

Answer: Verified hosts have 0.015 points higher average rating

QUESTION 7: Is there a correlation between listing price and service fee? 
------------------------------------------------------------
```
<img width="989" height="790" alt="image" src="https://github.com/user-attachments/assets/1e9cb5c0-47ea-4574-a656-e383e5458818" /> 

