# KYAU Lab Report Cover Generator 🎓

A simple, automated web tool to generate standardized lab report cover pages for the students of Khwaja Yunus Ali University (KYAU).

## 🌟 Overview

Tired of making the same lab report cover page again and again? This automated tool is designed specifically for KYAU students to instantly generate a perfectly formatted, A4-sized PDF cover page directly from their browser. No need to mess with Word document formatting or alignment issues anymore!

### 🔗 Live Preview
[https://shahriar-shorif.github.io/kyau-lab-report-generator/] 
*(Example: https://your-username.github.io/kyau-lab-report-generator/)*

## ✨ Features

* **Real-time Preview:** See the cover page update instantly as you type.
* **Perfect A4 Size:** Generates a flawlessly formatted, single-page PDF.
* **Auto Superscript:** Automatically formats `1st`, `2nd`, `3rd`, `4th` etc., into proper superscripts.
* **Client-Side Generation:** Completely secure and fast. No data is sent to any server. It uses `html2pdf.js` to create the PDF directly in your browser.
* **Pre-filled Defaults:** Common fields like Course Title, Teacher's Name, and Semester are pre-filled to save time.

## 🛠️ Technology Stack

* **HTML5 & CSS3** for structure and styling.
* **Bootstrap 5** for the responsive input form layout.
* **JavaScript (Vanilla)** for real-time text binding and logic.
* **html2pdf.js** for converting the HTML DOM element into a high-quality PDF.

## 🚀 How to Use Locally

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/your-username/kyau-lab-report-generator.git](https://github.com/your-username/kyau-lab-report-generator.git)
    ```
2.  Navigate to the project folder.
3.  Because the `html2pdf.js` library needs to read the local image (`kyau.png`), opening `index.html` directly in the browser (`file:///`) might cause CORS errors when downloading the PDF.
4.  **Recommended Solution:** Open the project in VS Code and use the **Live Server** extension to run the project. 

## 🤝 Contribution

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/kyau-lab-report-generator/issues). If you want to add support for other departments or improve the design, just fork the repo and create a pull request.

## 👨‍💻 Author

**Shoriful Islam**
* Student, Dept. of CSE, Khwaja Yunus Ali University
* GitHub: [@your-username](https://github.com/Shahriar-Shorif/)

---
*Made with ❤️ for the students of KYAU.*
