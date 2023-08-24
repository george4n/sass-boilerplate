# SASS Boilerplate

Welcome to SASS Boilerplate crafted by George Neophytou! Built upon the efficient 7-1 architecture pattern, this boilerplate ensures that your SASS projects are well-organized and maintainable.

## 🚀 Features

- Optimized Build Process: Utilize PostCSS, Autoprefixer, and CSSNano for optimized and cross-browser compatible CSS.
- Live Reloading: Browser-sync ensures real-time updates as you code.
- File Watching: Automatic detection and processing of file changes, both in SASS and HTML files.
- Asset Management: Automated asset copying from source to public directory.

## 📦 Prerequisites
Ensure you have Node.js installed, as this boilerplate uses npm for package management.

## 🛠 Setup

1. Clone the Repository

```bash
git clone https://github.com/your-username/sass-boilerplate.git
```
2. Navigate to the Directory

```bash
cd sass-boilerplate
```

3. Install Dependencies
```bash
npm install
```

4. Start the Development Server

```bash
npm start
```

Now, you should have the development server up and running. Happy coding!

## 🚢 For Deployment
When you're ready to deploy, compile and optimize your SASS code into production-ready CSS by running:

1. Build the project

```bash
npm run build
```

2. Optimize CSS
The postbuild script will automatically run after the build, optimizing and prefixing your CSS.

## 🔧 Scripts Overview
Your boilerplate comes packed with various scripts to aid development:

- build:sass: Compile SASS to CSS without source maps.
- copy:assets: Copy assets from source to public directory.
- copy:html: Copy HTML files from source to public directory.
- watch:*: Watch for changes in assets, SASS, and HTML files and run appropriate tasks.
- serve: Start a development server with browser-sync.
- postbuild: Optimize and prefix CSS using PostCSS.

## 📚 Dependencies
Your project uses the following key dependencies:

- autoprefixer: Prefix CSS to ensure cross-browser compatibility.
- browser-sync: Keep your browser in sync with code changes.
- copyfiles: Simplifies copying of files and assets.
- cssnano: Minify and optimize CSS.
- npm-run-all: Run multiple npm scripts sequentially or in parallel.
- onchange: Watch files and run commands when they change.
- postcss-cli: Command-line interface for PostCSS.

## 🗂 7-1 Architecture Overview
The 7-1 pattern divides the SASS files into 7 folders and 1 main file. Here's a brief overview:

- base/: Holds the boilerplate styling.
- components/: For small components, buttons, and similar styling.
- layout/: Styling for larger layout components; e.g. header, footer, etc.
- pages/: Specific styles for individual pages.
- themes/: Different themes for the application.
- abstracts/: Sass tools, helpers, variables, and function files.
- vendors/: External libraries and CSS.
- main.scss: The primary SASS file which imports everything.

## 📝 License
This project is open-source and available under the MIT License.