# Neural Extractive Summarization on Scientific Articles (NESSA)

## Introduction


## Data
### Training Data

The extractive summaries are based on the TalkSumm (Lev et al. 2019) dataset. The dataset contains 1705 automatically-generated noisy extractive summaries of scientific papers from the NLP and Machine Learning domain based on video talks from associated conferences (e.g., ACL, NAACL, ICML)  Summaries can be found under data/extractive/. Each summary provides the top-30 sentences, which are on average around 990 words.  The format of each summary file is as follows:

* Each line contains: sentence index (in original paper), sentence score (i.e. duration), then the sentence itself. The fields are tab-separated.
* The order of the sentences is according to their order in the paper.
* Link to the reference paper.

### Test Data
 
* **CLi SciSumm 2016**
* **CLi SciSumm 2017**
* **SciSummNet 2019**

### Todo
Complete code of CNES wil be uploaded soon...!!!
