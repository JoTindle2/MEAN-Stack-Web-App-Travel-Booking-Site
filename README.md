# Module 1: Intro, Setup, and Static HTML Site
## Create Website
This first module involves importing the static HTML mockup files into Node.js and Express, setting up the project by installing dependencies while working out of the **travlr** folder that can be downloaded.

1. Create and initialize a Node Express web application configured with the Handlebars (HBS) view engine.
    1. First, install the Express application template generator using the -g switch for global
       installation, which will make the generator available for all projects.
       `npm install -g express-generator`
    2. Generate an (empty) Express web application using the Handlebars view engine and a
       default Git configuration, if one does not already exist.
      `express --view=hbs --git –force`
3. Back in the Windows PowerShell command window, install the Node packages automatically
   included in **package.json** when the website was generated using the following command:
    `npm install`
4. Start the webserver using the instructions displayed earlier when Express generated the
   website:
    1. `SET DEBUG=travlr:*`
    2. `npm start`
5. The first time you launch the web server, a Windows Defender Firewall dialog will be displayed. You must click Allow access in order for the website to run correctly. Open a browser and navigate to the following URL:
    `http://localhost:3000`

## Install Static Web Files
5. This step requires the copying of the mock website content (travlr) that was downloaded and moving it into the public folder of the Express website.
    1. All of the .html files need to be moved to the public folder of **travlr**
6. Repeat the process to copy the image files into the images folder.
7. Copy the stylesheet from the CSS folder in the mockup site to the stylesheets folder on the Express website.
8. Launch the Express web server by switching to the command window and running the command `npm start` again.

At this point, you have a Node.js webserver running that is serving the static HTML site content to your web browser.
