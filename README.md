# 🔁 Reverse a Number – Attempting MIRO FIRST TIME EVER

Welcome! This is a personal learning project where I break down the logic of reversing a number.  
What started as a challenging concept during my early programming journey is now a documented milestone, visualized using a flowchart and implemented in Python.

---

## 💡 Why This Project?

When I was learning basic programming, I found the logic for **reversing a number** confusing at first — the loop, modulus, integer division — it all felt like magic.

Instead of just memorizing the code, I wanted to **understand it visually**. That’s when I decided to make a flowchart using [Miro](https://miro.com/), and everything finally clicked!

This project is a reflection of that moment of clarity.

---

## 📊 Visual Flowchart (Made in Miro)

To make the logic easier to grasp, I created a simple visual flowchart of how the number reversal works step by step.

> 📌 Exported from Miro as a PNG

![Reverse Number Flowchart](flowcharts/reverse_number_flowchart.png)

---

## 💻 Python Implementation

Here’s the actual Python code that reverses a number using a `while` loop:

```python
# Program to reverse a number using while loop

def reverse_number(n):
    rev = 0
    while n != 0:
        rev = rev * 10 + n % 10
        n = n // 10
    return rev

# Example usage
num = 1234
print("Original Number:", num)
print("Reversed Number:", reverse_number(num))
```

📂 File path: `code/reverse_number.py`

---

## 🚀 How to Run

If you want to try it yourself:

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/reverse-number-flowchart.git
   cd reverse-number-flowchart
   ```

2. Run the code:
   ```bash
   python3 code/reverse_number.py
   ```

---

## 🧠 What I Learned

- The power of **visualization** when logic feels confusing
- Breaking a problem into **tiny steps** helps it stick
- The importance of documenting learning for future reference

---

## 🛠 Tools Used

- 🧩 [Miro](https://miro.com/) – for flowchart creation  
- 🐍 Python – for code implementation  
- 🌐 GitHub – for hosting and sharing the project

---

## 📚 Additional Notes

- You’ll find the flowchart in the `flowcharts/` folder.
- The Python code is in `code/`.

---

## 🤝 Let’s Connect

If you're someone who learns best with visuals too — I feel you!  
Feel free to explore, use, or even fork this repo for your own learning path.  
Let’s grow together.

[![GitHub](https://img.shields.io/badge/GitHub-Visit-blue?style=flat&logo=github)](https://github.com/JissaAanJuby)

---

> 🧠 *“Understanding is deeper when you can draw it.”*
