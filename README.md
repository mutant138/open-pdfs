# 📄 Open-PDFs Contribution Guide

Welcome to **Open-PDFs**, a platform where students can contribute handwritten PDFs and e-books for learning and sharing knowledge.

---

## 📌 Contribution Rules

### 📝 **Handwritten PDFs**  

✅ **Maximum Pages:** 20 pages per submission.  
✅ If the document exceeds **20 pages**, create **Part 2** (e.g., "Lecture Notes Part 2").  
✅ Ensure the handwriting is **clear and readable**.  
✅ Upload files in **PDF format only**.  

### 📚 **E-Books**  

✅ **No page limit** – you can upload full e-books.  
✅ Must be in **PDF format** and properly formatted for easy reading.  

---

## 📌 Naming Convention

To maintain consistency, use the following format when naming your PDF files:

```
CATEGORY_PDF_NAME.pdf
```

### **Examples:**  
- **DSA_Top_Questions.pdf**  
- **Maths_Algebra_Part1.pdf**  
- **Physics_Notes_Part2.pdf**  

---

## 🚀 How to Contribute

### 🔄 **Pull Latest Changes**
Before making any changes, pull the latest updates from the repository:
```sh
git pull origin main
```

### 📁 **Add Your PDF File**
1. Place your PDF inside the appropriate category folder.  
2. Follow the **naming convention** while saving the file.  

### ✅ **Push Your Changes**

#### 1️⃣ **Stage Your File**
```sh
git add CATEGORY_PDF_NAME.pdf
```

#### 2️⃣ **Commit Your Changes**
```sh
git commit -m "Added DSA_Top_Questions.pdf"
```

#### 3️⃣ **Push to Repository**
```sh
git push origin main
```

---

## 🛠 **Creating a New Branch (Optional)**
If you are working on a feature or fixing something, create a new branch:
```sh
git checkout -b feature-branch-name
```
Push changes to your branch:
```sh
git push origin feature-branch-name
```
Then, create a **Pull Request (PR)** on GitHub.

---

## ⚠️ Important Notes

🔹 Ensure your file **follows the rules** (max 20 pages for handwritten PDFs).  
🔹 Use the **correct naming format** before pushing.  
🔹 Avoid duplicate files – check before uploading.  

Happy Contributing! 🚀📚
