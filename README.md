<<<<<<< HEAD
# Spider R&D — ML Inductions Task 1

Submission for Spider R&D Machine Learning Induction Tasks.

## Tasks Completed
- ✅ Base Task — Fashion-MNIST Neural Network (PyTorch)
- ✅ Applied ML Domain — RAG Research Paper Q&A System

## Repository Structure
spider_ml_task_1/
├── base_task/
│   ├── notebooks/        ← Training notebook
│   ├── saved_models/     ← Model weights
│   └── submission.csv    ← Test predictions
│
└── applied_ml_domain/
└── chatbot_code/     ← RAG pipeline notebook

## Quick Summary

### Base Task
- Built a 3-layer Neural Network in PyTorch
- Trained on Fashion-MNIST (60,000 images, 10 classes)
- Achieved ~88-90% validation accuracy

### Applied ML Domain
- Built end-to-end RAG pipeline
- Ingests 7 research papers on NLP and LLMs
- Answers conceptual and cross-paper questions with source citations

---

*A huge thank you to **Spider R&D** for designing such a thoughtful and 
challenging induction. These tasks were a great learning experience!*
=======
# Applied ML Domain — RAG Research Paper Q&A

## Problem Statement
Build a RAG pipeline that answers questions from 7 NLP research papers.

## Pipeline
PDFs → Extract Text → Chunk → Embed → FAISS Store
↓
Question → Embed → Search FAISS → Retrieve Chunks → LLM → Answer

## Research Papers
| Paper | Topic |
|-------|-------|
| Attention Is All You Need | Transformer architecture |
| BERT | Bidirectional pre-training |
| GPT-3 | Few-shot learning |
| RAG | Retrieval augmented generation |
| Sentence-BERT | Sentence embeddings |
| LoRA | Efficient fine-tuning |
| Llama 2 | Open source LLMs |

## Tech Stack
| Library | Purpose |
|---------|---------|
| LangChain | Pipeline orchestration |
| FAISS | Vector database |
| HuggingFace sentence-transformers | Text embeddings |
| PyPDF | PDF extraction |
| Groq Llama 3.1 | Answer generation |

## Demo
🎥 **Chatbot Demo:** [Add your screen recording link here]

## How to Run
1. Open `chatbot_code/rag_pipeline.ipynb` in Google Colab
2. Run Cell 1 to install dependencies
3. Run all cells in order
4. Papers download automatically

*Thank you Spider R&D for this opportunity!*
>>>>>>> c63955b2985200e58ebe419fb1f701602281f77b
