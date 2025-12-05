🖼️ Image Scraping from Google Images

A Python-based project to automatically scrape and download images from Google Images using Selenium and BeautifulSoup.

---

## 📌 **Project Overview**

This project allows you to enter a keyword (example: "cats", "cars", "flowers") and automatically download multiple relevant images from Google Images.
It uses browser automation to scroll, load images, capture URLs, and save them into a local folder.

---

## 🚀 **Features**

* 🔍 Search any keyword on Google Images
* 📥 Automatically scrape hundreds of images
* 📄 Uses Selenium for browser automation
* 🧹 Cleans duplicates
* 📁 Stores all images in a well-structured folder
* 🐍 Simple, beginner-friendly Python code

---

## 🛠️ **Tech Stack**

| Tool                         | Purpose                                     |
| ---------------------------- | ------------------------------------------- |
| **Python**                   | Main programming language                   |
| **Selenium**                 | Automate Google Images scrolling & clicking |
| **BeautifulSoup / Requests** | Extract image URLs                          |
| **OS, Time, urllib**         | File handling & downloading                 |
| **ChromeDriver**             | Driver for Selenium                         |

---

## 📦 **Installation**

Install required dependencies:

```bash
pip install selenium
pip install beautifulsoup4
pip install requests
```

## ▶️ **How to Run the Project**

1. Open the project notebook:
   **Image Scrapping (Google Images).ipynb**

2. Update the search keyword in the input section of the notebook.

3. Run all cells sequentially.

4. Images will be saved automatically into an output folder (e.g., `downloads/flowers/`).

---

## 📂 **Project Structure**

```
📁 Image-Scraping-Project
│── 📓 Image Scrapping (Google Images).ipynb
│── README.md
```

---

## 📸 **Output Example**

* For keyword: **“Sunset”**
  You will get:
  `images/sunset/img_1.jpg`
  `images/sunset/img_2.jpg`
  ... and so on.

---

## 🧪 **Future Improvements**

* Add multi-keyword scraping
* Add progress bar
* Improve UI with a simple frontend
* Deploy as a web app (Flask/Streamlit)

---

## 👤 **Author**

**Shyam Sundar Pareek**
