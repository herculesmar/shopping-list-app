# shopping-list-app

A minimalist browser tool for quickly creating and managing personal shopping items. Built as a hands-on project to practice core DOM manipulation, event handling, and form processing using vanilla JavaScript.

[Live Demo](https://herculesmar.github.io/shopping-list-app/)

## Overview

This project implements a quick-entry shopping list without external frameworks or dependencies. It handles immediate DOM updates, dynamic element creation, and form lifecycle management natively in the browser.

### Key Logic & Mechanics
* **Form Submission & Keybindings:** Listens on form submission rather than raw button clicks, allowing seamless `Enter` key creation alongside button clicks.
* **Dynamic DOM Management:** Instantiates list nodes, child text spans, and contextual action buttons on the fly using native Web APIs.
* **Input Clean-up & Focus:** Trims trailing whitespace to prevent empty entries and automatically refocuses the input field for continuous data entry.

## Tech Stack

* HTML5 (Semantic forms & structure)
* CSS3 (Clean baseline layout & element spacing)
* JavaScript / ES6+ (Native DOM methods & event handling)

## Local Setup

Clone the repository and launch the application directly in your browser:

```bash
git clone [https://github.com/herculesmar/shopping-list-app.git](https://github.com/herculesmar/shopping-list-app.git)
cd shopping-list-app
open index.html # Or double-click index.html in your file manager
