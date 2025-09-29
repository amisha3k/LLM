# LLM From Scratch 🚀

This project demonstrates how to **build a Large Language Model (LLM) from scratch**, implementing every key component step by step without relying on pre-built deep learning frameworks for transformers.

The goal is to understand **how LLMs work under the hood** — from tokenization, embeddings, and transformer blocks, to attention mechanisms and text generation.

---

## 📂 Project Structure

- **custom_tokenizer.ipynb** → Implements a tokenizer for breaking text into tokens.  
- **LLM_model.ipynb** → Combines all components into a working LLM model.  
- **llm.ipynb** → Final pipeline to train and generate text.  
- **layer_normalization.ipynb** → Implements Layer Normalization for stable training.  
- **gelu_function.ipynb** → GELU activation for smoother gradients.  
- **multi-head-attention.ipynb** → Multi-head attention mechanism for parallel context learning.  
- **shortcut_connection.ipynb** → Residual (skip) connections to improve gradient flow.  
- **loss.ipynb** → Cross-entropy loss for training.  
- **pretraining_loss.ipynb** → Pretraining loss setup for masked/next-word prediction.  
- **generating_text.ipynb** → Final text generation pipeline.  
- **tem_topK_sampling.ipynb** → Implements temperature scaling and Top-K sampling for diverse text generation.  

---

## 🧩 Steps Implemented

### 1. Tokenization
- Built a custom tokenizer to convert raw text into tokens.  
- Created a vocabulary and token-to-ID mapping.  

### 2. Embeddings
- Implemented token embeddings to represent tokens in dense vector space.  
- Added positional embeddings to preserve sequence order.  
- Combined into a vector embedding layer.  

### 3. Transformer Block
- **Multi-Head Attention**: Parallel attention heads to learn contextual relationships.  
- **Scaled Dot-Product Attention**: Core mechanism for focusing on relevant tokens.  
- **Residual Connections (Skip connections)**: Prevents vanishing gradients.  
- **Layer Normalization**: Ensures training stability.  
- **Feed Forward Network with GELU activation**: Introduces non-linearity.  

### 4. Model Training
- Implemented cross-entropy loss for next-word prediction.  
- Added pretraining loss functions to simulate how large models are trained.  

### 5. Text Generation
- Used the trained model to predict the next word given a context.  
- Implemented **Temperature Scaling** → controls randomness of predictions.  
- Implemented **Top-K Sampling** → selects from top-k likely words to improve fluency.  

---

## 🔮 Key Features
- **Built from scratch** → No black box, full understanding of each part.  
- **Implements the full transformer architecture**.  
- **Supports temperature & Top-K sampling for controllable text generation**.  
- **Modular notebooks** → Each file focuses on a single concept.  
