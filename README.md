# `docsum.py` - Document Summarizer

**`docsum.py`** is a simple Python script that summarizes documents, web pages, PDFs, and images using the Groq LLM.

It can handle:
- Local `.txt` or `.html` files  
- `.pdf` documents  
- URLs to online news articles or web pages  
- Images (via URL)

---

## Usage

Run the script using the terminal with the following syntax:

---

### Text or HTML Files

```bash
python3 docsum.py <name of local txt or html file>
```

**Examples:**
```bash
python3 docsum.py declaration.txt
The Declaration of Independence asserts that the thirteen united colonies have the right to sever ties with Great Britain and establish themselves as independent states. This decision is based on the belief that the British government has repeatedly abused and usurped the rights of the colonies, leading to a breakdown in the relationship between the two. The document goes on to list a series of grievances against King George III and the British government, concluding that the colonies must now take control of their own destinies and govern themselves as independent nations.
```




---

### PDF Files

```bash
python3 docsum.py <pdf file name>
```

**Example:**
```bash
python3 docsum.py research_paper.pdf
```

---

### URLs

```bash
python3 docsum.py <URL>
```

**Example:**
```bash
python3 docsum.py https://elpais.com/us/
```

---

### Image Files

```bash
python3 docsum.py <image URL>
```

**Example:**
```bash
python3 docsum.py https://www.cmc.edu/sites/default/files/about/images/20170213-cube.jpg
```

---