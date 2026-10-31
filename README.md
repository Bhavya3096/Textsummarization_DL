# Deep Learning Based Text Summarisation Using Transformer Architecture

## Project Overview

This project implements an abstractive text summarisation system using a pretrained Transformer-based deep learning model. It takes lengthy text as input and generates a shorter, meaningful summary while preserving the key information.

The project uses the **DistilBART CNN model (`sshleifer/distilbart-cnn-12-6`)** from Hugging Face Transformers. The implementation is performed using Python and PyTorch in Google Colab.

## Objectives

- Develop an automated text summarisation system using deep learning.
- Apply Transformer architecture for abstractive text summarisation.
- Generate concise summaries from lengthy text documents.
- Evaluate summarisation performance using ROUGE metrics.
- Analyse the relationship between input text length and generated summary length.

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- DistilBART
- Google Colab
- Matplotlib
- ROUGE evaluation metrics

## Model Architecture

The project uses the pretrained DistilBART model, which is based on the Transformer encoder-decoder architecture.

The encoder processes the input text and captures its contextual information. The decoder generates a concise summary based on the encoded representation.

Model: `sshleifer/distilbart-cnn-12-6`

## Project Workflow

1. Import the required Python libraries.
2. Load the pretrained DistilBART tokenizer and model.
3. Prepare sample input documents.
4. Tokenise the input text.
5. Generate summaries using the Transformer model.
6. Evaluate generated summaries using ROUGE-1, ROUGE-2 and ROUGE-L.
7. Visualise evaluation scores and text compression results.
8. Export generated summaries and evaluation results.

## Evaluation Metrics

The system uses the following ROUGE metrics:

- **ROUGE-1:** Measures unigram overlap between generated and reference summaries.
- **ROUGE-2:** Measures bigram overlap between generated and reference summaries.
- **ROUGE-L:** Measures the longest common subsequence between generated and reference summaries.

These metrics help assess the similarity between generated summaries and reference summaries.

## Repository Structure

```text
deep-learning-text-summarisation/
│
├── Text_Summarisation.ipynb
├── README.md
│
├── results/
│   ├── text_summarisation_results.csv
│   └── generated_summaries.txt
│
├── report/
│   └── Deep_Learning_Project_Report.docx
│
└── images/
    ├── rouge_evaluation.png
    └── summary_comparison.png
```

## How to Run the Project

1. Clone or download this repository.
2. Open `Text_Summarisation.ipynb` using Google Colab.
3. Run the notebook cells sequentially.
4. Allow the pretrained DistilBART model to download.
5. Execute the summarisation and evaluation sections.
6. View the generated summaries, evaluation scores and visualisations.

**Note:** An active internet connection is required to download the pretrained model from Hugging Face.

## Results

The project generates summaries for sample input documents and evaluates them using ROUGE metrics. It also provides visualisations comparing input text length, generated summary length and evaluation scores.

The notebook exports the generated summaries and evaluation results as downloadable files.

## Project Type

Academic Deep Learning Project

## Author

**Tarun Lanka**
