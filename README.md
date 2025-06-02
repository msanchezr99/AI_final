# AI_final


# ♟️ Chess Move Prediction from Board Images using GPT-4o and PyTorch

This project demonstrates how to:

- Convert FEN positions into images
- Use OpenAI's GPT-4o vision model to predict the best next move from an image
- Evaluate the performance using exact match accuracy and Levenshtein distance
- Optionally build a dataset and model training pipeline using PyTorch

---

## 📁 Project Structure

Final_IA_version_gpt/<br>
├── train.csv                   # Dataset: FEN, best_move<br>
├── gemini.csv                  # Gemini 2.5 pro predictions<br>
├── gemini_distance.csv         # Gemini predictions Levenshtein distance<br>
├── jugadas/                    # Generated board images<br>
├── predictions.csv             # GPT-4o predictions<br>
├── chess_move_predictor.ipynb  # Full pipeline<br>
├── README.md                   # Project documentation<br>



---

## 🔁 Pipeline Overview

1. **Image Generation**: FEN strings from `train.csv` are converted into PNG images.
2. **GPT-4o Prediction**: Each image is sent to the GPT-4o API, which returns the best move.
3. **Evaluation**:
   - Exact match accuracy
   - Levenshtein distance
   - Quartiles (Q1, Q2, Q3) of distance distribution

---

### Credits

Group formed by

Martín Sánchez,
Sebastian Amaya,
José Ramírez.
