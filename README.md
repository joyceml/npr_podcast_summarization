## A NPR Podcast Summarization algorithm using extractive and abstractive summarization

Created by Kaavya Shah and Joyce Li for our MIDS Data W266 final project


## Repository Files

1. **Podcast Summarization with NPR Transcripts.pdf**
    - Final paper explaining all research and work completed in this project
    - Contains project results and final summary examples
2. **transcript_cleaning.ipynb**
    - Script written to clean scraped transcripts and descriptions from html tags, extra new lines, soundbites, etc.
3. **modeling.ipynb** 
    - Baseline model: combining Bert Extractive Summarizer (trained on lectures) and BART-CNN abstractive model
4. **textrank.ipynb**
    - Final model: running textrank on NPR transcripts training set for final model
5. **abstractive fine-tuning.ipynb**
    - Final model: fine-tuning BART-CNN on extractive summaries of NPR transcripts, generating summaries on test set and Spotify test data, calculating ROUGE scores
6. **analysis.ipynb**
    - Pulls summary examples from final model to read
