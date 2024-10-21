# ASRC24

Adversarial Search Ranking competition Collection 2024 for "XX" paper.

## Dataset Description

The ASRC24 dataset comprises data from two different competitions:

| Competition | Ranking Function
|-------------|-----------------|
| B           | E5              |
| D           | E5 + MMR        |

Included in the dataset:
- XX documents submitted by students, XX of which are unique.
- 15 initial documents, one per topic.

Documents are stored in "trectext" format.

DOCNO Format: "ROUND-\<round_number\>-\<topic_id\>_\<competition\>-\<author_id\>"


## Queries

From the TREC 2009-2012 datasets, we selected topics with commercial intent likely to stimulate competition. 
Each topic is associated with a query.

The full list of selected queries is provided in "queries.txt".


## Relevance Judgments

Relevance was assessed by five annotators on Cloudresearch’s Connect platform, based on the topic title and backstory. 
Documents were rated relevant based on their alignment with the stated information need. 
A document’s relevance grade is the count of judges deeming it relevant.

diversity judgment was conducted XXX

Relevance grades can be found in "documents.rel".


## Quality Judgments

The quality of documents authored by students was also judged by five Cloudresearch annotators. Documents were evaluated as:
1. **Keyword-stuffed** - Contains unnatural repetition of keywords.
2. **Spam** - Content does not meet any conceivable information need.
3. **Valid** - Contents is neither spam nor keyword-stuffed.
A quality grade represents the count of judges who deemed a document valid.

Quality grades can be found in "students_documents.quality".


## Citations

Please cite the ASRC24 dataset as follows when using it in your research:

XXXXXXXXXXXX

