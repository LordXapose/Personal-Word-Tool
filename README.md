# Personal Word Tool

A lightweight, privacy-friendly desktop word processor built with **Python, PySide6, and python-docx**.

Personal Word Tool is an independent project designed to provide a simple alternative to Microsoft Word for opening, editing, and creating `.docx` documents.

The project is currently in early development, with the goal of gradually building a powerful desktop document editor with strong DOCX compatibility, professional editing features, and optional AI capabilities.

---

## 🚀 Current Status

**Version:** V2.0  
**Status:** Early Development  
**Platform:** Windows  
**Language:** Python

> This project is actively being developed. DOCX compatibility is still being improved.

---

## ✨ Current Features

### 📄 Document Management

- Create new documents
- Open `.docx` files
- Open `.txt` files
- Save documents
- Save As
- Drag & drop documents
- Open documents using command-line arguments
- Unsaved-change protection
- Basic error handling

### ✍️ Text Editing

- Bold
- Italic
- Underline
- Strikethrough
- Font selection
- Font size
- Text color
- Text highlighting
- Clear formatting
- Undo / Redo
- Cut / Copy / Paste
- Select All

### 📑 Paragraph Formatting

- Left alignment
- Center alignment
- Right alignment
- Justified alignment
- Bullet lists
- Numbered lists

### 🖼️ Images

Basic image support is available.

Supported formats include:

- PNG
- JPG
- JPEG
- BMP
- GIF
- WebP
- SVG where supported by Qt

The editor can:

- Insert images
- Load basic embedded images from DOCX
- Display images inside documents
- Save inserted images into DOCX

### 📊 Tables

- Insert tables
- Select number of rows
- Select number of columns
- Load basic DOCX tables
- Save tables into DOCX

### 🔗 Hyperlinks

- Insert hyperlinks
- Convert selected text into hyperlinks
- Load basic hyperlinks from DOCX
- Save hyperlinks into DOCX

### 🔎 Find & Replace

- Find
- Find next
- Replace
- Replace all

### 📄 Document Tools

- Page breaks
- Basic headers
- Basic footers
- Word count
- Character count
- Page estimation
- Zoom controls

---

# 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Application logic |
| PySide6 | Desktop GUI |
| python-docx | DOCX processing |
| lxml | XML processing |
| Qt QTextDocument | Rich-text editing |

---

# 📦 Installation

## Requirements

- Python 3.11+
- Windows 10/11 recommended

Install the dependencies:

```bash
pip install --upgrade PySide6 python-docx lxml
