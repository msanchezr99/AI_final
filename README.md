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

## Video
[Link to the video](https://eafit-my.sharepoint.com/personal/jmramirezg_eafit_edu_co/_layouts/15/stream.aspx?id=%2Fpersonal%2Fjmramirezg%5Feafit%5Fedu%5Fco%2FDocuments%2FGrabaciones%2FCall%20with%20Martin%20and%201%20other%2D20250601%5F143542%2DMeeting%20Recording%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E786c206e%2D2e93%2D4686%2Daa43%2D7eb69d87817a)

---

### Credits

Group formed by
José Manuel Ramírez,
Martín Sánchez,
Sebastián Amaya

