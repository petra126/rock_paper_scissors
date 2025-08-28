# rock_paper_scissors 

A real-time Rock-Paper-Scissors game using hand gesture recognition with OpenCV. Play against the computer using your webcam!

---

## Screenshot

![Gameplay Screenshot](assets/screenshot.png)

---

## How to Run

Run the following commands in your terminal:

```bash
# Clone the repository
git clone https://github.com/petra126/rock_paper_scissors.git
cd rock_paper_scissors

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook rock_paper_scissors.ipynb
```
---

## Controls

- ESC → Exit the game
- Show Rock, Paper, or Scissors hand gesture in the webcam ROI

---

## How it Works

- The game detects your hand using OpenCV.
- Counts fingers to determine Rock (0), Paper (5), or Scissors (2).
- Plays against a random computer choice and updates the score.

---

## Technologies Used

- Python 3
- OpenCV
- NumPy
- scikit-learn
- Jupyter Notebook

---

