## 📋 Table of Contents

- [📋 Table of Contents](#-table-of-contents)
- [🌟 Introduction](#-introduction)
- [🕹️ Features](#️-features)
- [📂 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [📄 License](#-license)

---

## 🌟 Introduction

This project is built using [MkDocs with the Material theme](https://squidfunk.github.io/mkdocs-material/) , providing a clean and responsive design for the documentation.

---


## 🕹️ Features

- 📘 **Code Documentation**  
- 📝 **Blog Section**
- 🏷️ **Tags & Search**
- 🎨 **Custom Design**

---

## 📂 Project Structure

Here’s a high-level view of the project directory:

```bash
mkdocs-blog/
│
├── .github/
│  └── workflows/
│     └── ci.yml
│
├── docs/
│  ├── assets/
│  │  ├── bits.ico
│  │  ├── favicon.ico
│  │  ├── home-bg.jpg
│  │  └── logo.png
│  │
│  ├── blog/
│  │  ├── posts/
│  │  │  ├── first-post.md
│  │  │  └── second-post.md
│  │  │
│  │  ├── .authors.yml
│  │  └── index.md
│  │
│  ├── coding/
│  │  ├── python.md
│  │  └── random-forest.md
│  │
│  ├── stylesheets/
│  │  └── extra.css
│  │
│  ├── javascripts/
│  │  └── mathjax.js
│  │
│  ├── index.md
│  ├── about.md
│  └── tags.md
│
├── hooks/
│  └── socialmedia.py
│
├── overrides/
│  └── partials/
│     └── comments.html
│
├── site/
│  └── ...
│
├── .gitignore
├── mkdocs.yml
├── LICENSE.txt
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Ensure you have the following installed:
- Python 3.10+
- MkDocs Material theme

---

### Installation

1. Clone the repository:

   ```bash
   $ git clone https://github.com/Mohammed-Gamal/mkdocs-blog.git  
   $ cd mkdocs-blog
   ```

2. Install the dependencies:

   ```bash
   $ pip install -r requirements.txt
   ```

3. Run the local development server:

   ```bash
   $ mkdocs serve
   ```

---

### 📄 License

This project is licensed under the [MIT License](https://opensource.org/license/mit). See the LICENSE file for details.

---

👨‍💻 Made with ❤️ by [Mohamed Gamal](https://github.com/Mohammed-Gamal)
