# BART Fine-tuning for Text Summarization

A deep learning project focused on fine-tuning the BART (Bidirectional and Auto-Regressive Transformers) model for scientific text summarization using the CiteSUM dataset.

## 🎯 Project Overview
This project implements a text summarization system by fine-tuning BART on scientific papers. The model is optimized to generate concise, accurate summaries while maintaining the technical essence of scientific documents.

## 🚀 Features
- Scientific paper summarization
- Abstractive summary generation
- Custom fine-tuning pipeline
- ROUGE metric evaluation
- Flexible input handling

## 🛠️ Technical Implementation

### Model Architecture
- Base Model: facebook/bart-base
- Type: Sequence-to-Sequence Transformer
- Training Approach: Fine-tuning
- Dataset: CiteSUM

### Training Pipeline
1. **Data Preprocessing**
   - Text cleaning and formatting
   - Token length management
   - Dataset preparation and splitting

2. **Model Fine-tuning**
   - Custom training arguments
   - Learning rate optimization
   - Batch size adjustment
   - Gradient accumulation

3. **Evaluation**
   - ROUGE score metrics
   - Model performance analysis
   - Summary quality assessment


## 📈 Results
- Improved summarization quality for scientific texts
- ROUGE score metrics evaluation
- Comparison with baseline models

## 🎯 Future Improvements
- Multi-GPU training support
- Additional dataset integration
- Model compression techniques
- Web interface development
- Batch processing capability

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 👨‍💻 Author
Madan Mohan Bammidi
- GitHub: [@MadanMohanBammidi](https://github.com/MadanMohanBammidi)

## 🙏 Acknowledgments
- Hugging Face team for the Transformers library
- BART model developers
- CiteSUM dataset creators
