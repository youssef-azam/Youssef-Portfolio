# Youssef Azam - Data Engineer Portfolio

This is the completely modernized and rebuilt portfolio website for Youssef Azam, showcasing expertise as a Data Engineer.

## Key Features
- **Modern Design:** Dark-themed UI with cyan and electric blue accents, tailored for the tech and data engineering industry.
- **Responsive Layout:** fully functional on Mobile, Tablet, and Desktop devices.
- **Animations:** Scroll reveal animations (AOS) and typing effects for an interactive experience.
- **Data Engineering Focus:** Highlights critical skills like ETL/ELT, Apache Spark, Airflow, Snowflake, PostgreSQL, AWS, Databricks, MinIO, Kafka, and more.
- **Featured Projects:** Showcases the latest CV projects with abstract, high-quality generated images.
- **No Heavy Frameworks:** Built with pure HTML5, Vanilla CSS3, and Vanilla JavaScript for maximum performance and easy deployment.

## Project Structure
```text
YoussefAzam_Portfolio_Modern/
│
├── index.html        # Main HTML structure and content
├── css/
│   └── style.css     # Custom styles, variables, typography, and responsive rules
├── js/
│   └── script.js     # Interactivity, typing effect, and intersection observers
└── assets/           # Images (profile picture, project screenshots, abstract graphics)
```

## How to Run Locally

Since this project is built using standard HTML/CSS/JS, no complex build steps or dependencies are required.

### Method 1: Directly in Browser
1. Open the `YoussefAzam_Portfolio_Modern` folder.
2. Double-click the `index.html` file to open it in your default web browser.

### Method 2: Using VS Code Live Server (Recommended)
1. Open the `YoussefAzam_Portfolio_Modern` folder in VS Code.
2. Install the **Live Server** extension if you haven't already.
3. Right-click on `index.html` and select **"Open with Live Server"**.
4. The website will automatically open in your browser at `http://localhost:5500` and will reload whenever you save changes.

### Method 3: Using Python HTTP Server
If you have Python installed, you can quickly serve the files:
1. Open your terminal or command prompt.
2. Navigate to the project directory: `cd path/to/YoussefAzam_Portfolio_Modern`
3. Run: `python -m http.server 8000`
4. Open your browser and navigate to `http://localhost:8000`.

## Customization
- **Colors & Theming:** All main colors are defined as CSS variables at the top of `css/style.css` inside the `:root` block. Modify them to adjust the theme globally.
- **Content:** To update your experience or projects in the future, simply edit the corresponding sections in `index.html`.
- **Images:** Add new project images to the `assets/` folder and link them in the `<img src="./assets/... ">` tags inside `index.html`.
