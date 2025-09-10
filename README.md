# Strasbourg University Web Development Course Repository

Welcome to this repository!  
Here you will find the source code used during our classes in **HTML, CSS, and PHP**.  
The goal is for you to fork this repository and practice directly in your own GitHub Codespace.

---

## How to get started

1. **Fork this repository**  
   - Click on the **Fork** button (top right of the GitHub page).  
   - This creates **your own copy** of the course repository under your GitHub account.  

2. **Open in Codespaces**  
   - On your fork, click the green **Code** button.  
   - Choose **Codespaces** → **Create Codespace on main**.  

3. **Start coding!**  
   - The Codespace already comes with some useful extensions pre-installed (see below).  
   - You will find all course examples organized by folder (HTML, CSS, PHP).  

---

## Pre-installed Extensions

The Codespace is configured to automatically install these extensions:

- **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)**  
  Start a development server for your HTML/CSS/JS files with live reload.  

- **[Open in Browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)**  
  Allows you to open an HTML file directly in your browser (optional, but convenient).  

- **[PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)**  
  Provides IntelliSense for PHP: autocomplete, code navigation, error checking.  

---

## Running PHP Code

You have **two options** to run PHP scripts in Codespaces:

### Option 1: Install PHP Server Extension (manual installation)
- Open the Extensions panel in Codespaces (`Ctrl+Shift+X`).  
- Search for **PHP Server (by brapifra)** and install it.  
- Then right-click a PHP file → **PHP Server: Serve Project**.  
- A preview link will appear in the **Ports** tab.

### Option 2: Use the built-in PHP server (recommended)
- Open a terminal in Codespaces.  
- Check if PHP is available:  
  ```bash
  php -v
- Run the development server:
  php -S 0.0.0.0:8000
- Open the Ports tab at the bottom of Codespaces.
- Find port 8000, then click the link to preview your PHP app in the browser.

---

## Syncing your fork with the teacher’s repository
Sometimes the teacher will update the original repository.
To keep your fork up to date:
- Go to your fork on GitHub.
- Click the Sync fork button (next to the green Code button).
- Accept the pull request to merge the updates into your copy.

  
