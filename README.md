# 📄 `docsum.py` - Document Summarizer

**`docsum.py`** is a simple Python script that summarizes documents, web pages, PDFs, and images using the Groq LLM.

It can handle:
- Local `.txt` or `.html` files  
- `.pdf` documents  
- URLs to online news articles or web pages  
- Images (via URL)

---

## 📦 Usage

Run the script using the terminal with the following syntax:

---

### 📄 Text or HTML Files

```bash
python3 docsum.py <name of local txt or html file>
```

**Examples:**
```bash
python3 docsum.py constitution-mx.txt
```

```bash
python3 docsum.py news-mx.html
```

---

### 📚 PDF Files

```bash
python3 docsum.py <pdf file name>
```

**Example:**
```bash
python3 docsum.py research_paper.pdf
```

---

### 🌐 URLs

```bash
python3 docsum.py <URL>
```

**Example:**
```bash
python3 docsum.py https://elpais.com/us/
```

---

### 🖼️ Image Files

```bash
python3 docsum.py <image URL>
```

**Example:**
```bash
python3 docsum.py https://www.cmc.edu/sites/default/files/about/images/20170213-cube.jpg
```

---