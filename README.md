# AI_final


# ♟️ Chess Move Prediction from Board Images using GPT-4o and PyTorch

This project demonstrates how to:

- Convert FEN positions into images
- Use OpenAI's GPT-4o vision model to predict the best next move from an image
- Evaluate the performance using exact match accuracy and Levenshtein distance
- Optionally build a dataset and model training pipeline using PyTorch

---

## 📁 Project Structure

Final_IA_version_gpt/
├── train.csv # Dataset: FEN, best_move
├── jugadas/ # Folder containing board images (e.g., e2e4.png)
├── predictions.csv # Output of GPT-4o predictions
├── chess_move_predictor.ipynb # Main notebook for running the full pipeline
├── README.md # This file



---

## 🔁 Pipeline Overview

1. **Image Generation**: FEN strings from `train.csv` are converted into PNG images.
2. **GPT-4o Prediction**: Each image is sent to the GPT-4o API, which returns the best move.
3. **Evaluation**:
   - Exact match accuracy
   - Levenshtein distance
   - Quartiles (Q1, Q2, Q3) of distance distribution



