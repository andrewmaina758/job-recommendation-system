Synthetic Dataset README
=======================

Files generated:
- students_synthetic.csv
- jobs_synthetic.csv
- synthetic_data_dictionary.csv

Design assumptions:
1. Student experience years are correlated with school year and degree level.
2. Student skills are sampled from major-specific skill pools with occasional cross-domain skills.
3. Job titles, industries, and skills are generated from aligned major-to-career mappings so recommendations are meaningful.
4. Intern roles are always assigned Entry experience level.
5. Some locations include 'Remote' to support location-aware recommendation experiments.
6. Company IDs and Student IDs are generated administrative identifiers.

Recommended use:
- Use students_synthetic.csv as the learner profile table.
- Use jobs_synthetic.csv as the job postings table.
- Split the Skill and Job Skills columns into lists for matching.
- Use the data dictionary to explain what is generated vs synthetic-realistic.
