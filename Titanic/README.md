# [🎥 Titanic EDA Slideshow](https://nisanman.github.io/Kaggle/#/)

![Jupyter Logo](https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg)
<a href="https://pandas.pydata.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="40"/></a>
## 📌 Overview
Create an interactive **Jupyter slideshow** for Titanic data analysis.

---

## 📂 Dataset
Passenger details, demographics, and survival info.  
📥 [Download from Kaggle](https://www.kaggle.com/competitions/titanic/data).

---

## ⚙️ Jupyter Slideshow Setup
### **1️⃣ Enable Slideshow Mode**
🔹 Go to **View ➡️ Cell Toolbar ➡️ Slideshow**

### **2️⃣ Assign Slide Types**
| Type       | Description                          | Navigation |
|------------|--------------------------------------|------------|
| **Slide**      | Starts a new slide                  | ➡️ |
| **Sub-Slide**  | Replaces previous slide content    | ⬇️ |
| **Fragment**   | Adds content to the same slide     | ⬇️ & ➡️ |
| **Skip**       | Hidden in the presentation         | ❌ |
| **Notes**      | Speaker notes (not displayed)      | 📝 |

---

## 🛠 Convert to Presentation
Run the following commands in your terminal:

```bash
# Convert to slideshow
jupyter nbconvert --to slides "presentation.ipynb"
```
```bash
# Convert with hidden code
jupyter nbconvert --to slides --no-input "presentation.ipynb"
```
