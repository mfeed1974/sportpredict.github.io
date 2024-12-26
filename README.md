CSV Column Selector
A lightweight web application for processing CSV files and selecting specific columns for export. Built with TypeScript and running entirely in the browser without server-side dependencies.
Features
Pure browser-based CSV processing
File size limit: 300kB
Column selection interface with modern dark theme
Export selected columns to a new CSV file
Responsive design
No server-side requirements
Tech Stack
TypeScript
Webpack
PapaParse for CSV processing
Modern CSS with Flexbox
Project Structure
text
TSWEBAPP/
├── dist/
├── node_modules/
├── src/
│   ├── types/
│   └── app.ts
├── index.html
├── webpack.config.js
├── package.json
├── package-lock.json
└── tsconfig.json
Installation
Clone the repository
Install dependencies:
bash
npm install
Development
Run the development server:
bash
npm start
Build
Create a production build:
bash
npm run build
Usage
Open the application in a web browser
Click "Choose File" to select a CSV file (max 300kB)
Select the columns you want to keep
Click "Process CSV" to download the new CSV with selected columns
Dependencies
papaparse: CSV parsing library
typescript: Programming language
webpack: Module bundler
ts-loader: TypeScript loader for webpack
License
MIT
Author
[mfeed1974]
