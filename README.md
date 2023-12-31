# Independent Study, Summer 2022, University of Colorado Boulder

## Study and design of NER & Text extraction from OCR scanned Handwritten Slave Trade Volumes

#### Supervisors: Prof. Henry Lovejoy, Digital Slavery Research Lab, and Dr. Jane Wall, Faculty Director, Data Science

I worked on an Independent Study supervised by Prof. Henry Lovejoy for the Digital Slavery Research Lab, at the University of Colorado, Boulder. It was towards study and design of Named Entity Recognition from OCR scanned Handwritten Slave Trade Volumes and to train a search over OCR scanned documents. 

#### Goal
The novel goal is that of not only emancipating Africans from
historical events and providing valuable insights, but also seems to indicate
a shift to emancipate from the present-day impressions of the past.
To analyze and emancipate people from present impressions of the past.

Acknowledgements:
Thanks to the <a href="https://www.colorado.edu/lab/dsrl/collaborators">Digital Slavery Research Lab/collaborators </a>.

- <a href="https://github.com/sushmaakoju/study-work-reports/blob/main/university-of-colorado-boulder/sushma-akoju-independent-study-digital-slavery-first_summary_report.pdf"> First report: study and design of Named Entity Extraction from OCR scanned Handwritten Slave Trade Volumes and to train a search over OCR scanned documents<a/>

- <a href="https://github.com/sushmaakoju/study-work-reports/blob/main/university-of-colorado-boulder/sushma-akoju-digital-slavery-project-indep_study_final_report.pdf"> Second report: study and design of Named Entity Extraction from OCR scanned Handwritten Slave Trade Volumes and to train a search over OCR scanned documents<a/>

- The challenge here was that Named Entity Recognition needs to run over the text extracted from the 19th-century English language text corpus. Performance over BERT under zero-shot settings was poor for 80% of the vocabulary. So we used <a href="https://github.com/sushmaakoju/macberth-eval">MacBERTh</a> model.

View the Notebooks for each one of the following:

1. <a href="https://nbviewer.org/github/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/extract_from_listofpapers_june17.ipynb">Extracting "List of papers" Pages using Tesseract and Transkribus manual annotations for Regions of Interest (ROI) for layout segmentations</a>

2. <a href="https://nbviewer.org/github/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/automated_annotation_layout_parser_segmentation.ipynb"> Zero-shot layout segmentation annotations evaluation</a>

3. <a href="https://github.com/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/sushma_akoju_july_19_class_A_analysis.ipynb">Text extraction with Google Document AI API and text extraction over class **A** documents, Slave trade volumes</a>

4. <a href="https://github.com/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/sushma_akoju_july_20_class_B_analysis.ipynb">Text extraction with Google Document AI API and text extraction over class **B** documents, Slave trade volumes</a>

5. <a href="https://github.com/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/sushma_akoju_pos_analysis.ipynb">Annotating IOB tags from Parts-of-speech tags and Named Entities from ground truth over-extracted text from OCR scanned Handwritten Slave Trade Volumes</a>
