# `docusm.py` - Document Summarizer

**`docusm.py`** is a simple Python script that summarizes documents, web pages, PDFs, and images using the Groq LLM.

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
python3 docusm.py <name of local txt or html file>
```

**Examples:**
```bash
python3 docusm.py declaration.txt
The Declaration of Independence asserts that the thirteen united colonies have the right to sever ties with Great Britain and establish themselves as independent states. This decision is based on the belief that the British government has repeatedly abused and usurped the rights of the colonies, leading to a breakdown in the relationship between the two. The document goes on to list a series of grievances against King George III and the British government, concluding that the colonies must now take control of their own destinies and govern themselves as independent nations.
```




---

### PDF Files

```bash
python3 docusm.py <pdf file name>
```

**Example:**
```bash
python3 docusm.py research_paper.pdf
The research paper proposes a novel unsupervised pretraining method called DOCSPLIT, designed to improve the representation of large documents. DOCSPLIT uses contrastive learning to force models to consider the entire global context of a document, outperforming existing methods on various downstream tasks. The authors demonstrate significant improvements on document classification, few-shot learning, and document retrieval tasks using DOCSPLIT-pretrained models.
```

---

### URLs

```bash
python3 docusm.py <URL>
```

**Example:**
```bash
python3 docusm.py https://elpais.com/us/
The text appears to be a collection of JavaScript and CSS code, as well as news articles and headlines from a Spanish-language news website, El País. The code includes settings, configurations, and styles for a web application, while the articles cover a range of topics including politics, sports, economy, and culture. The text also includes references to specific CSS files, fonts, and layout information, suggesting that it is part of a web design project or online application.
```

---

### Image Files

```bash
python3 docusm.py <image URL>
```

**Example:**
```bash
python3 docusm.py https://www.cmc.edu/sites/default/files/about/images/20170213-cube.jpg
summarizing image
ChatCompletionMessage(content='The image depicts a modern building with a glass structure and a pool of water in front of it. The scene is set at dusk, with the sky turning dark blue and clouds visible.\n\n*   **Glass Structure:**\n    *   The glass structure is a square-shaped building with a flat roof.\n    *   It has a large open area inside with several chairs and tables.\n    *   The interior is well-lit, suggesting that it may be used for socializing or relaxation.\n*   **Pool of Water:**\n    *   The pool of water is rectangular and reflects the light from the glass structure.\n    *   It appears to be a shallow pool, possibly used for aesthetic purposes rather than swimming.\n*   **Surrounding Buildings:**\n    *   There are two other buildings visible in the background, one on either side of the glass structure.\n    *   These buildings appear to be multi-story and have a more traditional design compared to the modern glass structure.\n*   **Sky and Clouds:**\n    *   The sky is dark blue, indicating that it is either dusk or dawn.\n    *   There are some clouds visible in the sky, adding texture and depth to the image.\n*   **Overall Atmosphere:**\n    *   The image conveys a sense of serenity and tranquility, with the peaceful surroundings and calm water creating a soothing atmosphere.\n    *   The modern design of the glass structure and the surrounding buildings suggests a contemporary and sophisticated setting.\n\nIn summary, the image presents a serene and modern scene, featuring a glass structure with a pool of water in front of it, surrounded by other buildings and set against a dark blue sky with clouds.',
```

---