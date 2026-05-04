# AIKR-Project

# StyleSense — AI Fashion Stylist for Everyone

> **Smart suggestions. Effortless style. Every day, your way.**

StyleSense is an AI-powered fashion styling web app built with Streamlit. It provides personalized outfit recommendations, smart wardrobe suggestions, and occasion-based styling advice — making professional fashion guidance accessible to everyone.

---

## Project Description

StyleSense leverages the power of generative AI to act as your personal fashion stylist. Whether you're dressing for a job interview, a casual outing, or a special occasion, StyleSense analyzes your preferences and generates tailored outfit ideas with smart recommendations.

**Key Features:**
- **Personalized Outfits** — Recommendations based on your style preferences and body type
- **Smart Recommendations** — AI-driven suggestions that adapt to your wardrobe
- **For Every Occasion** — Styling advice for casual, formal, festive, and more
- **Always On Trend** — Up-to-date fashion insights powered by AI

**Live Demo:** [https://aikr-project-epihzgygwmulhj57ayhhci.streamlit.app/](StyleSense Link)

---

## Installation Steps

### Prerequisites
- Python **3.8 or higher**
- `pip` package manager

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/stylesense.git
cd stylesense
```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv

# On Windows
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

If a `requirements.txt` is not present, install the core packages manually:

```bash
pip install streamlit anthropic pillow requests
```

### 4. Set Up Environment Variables

Create a `.env` file in the root directory and add your API key:

```
ANTHROPIC_API_KEY=your_api_key_here
```

Or set it directly in your terminal:

```bash
# macOS/Linux
export ANTHROPIC_API_KEY=your_api_key_here

# Windows
set ANTHROPIC_API_KEY=your_api_key_here
```

---

## How to Run the Project

```bash
streamlit run st.py
```

The app will open automatically in your browser at:

```
http://localhost:8501
```

---

## Example Input / Output

### Example 1 — Casual 

**Input:**
```
Occasion : Casual
Gender   : Female
Top      : Crop Top


```

**Output:**
```
✨ Outfit Suggestion:
- White linen wide-leg trousers
- Pastel lavender fitted crop top
- Nude strappy sandals
- Minimal gold hoop earrings
- Beige tote bag

💡 Stylist Tip: Tuck in the top slightly on one side for an effortless asymmetric look.
```

---

### Example 2 — Formal

**Input:**
```
Occasion : Formal
Gender   : Male
Top      : White Shirt

```

**Output:**
```
✨ Outfit Suggestion:
- Navy slim-fit chinos
- Crisp white button-down shirt
- Grey blazer
- White leather sneakers or oxford shoes
- Minimalist watch

💡 Stylist Tip: Roll up your blazer sleeves slightly for a modern, relaxed professional look.
```

---

### Example 3 — Festive / Party

**Input:**
```
Occasion : Festive party
Gender   : Female
Top      : Saree

```

**Output:**
```
✨ Outfit Suggestion:
- Red Saree
- Bangles
- Silver Jhumkas
- Black Heels
- Small clutch bag

💡 Stylist Tip: Keep makeup bold on one feature — either eyes or lips — to balance the statement outfit.
```

---

## Project Structure

```
stylesense/
├── app.py                 # Code
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## Requirements

```
streamlit
anthropic
pillow
python-dotenv
requests
```

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
