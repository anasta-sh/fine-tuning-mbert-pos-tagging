# fine-tuning-mbert-pos-tagging

This university project explores the multilingual capabilities of mBERT for Part-of-Speech tagging across multiple languages. The project utilizes the Universal Dependencies (UD) dataset to maintain consistent annotation across languages for valid comparisons. It involves fine-tuning mBERT on French using the Universal Dependencies dataset, aligning mBERT’s tokenization with UD conventions, and analyzing its ability to transfer knowledge learned from one language (French in our case) to others (Italian, German, Russian and Indonesian). 

We can see that the fine-tuned model on French dataset, achieving a 98% validation accuracy, performs well on other tested languages: exceptionally well (93%) on Italian (due to linguistic similarities between French and Italian), enough well on German (87%), Russian(84%) and English (82%) and worst (78%) on Indonesian (due to its morphological and syntactic difference from French).
<img width="850" alt="image" src="https://github.com/user-attachments/assets/af38afb1-0582-4b78-bd50-82094c4f8931" />

Theses results demonstrate decent generalization capabilities of the model, but highlights the limitations of using a model trained on one language for other unrelated and typologically different languages.

Instructions:
- To launch the program, download the necessary datasets and save them to your Google Drive.
- To run the trainer, you need an API key from your profile on (https://wandb.ai/).
