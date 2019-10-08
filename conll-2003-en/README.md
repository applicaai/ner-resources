This is an instruction for additional content for publication `Named Entity Recognition - is there a glass ceiling?` (https://arxiv.org/abs/1910.02403).  

### List of supplementary files 

1. Diagnostic data sets (this data contain `\t` char as separator): 
   1. `document_context_sentences_BIO_v1.0.txt` - file in BIO format for Document Context Sentences (for each document we provide link to Wikipedia)
   1. `template_sentences_BIO_v1.0.txt` - file in BIO format for Template Sentence (for each sentence we provide link to Wikipedia with list of entities to be replaced)
1. Errors analyse sample data set `errors_analyse_sample_v1.0.csv` / `errors_analyse_sample_v1.0.xlsx` - files with our annotations with fallowing columns:
   1. `document index` - index of a document/article in CoNNL 2003 test set 
   1. `sentence index` - index of a sentence in document/article in CoNNL 2003 test set 
   1. `sentence text` - sentence text which suited to provided indexes (just for clarification)
   1. `CONLL annotation` - list of entities which originally was tagged as gold standard    
   1. `entity error` - list of words (or single word) on which some of model wrongly tagged 
   1. `DE-A` - linguistic category `document error - annotation`
   1. `DE-BS` - 1/0 if match with linguistic category `document error - bad segmentation` 
   1. `DE-WT` - 1/0 if match with linguistic category `document error - word typo`
   1. `SL-C` - 1/0 if match with linguistic category `sentance level - context`
   1. `SL-S` - 1/0 if match with linguistic category `sentance level - structure`
   1. `DL-CR` - 1/0 if match with linguistic category `document level - co-reference`
   1. `DL-S` - 1/0 if match with linguistic category `document level - structure`
   1. `G-A` - 1/0 if match with linguistic category `general - amibiguity`
   1. `G-HC` - 1/0 if match with linguistic category `general - hard case`
   1. `G-I` - 1/0 if match with linguistic category `general - incosistence`
