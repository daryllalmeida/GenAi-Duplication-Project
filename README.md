**PROJECT OVERVIEW :**

1. Automated duplicate product detection for merchant catalogs using a GenAI + rules workflow on a 128,038-record dataset.

2. Standardized product fields (name/brand/category/package + unit normalization), cleaning ~88% with extended unit-conversion logic for edge cases.

3. Generated fuzzy similarity scores and bucketed results into Auto-merge (>95), Human-in-the-loop (75–95), and Unique (<75) actions.

4. Classified duplicates into 3 types: packaging variation (27,687), misspellings/variants (9,323), and unit/synonym size (938).

5. Findings show duplication concentrated in certain categories and tied to inconsistent naming/pack formats; proposed scalable fixes (hybrid RAG, SKU rules, geo synonym maps, merchant training + validation).
