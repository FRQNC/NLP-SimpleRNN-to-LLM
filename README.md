# NLP from SimpleRNN to fine tuning LLM
Repositori ini dibuat untuk memenuhi tugas pada mata kuliah NLP.

Slide presentasi ([Canva](https://www.canva.com/design/DAGaKu4Qkp8/7WSXOdOcbdxetxAsyrLwOg/edit?utm_content=DAGaKu4Qkp8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton))
## Dataset
Dataset yang digunakan pada projek ini adalah IndoSum yang berisikan teks artikel berita dan ringkasannya.
([https://github.com/kata-ai/indosum](https://github.com/kata-ai/indosum))
- Fold pertama pada dataset (train.01, dev.01, test.01) digunakan untuk training pada seluruh model
- Untuk training dan validasi digunakan seluruh data yang berada pada datasetnya (14262 data training, 750 data untuk validasi)
- Untuk testing hanya menggunakan 100 data awal saja

## Model LLM
Untuk model LLM yang digunakan adalah :
- google/mt5-small untuk T5 based ([https://huggingface.co/google/mt5-small](https://huggingface.co/google/mt5-small))
- unsloth/Llama-3.2-1B-bnb-4bit ([https://huggingface.co/unsloth/Llama-3.2-1B-bnb-4bit](https://huggingface.co/unsloth/Llama-3.2-1B-bnb-4bit))

## Platform
Google Colab dan Kaggle digunakan untuk mengerjakan projek ini, berikut adalah link dari projek-projek yang ada
- SimpleRNN ([Colab - SimpleRNN](https://colab.research.google.com/drive/1zkScBnPqgJRBVVT8_ZgvuSGfbBI6Rb-c?usp=sharing))
- LSTM ([Colab - LSTM](https://colab.research.google.com/drive/18CTXcA0Z466EnhmKGT-775uptSP6rqWk?usp=sharing))
- Transformer ([Kaggle - Transformer](https://www.kaggle.com/code/furqonalhaqqi/nlp-transformer))
- Fine Tuning mt5-small ([Colab - Fine Tuning mt5-small](https://colab.research.google.com/drive/18yGdQcE52flyaoDFkBrt2VZY4h9Vw8EH?usp=sharing))
- Llama-3.2-1B In context learning ([Kaggle - Llama-3.2-1B ICL](https://www.kaggle.com/code/muhamadfurqon/nlp-llama-3-2-1b-unsloth-in-context-learning))
- Llama-3.2-1B Fine Tuning ([Kaggle - Llama-3.2-1B Fine Tuning](https://www.kaggle.com/code/muhamadfurqon/nlp-llama-3-2-1b-fine-tuning))
- Llama-3.2-1B Fine Tuned - Generate ([Kaggle - Llama-3.2-1B Fine Tuned - Generate](https://www.kaggle.com/code/muhamadfurqon/nlp-llama-3-2-1b-unsloth-fine-tuned-generate))
