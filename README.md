# 🖼️ Stock Image Scraper

A web scraping project that automatically extracts **image URLs, titles, tags, and metadata** from a stock image website. Built using Python and Jupyter Notebook, this scraper helps gather datasets for machine learning, research, or creative work.

---

## 📌 Project Overview

This project scrapes stock images and their metadata from a chosen website's pages. The extracted data can be used for:

* Dataset creation
* Computer vision training
* Market analysis
* Research projects

Depending on the website structure, the scraper can extract:

* ✔️ Image URLs
* ✔️ Image titles / alt text
* ✔️ Tags / categories
* ✔️ Photographer names (if available)
* ✔️ Image resolutions
* ✔️ Download links (if allowed)

All scraped data is stored in a **CSV file** or displayed in the notebook.

---

## 🛠️ Tech Stack

### **Languages & Tools**

* Python
* Jupyter Notebook

### **Libraries Used**

* `requests` – Fetch HTML pages
* `BeautifulSoup` – Parse & extract elements
* `pandas` – Save scraped data into DataFrame/CSV
* `os` – Optional image-saving utility
* `urllib` – Download images

---

## 📂 Project Structure

```
📦 Stock-Image-Scraper
├── 📄 Stock Image Scraper.ipynb
├── 📄 README.md
├── 📁 images_downloaded (optional)
├── 📁 data
│   └── image_metadata.csv
└── 📁 screenshots (optional)
```

---

## ▶️ How to Run the Project

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/stock-image-scraper.git
cd stock-image-scraper
```

### **2. Install Required Libraries**

```bash
pip install requests beautifulsoup4 pandas
```

*Add this if you're downloading images:*

```bash
pip install pillow
```

### **3. Launch the Notebook**

```bash
jupyter notebook
```

Open: **Stock Image Scraper.ipynb**

---

## 🧩 Features

### 🔹 **1. Web Scraping**

* Extracts image URLs from home/category pages
* Scrapes metadata (title, tags, description)
* Handles multiple pages (if implemented)

### 🔹 **2. Data Storage**

Stores scraped info in:

* CSV file
* DataFrame
* JSON (optional)

### 🔹 **3. Image Downloading (Optional)**

You can enhance the notebook to:

* Download all high-resolution images
* Organize into category folders

### 🔹 **4. Rate Limit & Error Handling**

Includes:

* Try/Except wrappers
* Request status checks
* Pause between requests (optional)

---

## 📊 Example Output

Sample CSV content:

```
image_url,title,tags
"https://images.com/photo/123", "Sunset Landscape", "sunset, nature, orange"
"https://images.com/photo/987", "Office Workspace", "office, business, laptop"
```

---

## 🚀 Future Improvements

* Add pagination scraping
* Add download functionality
* Multi-threaded scraping
* Integrate with Selenium for JS-heavy websites
* Add CLI version

---

## 🤝 Contributing

Pull requests and feature suggestions are always welcome!

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If this project helped you, please consider giving it a **star ⭐ on GitHub**!
