1. Install NodeJs
2. Install Git
    Add email: git config --global user.email "youtemail@gamil.com"
    All name: git config --global user.name "Your name"

    echo "# projectname" >> README.md //Create README file to your project
    git init //Initial git
    git add README.md //Add file to commit. Using "." to add all file at current folder
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/username/projectname.git
    ----Run: git remote rm origin if Faltal error: origin already exist
    git push -u origin main
3. Create project 
    Create folder projectname
    Open forlder by VSCode, 
    Open terminal and type: npx create-react-app . //"." is create react project in current folder 
4. Run project: npm start
5. Build project: npm run build

6. Add Bootstrap
    Copy "Bootstrap" folder to public project folder
    Link to Bootstrap file. Add to line to index.html
        <link rel="stylesheet" href="bootstrap/bootstrap.min.css" />
        <link rel="stylesheet" href="bootstrap/bootstrap-icons.css" /> 
7. Create folder "images, css" in "src" contain images and css of project
8. Create folder "components" contain Footer.js, Header.js.....
9. Create folder "pages" contain Home.js....some other pages
10. Import css to Header.js
11. Create folder "fonts/fontname" and add it to css
