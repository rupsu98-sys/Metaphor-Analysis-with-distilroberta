# Metaphor-Analysis-with-distilroberta
This project fine-tunes a **DistilRoBERTa model** for **metaphor detection** inspired by T.S. Eliot's *The Love Song of J. Alfred Prufrock*. This project uses a small, illustrative dataset designed for metaphor detection and analysis. It contains two types of conversations:

Professor–student dialogue discussing T.S. Eliot’s The Love Song of J. Alfred Prufrock.
Casual student conversation about the poem.

The dataset demonstrates how the model handles both literary and informal contexts, providing a foundation for training and evaluating metaphor detection with DistilRoBERTa.
It demonstrates how large language models can be adapted for literary and cognitive semantic tasks. ## ✨ Features - Uses Hugging Face's distilroberta-base as backbone. - Fine-tuned for **binary sequence classification** (metaphor vs. non-metaphor). - Includes evaluation with **accuracy, precision, recall, and F1-score**. - Saves trained models for reuse (./models/prufrock_roberta). ## 📂 Project Structure - prufrok.convo_Roberta.(metaphor analysis with Roberta).ipynb – main notebook with code. - models/prufrock_roberta/ – directory for saving trained models (auto-created). - data/ – expected dataset location (you can adapt to your own). ## 🛠 Requirements Install dependencies:
