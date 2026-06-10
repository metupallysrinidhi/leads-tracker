# Leads Tracker Chrome Extension

A simple Lead Tracker application built using HTML, CSS, and JavaScript. This project allows users to save website URLs, store them in Local Storage, and access them later. It can be used both as a regular web application and as a Chrome Extension.

##  Features

* Save custom links manually
* Save the currently active browser tab
* Store leads using Local Storage
* Display saved leads dynamically
* Open saved links in a new tab
* Delete all saved leads
* Works as a Chrome Extension
* Works as a standalone web application

##  Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Local Storage 
* Chrome Extension 
* Chrome Tabs API

## Project Structure

```text
leads-tracker/
│
├── images/
│   └── dollar.png
│
├── Lead-Tracker.html
├── Lead-Tracker.css
├── Lead-Tracker.js
├── manifest.json
├── README.md
│
└── screenshots/
    ├── web-version.png
    └── extension-version.png
```

##  Running as a Web Application

1. Open `Lead-Tracker.html` in your browser.
2. Enter a URL in the input field.
3. Click **SAVE INPUT**.
4. The link will be stored in Local Storage and displayed on the page.

## Running as a Chrome Extension

1. Open Chrome.
2. Visit:

```
chrome://extensions
```

3. Enable **Developer Mode**.
4. Click **Load Unpacked**.
5. Select the project folder.
6. Click the extension icon in Chrome.
7. Use **SAVE TAB** to save the currently active browser tab.

##  How It Works

### SAVE INPUT

Allows users to manually enter a URL and save it.

### SAVE TAB

Uses the Chrome Tabs API to capture the URL of the currently active browser tab and store it in Local Storage.

### DELETE ALL

Double-clicking the delete button clears all saved leads from Local Storage.

### Local Storage

The application stores data using:

```javascript
localStorage.setItem()
```

and retrieves data using:

```javascript
localStorage.getItem()
```

The leads are stored as an array and converted using:

```javascript
JSON.stringify()
JSON.parse()
```

## Screenshots

Add screenshots of:

* Web Application Version
* Chrome Extension Version

inside the `screenshots` folder.

##  Future Improvements

* Edit saved leads
* Delete individual leads
* Export leads
* Search saved links
* Dark Mode support

## Author

Srinidhi

GitHub: https://github.com/metupallysrinidhi

```
```
