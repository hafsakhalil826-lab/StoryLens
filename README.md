# StoryLens

NLP-based user story quality and security gap analyzer.
*Find vague and unsafe user stories before they become expensive bugs.*

## What it does
- Ambiguity detection with explanations
- Security gap detection for stories involving sensitive data or functions
- Duplicate story detection and theme grouping
- Suggested rewrites and acceptance criteria (human-reviewed)
- Summary report with figures computed in code

## Tech stack
Python, spaCy, scikit-learn, sentence-transformers, FastAPI, Next.js, TypeScript, pytest

## Datasets
Download these and place them in `data/raw/` (not stored in this repo):

[1] C. Okechukwu, "User Story Ambiguity Dataset: A Comprehensive Research Resource," Mendeley Data, V1, Jul. 11, 2025. doi: 10.17632/wz9spjy4v5.1
[2] F. Dalpiaz, "Requirements data sets (user stories)," Mendeley Data, V2, Dec. 19, 2024. doi: 10.17632/7zbk8zsd8y.2

## Status
Work in progress.