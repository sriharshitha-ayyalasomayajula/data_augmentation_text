# Medical Question-Answering with BioBERT and Data Augmentation

This repository demonstrates how **data augmentation** and **BioBERT fine-tuning** can enhance medical question-answering tasks. The project explores using **synthetic data augmentation** with techniques like **NLPAug** and **DistilGPT-2** to address challenges in training robust models for healthcare-related tasks.

## Project Overview

Medical question-answering models often face limitations due to the lack of diverse and labeled datasets. This project addresses these challenges by:
- Utilizing **synthetic data augmentation** to enhance the dataset.
- Fine-tuning **BioBERT** for improved accuracy.
- Evaluating model performance using BLEU and ROUGE metrics.

### Key Features:
1. **Data Augmentation**:
   - Synthetic data generation using NLPAug and GPT-based models.
2. **Fine-Tuning BioBERT**:
   - Adapted BioBERT for question-answering tasks using augmented data.
3. **Model Evaluation**:
   - Compared augmented datasets' performance using BLEU and ROUGE scores.

### Practical Applications in Healthcare:
- Automating patient query responses in virtual health assistants.
- Enhancing diagnostic tools without compromising data privacy.
- Scalable and cost-effective improvement of medical AI systems.

## Dependencies

This project requires the following Python libraries:
- `transformers`
- `torch`
- `pandas`
- `nltk`
- `rouge_score`
- `google-cloud-storage`

## Getting Started

1. Clone the repository:
   ```bash
   git clone repostitory 
   ```

2. Run the code block 

## Usage

1. **Data Augmentation**:  
   Replace the provided dataset with your own to generate synthetic data using NLPAug or GPT models.

2. **Model Fine-Tuning**:  
   Fine-tune BioBERT on augmented datasets for custom question-answering tasks.

3. **Evaluation**:  
   Use BLEU and ROUGE metrics to evaluate the performance of your fine-tuned model.

---

## Results

- **BLEU Score**: 0.533  
- **ROUGE-1**: 0.833  
- **ROUGE-2**: 0.831  
- **ROUGE-L**: 0.833  

These metrics indicate significant improvements in the model's ability to generate accurate and fluent answers.

--

## Conclusion

This project demonstrates how **Generative AI** and **data augmentation** techniques can improve the performance of medical question-answering models. It highlights the importance of leveraging synthetic data for creating robust and scalable healthcare AI solutions.

---
