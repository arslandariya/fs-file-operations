# FS File Operations Web App

A **Node.js web application** to **create, read, and edit files** using the built-in `fs` module.  
The app uses **Express.js** for server-side routing, **EJS** for rendering dynamic templates, and **Tailwind CSS** for modern UI styling.

---

## Features

- **Create File**: Add new files with custom name, type, and content.  
- **Read File**: View the content of any file dynamically.  
- **Edit File Name**: Rename existing files.  
- **File Types Supported**: HTML, CSS, JS, Python, Java, C++, C, JSON, TypeScript, PHP, Ruby, Go, Rust, Swift, Kotlin, SQL, XML, YAML, Markdown, Text.  
- **Responsive UI**: Works on desktop and mobile devices.  
- **Dynamic Templates**: Uses **EJS** to render file lists and file content dynamically.

## Project Structure

fs-file-operations/
├─ files/ # Folder where user files are stored
├─ public/ # Static assets
├─ views/ # EJS templates
│ ├─ index.ejs # Homepage / list of files
│ ├─ edit.ejs # Edit file name page
│ └─ show.ejs # Read file content page
├─ .env # Environment variables (ignored by Git)
├─ .gitignore # Ignore node_modules and .env
├─ app.js # Main Express server file
├─ package.json
└─ README.md


## Prerequisites

- **Node.js** installed (v14+ recommended)  
- Basic knowledge of JavaScript and Node.js  

---

## Installation

1. **Clone the repository**:

```bash
git clone https://github.com/arslandariya/fs-file-operations.git
Navigate to the project folder:

bash
Copy code
cd fs-file-operations
Install dependencies:

bash
Copy code
npm install
Create a .env file (optional):

env
Copy code
PORT=3000
Usage
Start the server:

bash
Copy code
node app.js
Open your browser:

arduino
Copy code
http://localhost:3000
App Features:

Create a File → Fill name, content, type → Submit

Read a File → Click "Read More"

Edit a File → Click "Edit File" → Change name and type → Submit

All files are stored in the files/ folder.
EJS templates dynamically render file lists and file content.

Notes
Do not commit .env or node_modules to GitHub.

File names are trimmed of spaces automatically.

Supports most programming and markup languages.

Author
Arslan Dariya
