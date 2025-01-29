# Week 2 Day 3 - Creating a Nav Bar and using the `<main>` element

## What is Forking a Repository?
Forking a repository means making a copy of someone else's project on GitHub so you can work on it independently. Here’s how you can do it:

1. Go to the GitHub page of the project you want to copy.
2. Click the **Fork** button in the top-right corner.
3. Wait for GitHub to create your own copy of the project.
4. To work on your copy, open a terminal or command prompt and paste in your repo link. (This is found by pressing the green code button)(Refererence the example below):
   ```sh
   git clone https://github.com/your-username/repository-name.git
   ```
   This downloads the project to your computer.
5. Move into the project folder:
   ```sh
   cd folder-name
   ```
6. You can now make changes and save them in your own version of the project!

## HTML Elements Used in This Page
This simple webpage uses the following HTML elements:

- `<header>`: This is the top section of the page, which includes the title and menu.
- `<nav>`: A navigation bar with links to different parts of the page.
- `<main>`: The main content area where the important information is displayed.
- `<h1>`: A heading, which is usually the title of a section.
- `<p>`: A paragraph that holds text content.
- `<img>`: An image to visually enhance the page.
- `<footer>`: The bottom section that usually contains copyright information.

## How to Create This Webpage
Follow these steps to create a simple HTML page like this one:

1. Open a text editor (such as Notepad, VS Code, or Sublime Text).
2. Create a new file and name it `index.html`.
3. Start with the basic HTML structure:
   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>My Simple Page</title>
   </head>
   <body>
   </body>
   </html>
   ```
4. Inside `<body>`, add the following elements:
   - **Header with Navigation**
     ```html
     <header>
         <h1>My Simple Page</h1>
         <nav>
           <ul>
             <li><a href="#home">Home</a></li>
             <li><a href="#about">About</a></li>
             <li><a href="#contact">Contact</a></li>
           </ul>
         </nav>
     </header>
     ```
     The `<header>` element contains the page title and a `<nav>` section with links.
   
   - **Main Content**
     ```html
     <main>
         <h1>Welcome to My Website</h1>
         <p>This is a simple HTML page layout using essential elements.</p>
         <img src="https://via.placeholder.com/600x300" alt="Placeholder Image" width="600" height="300">
     </main>
     ```
     The `<main>` section includes a heading (`<h1>`), a paragraph (`<p>`), and an image (`<img>`).
   
   - **Footer**
     ```html
     <footer>
         &copy; 2025 My Simple Page. All rights reserved.
     </footer>
     ```
     The `<footer>` element is placed at the bottom of the page for additional information.

5. Save the file as `index.html`.
6. Open the file in a web browser (double-click the file or use the browser's "Open" feature).

## How to Commit and Push Changes to GitHub from VS Code
Once you have made changes to your project, follow these steps to save and upload them to GitHub:

1. **Open VS Code** and make sure your project folder is opened.
2. **Check your changes** by clicking on the **Source Control** icon in the left sidebar (or using `Ctrl+Shift+G`).
3. **Stage your changes** by clicking the `+` icon next to each modified file or clicking "Stage All".
4. **Write a commit message** (e.g., "Added index.html with basic structure").
5. Click the **Commit** button (or press `Ctrl+Enter`).
6. **Push your changes** to GitHub by clicking the **Sync Changes** or **Push** button in the Source Control tab.
7. Go to your GitHub repository and refresh the page to see your changes.

That's it! You've created a Nav and used the `<main>` element, committed your changes, and uploaded them to GitHub. Keep practicing, and soon you'll be building even more advanced websites!
