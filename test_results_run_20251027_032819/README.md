# RAG Validation Test Run - 20251027_032819

## Overview
This directory contains the complete results from a RAG validation test run conducted on 2025-10-27 03:34:02.

## Directory Structure
```
test_results_run_20251027_032819/
├── README.md                           # This file
├── rag_validation_summary.json         # Complete test summary and results
├── case_1_rag_with_disease/            # Case 1: RAG + Disease Context
│   ├── meal_plan.json                  # Generated meal plan
│   ├── metadata.json                   # Test metadata and analysis
│   ├── articles/                       # Retrieved PMC articles
│   │   ├── article_1_PMID123.json
│   │   └── ...
│   └── logs/                          # Detailed logs
│       ├── case_1_rag_with_disease_detailed.log
│       └── rag_pipeline_logs.json
├── case_2_no_rag_with_disease/         # Case 2: No RAG + Disease Context
│   └── ... (same structure)
├── case_3_rag_no_disease/              # Case 3: RAG + No Disease Context
│   └── ... (same structure)
└── case_4_baseline/                    # Case 4: Baseline (No RAG, No Disease)
    └── ... (same structure)
```

## Test Cases
1. **Case 1 (RAG + Disease)**: Retrieval-Augmented Generation with medical condition context
2. **Case 2 (No RAG + Disease)**: Standard generation with medical condition context
3. **Case 3 (RAG + No Disease)**: Retrieval-Augmented Generation without medical context
4. **Case 4 (Baseline)**: Standard generation without medical context

## Test Subject Profile
- **Name**: Farhan Mukit
- **Age**: 21 years
- **Gender**: Male
- **Height**: 178 cm (5'10")
- **Weight**: 89 kg (196.2 lbs)
- **Medical Condition**: Hirschsprung's disease
- **Fitness Goal**: Weight maintenance
- **Activity Level**: Moderate

## Nutritional Targets
- **Daily Calories**: 2,950 kcal (± 50 kcal tolerance)
- **Protein**: 220g (± 5g tolerance)
- **Carbohydrates**: 375g (± 10g tolerance)
- **Fat**: 80g (± 5g tolerance)
- **Fiber**: >30g (critical for Hirschsprung's disease - high fiber needed)

## Key Files
- `rag_validation_summary.json`: Complete test results and analysis
- `case_X/meal_plan.json`: Generated meal plan for each test case
- `case_X/metadata.json`: Detailed analysis and nutritional breakdown
- `case_X/articles/`: Retrieved PMC articles (for RAG cases)
- `case_X/logs/`: Detailed execution logs and RAG pipeline traces

## Analysis
Compare the results across all 4 cases to evaluate:
1. **Medical Compliance**: How well each case handles Hirschsprung's disease requirements (HIGH fiber needed)
2. **Fiber Management**: Fiber content differences between RAG and non-RAG cases (higher is better)
3. **Nutritional Accuracy**: Macro and micronutrient target achievement
4. **RAG Effectiveness**: Impact of medical literature retrieval on meal plan quality

## Generated on
2025-10-27 03:34:02
