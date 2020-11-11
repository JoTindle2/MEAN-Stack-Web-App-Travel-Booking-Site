# CS-465-Full-Stack-Development-I
## Module 1: Intro, Setup, and Static HTML Site
Step 1: Create a Website
  1) Open a Windows PowerShell command prompt and ensure you are in the top folder of your travlr local Git repository directory.
      cd ~/travlr
  2) Create and initialize a Node Express web application configured with the Handlebars (HBS) view engine.
    a) First, install the Express application template generator using the -g switch for global installation, which will make the generator available for all projects.
      npm install -g express-generator
    b) Generate an (empty) Express web application using the Handlebars view engine and a default Git configuration, if one does not already exist.
      express --view=hbs --git –-force
  3) Launch the Visual Studio (VS) Code editor and open the newly created Express website.
      code .
  4) Edit the “.gitignore” file and add instructions to ignore the VS Code working files when committing your source code to Git by copying the following:
      .vscode/*
      !.vscode/settings.json
      !.vscode/tasks.json
      !.vscode/launch.json
      !.vscode/extensions.json
      *.code-workspace
   5) Back in the Windows PowerShell command window, install the Node packages automatically included in packages.json when the website was generated using the following 
      command:
      npm install
   6) Start the webserver using the instructions displayed earlier when Express generated the website:
      a) SET DEBUG=travlr:*
      b) npm start
      Open a browser and navigate to the following URL: http://localhost:3000
Step 2: Install Static Web Files
   7) Copy the mock website content you downloaded from the course files into the public folder of the Express website.
      a) Open a second Windows File Explorer window and arrange it so you can see both windows.
      b) Select the .html files and drag them to the public folder while holding the right mouse button. Drop the files (by letting go of the right mouse button) over the public 
         folder and choose Copy files.
   8) Repeat the process to copy the image files into the images folder.
   9) Copy the stylesheet from the CSS folder in the mockup site to the stylesheets folder on the Express website.
   10) Launch the Express web server by switching to the command window and running the command npm start again.
   11) In VS Code, right-click on the stylesheets folder and choose Rename to change the name to “css” and then refresh the browser.
   
At this point, you have a Node.js webserver running that is serving the static HTML site content to your web browser. 
