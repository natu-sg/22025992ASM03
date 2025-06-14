## Description
A student uploads 5 academic articles and asks:

> "What are the most common limitations of using decision trees in business analytics?"

NotebookLM responds by:
- Highlighting 3 articles with relevant answers
- Quoting paragraphs directly from those sources

## Evaluation
- **Accuracy & Relevance:** High. Returned paragraphs contain terminology like "overfitting", "low interpretability", and "bias in categorical splitting", all aligned with textbook definitions.
- **Academic Usefulness:** Very useful for cross-comparing sources without manually scanning PDFs.
- **Limitations:** Cannot detect nuances like outdated or low-quality sources.

## Conclusion
This feature enhances critical review skills and is suitable for production with human oversight.

""",

    "automatic_summarization.md": """# Scenario: Automatic Summarization

## Description
A student uploads 5 research articles on customer segmentation. Each article is summarized automatically into under 300 words.

## Evaluation
- **Accuracy & Relevance:** Summaries are concise and cover the abstract + findings effectively.
- **Academic Usefulness:** Helpful for quickly reviewing methodologies and comparing results.
- **Limitations:** Occasional omission of key limitations or context (e.g., data bias mentioned in footnotes).

## Conclusion
Useful for academic workflows. Should be used with access to the full article for verification.

""",

    "notebook_organization.md": """# Scenario: Notebook Organization

## Description
Student creates 3 folders: *Methodology*, *Findings*, and *Critiques*. Notes from each uploaded article are tagged and filed automatically into these sections.

## Evaluation
- **Accuracy & Relevance:** Tags and placement were mostly accurate (~90%).
- **Academic Usefulness:** Helps with structured thinking and thematic synthesis.
- **Limitations:** Manual re-tagging may be needed when research overlaps multiple themes.

## Conclusion
Strong organizational feature. Valuable for research reports and literature reviews.

""",

    "citation_tracking.md": """# Scenario: Citation Tracking

## Description
When a student copies a sentence or fact from NotebookLM’s output, a reference with source name and page number is auto-attached.

## Evaluation
- **Accuracy & Relevance:** Citation accuracy is reliable. All tested references matched source documents.
- **Academic Usefulness:** Excellent for academic integrity and referencing.
- **Limitations:** Does not support complex citation styles (e.g., APA7 in-text + full ref formatting).

## Conclusion
Production-ready. Ideal
