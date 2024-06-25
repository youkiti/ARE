# Full-Text Extraction
We used the Adobe Extract PDF API to extract full text.

# Screening Using GPT
We used the OpenAI GPT API to employ GPT-4. We defined a detailed system prompt to guide the GPT model in determining the inclusion or exclusion of manuscripts based on predefined criteria. For each combined text, the GPT model was prompted to decide on inclusion or exclusion, and to extract drug names, dosages, and administration details. 
The source code can be accessed at GitHub ([https://github.com/youkiti/ARE/blob/postspinal-hypotension/TA_screening_zeroshot_imai.ipynb](https://github.com/youkiti/ARE/blob/postspinal-hypotension/fullText_processing_for_github.ipynb))

# Conflict Resolution
One reviewer determined the inclusion or exclusion criteria, masking the GPT's results.
The GPT model's judgments on inclusion were directly compared to the human reviewer's judgments.
For the GPT model's judgments on exclusion, one reviewer checked the decisions and then compared them to another reviewer's decisions, who was masked to the GPT's results.
Any conflicts were resolved through discussion with human reviewers.
