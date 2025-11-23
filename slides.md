---
marp: true
title: Product Documentation with Marp
description: Multi-format developer documentation powered by Marp
paginate: true
footer: "Page $page / $total"
math: katex
theme: ./theme/custom-tech-docs.css
---

<!-- _class: lead -->

# Product Documentation with Marp  
### Creating Maintainable, Version-Controlled Docs  
**Email:** <22f3003000@ds.study.iitm.ac.in>

---

# Why Use Marp?

- Version controlled documentation (`git`)
- Single Markdown source → PDF, PPTX, HTML
- Custom themes for company branding
- Supports math (KaTeX), diagrams, images
- Easy to automate with GitHub Actions

---

<!-- _backgroundImage: url('images/background.jpg') -->
<!-- _backgroundSize: cover -->
<!-- _color: white -->

# Background Image Example

This slide demonstrates a background image stored in the repository.

---

# Project Structure

marp-product-docs/
├─ slides.md
├─ images/
│ ├─ background.jpg
│ └─ architecture.png
└─ theme/
└─ custom-tech-docs.css



---

# Algorithmic Complexity

Inline math example:  
Time complexity: $O(n \log n)$

Block-level example:

$$
T(n) = T(\frac{n}{2}) + O(n)
$$

Therefore:

$$
T(n) = O(n \log n)
$$

---

# Using Custom Themes

Your custom theme file:


Provides:

- Custom fonts  
- Corporate colors  
- Better spacing  
- Styled headers & footers

---

# Exporting

You can export to:

- **PDF**
- **PPTX**
- **HTML**

Using:
- VS Code Extension  
- GitHub Actions  
- Marp Web App  

---

# GitHub Raw URL

You can access the source Markdown here:

https://raw.githubusercontent.com/
<USERNAME>/<REPO>/main/slides.md


(Substitute your GitHub username and repository.)

---

# Thank You

For questions, contact:  
📧 <22f3003000@ds.study.iitm.ac.in>


