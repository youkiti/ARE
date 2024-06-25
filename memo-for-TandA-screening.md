# Title and Abstract Screening
To conduct the title and abstract screening for our systematic review, we followed a multi-step process:
## Random Sampling:
Initially, we performed a random sampling of 50 abstracts from our search results.
## Independent Review:
Two independent reviewers assessed the sampled abstracts using Rayyan, a web application for systematic reviews(citation). Each reviewer independently categorized the abstracts as either “included” or “excluded.” Any abstract judged as “included” by at least one reviewer was treated as the reference standard for inclusion.
## Filtering Using GPT-4o:
We utilized the OpenAI application programming interface to employ GPT-4 (specifically the GPT-4o-05-13 model) for further screening of titles and abstracts. The screening was guided by a prompt developed from the protocol by a single researcher. We used the exported CSV file from Rayyan as input data for this process. The source code can be accessed at GitHub (https://github.com/youkiti/ARE/blob/postspinal-hypotension/TA_screening_zeroshot_imai.ipynb). The performance of the GPT-4o filter on the 50 abstracts showed a sensitivity of 0.94 and a specificity of 0.79.
## Human Review of Filtered Abstracts:
After applying the GPT-4o, One reviewer manually reviewed the remaining 578 abstracts. Additionally, another reviewer independently evaluated the remaining 1683 abstracts before filtering. Any discrepancies in the inclusion/exclusion decisions were resolved through discussion and consensus.
## Decision for Full Text Review:
Based on the resolved decisions, we finalized the list of studies to be included in the full-text review phase.
