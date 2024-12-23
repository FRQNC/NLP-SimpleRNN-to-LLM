# NLP from SimpleRNN to fine tuning LLM
Repositori ini dibuat untuk memenuhi tugas pada mata kuliah NLP

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
