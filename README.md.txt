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