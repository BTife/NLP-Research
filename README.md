# NLP-Research
Research on Nigerian Pidgin translation and sentiment analysis using natural language processing.
This UR2PhD team research project explores how natural language processing (NLP) systems handle Nigerian Pidgin, especially the spelling variations, slang, code-switching, and context found in online posts. The research proposal outlines a plan to prepare and annotate text, evaluate Pidgin-to-English translation and sentiment classification, and examine common model errors.

#### Project status: 
This repository currently presents the research proposal and a summary of the work described on my resume. This is a proposal and project overview. The proposal alone does not establish that the planned dataset, models, application, or performance improvements were completed. Any future code, results, or data will be described separately when they are available and approved for release.

## Why this matters
Nigerian Pidgin is used widely in everyday communication, but language models trained mainly on standardized languages can miss the meaning or emotional tone of informal Pidgin text. A word-for-word translation may also lose humor, idioms, or cultural context. This project studies those limitations and how better data preparation and evaluation might improve performance.

## Research goals
1. Investigate how multilingual models translate informal Nigerian Pidgin into English.
2. Classify Pidgin text as positive, neutral, or negative and study difficult cases such as sarcasm, slang, and code-switching.
3. Prepare and document annotated examples while respecting source terms, privacy, and permission to release data.
4. Compare outputs against baselines using quantitative metrics and bilingual review.
5. Explore a small demonstration interface for translation and, if supported by evaluated models, sentiment analysis.

## My contribution
As an undergraduate researcher, I worked on preparing and cleaning Nigerian Pidgin social media data, refining labels, and evaluating translation and sentiment analysis results. I used precision, recall, F1 scores, and confusion matrices to identify errors and guide model improvements. 

## Proposed approach
| Area | Proposed approach |
| --- | --- |
| Data preparation | Collect eligible Nigerian Pidgin text, remove irrelevant or duplicate posts, and clean the text while preserving meaningful expressions. |
| Annotation | Pair selected Pidgin text with English translations and label each example as positive, neutral, or negative. Bilingual reviewers check disagreements. |
| Translation | Compare a baseline translation system with a multilingual model adapted to Nigerian Pidgin. |
| Sentiment | Evaluate positive, neutral, and negative predictions using class-level precision, recall, F1, and a confusion matrix. |
| Error analysis | Review mistakes involving slang, spelling differences, code-switching, humor, and idioms. |
| Web application | If feasible, build a React and FastAPI demo where users enter text and view a translation. |

## Results and reproducibility
The resume associated with this project mentions an approximately 15–25% improvement in accuracy and F1. That figure is not documented by the proposal alone. Before presenting it here as a result, I need to provide the dataset and test split, baseline and final scores, metric definitions, experiment settings, and my role in those experiments. No result should be inferred from the proposal's expected outcomes.
| Task | What we studied | How we evaluated it |
| --- | --- | --- |
| Translation | Nigerian Pidgin to English | BLEU, chrF, and human review |
| Sentiment analysis | Positive, neutral, or negative text | Precision, recall, F1, and confusion matrix |

## Repository contents
- [`proposal.pdf`](proposal.pdf) — cleaned research proposal, if the team approves its public release.

## Team and attribution
The research proposal names **Oluwatomiwa Baruwa, Oluwatobi Olajide, Iyinoluwa Ayodele, and Abimbola Olorogun** as authors. 

## Background resources
The proposal discusses NaijaSenti, Masakhane, JW300, and multilingual translation models.
