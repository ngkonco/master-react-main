# master-react-main
The following process will be used to install admin dashboard using package manager.
1. Install Node.js : Please install latest version of Node.js from https://nodejs.org
2. Extract main template : Extract the admin template site to your suitable directory or folder.
3. Access Command Prompt : Open node.js command prompt.
    Note:- The process mentioned below can also be excuted with system command prompt.
4. In CMD, Navigate to the location where main folder is extracted.
5. Navigate to the root folder of project where package.json file exist.
6. Install node dependencies : Run npm install.
7. To run npm run dev.
    Note:- when you run above command it will run project in browser automatically.
    Note:- It will enable auto refresh function everytime you save a file.
8. Run command npm run build to build for production.

File Sturcture

The arrangement below describes our file structure.

Vristo
    public
        assets
            images
        locales
src
    assets
        css
    components
    pages
    router
    store
    App.tsx - custom app setting configuration file
    i18n.tsx
    tailwind.css
    main.tsx - reactjs entry point file
    theme.config.tsx
index.html
package.json
postcss.config.cjs
tailwind.config.cjs
tsconfig.json
vite.config.ts
.editorconfig
.gitignore
.prettierrc

Code Structure

This section will give you a brief description of our code.

1. Header Section : This is the default navbar section. It contains :

a. Sidebar Toggle button.
b. Quick access button for calendar.
c. Quick access button for todolist.
d. Quick access button for chat.
e. Search Bar
f. Theme toggle button.
g. Language Dropdown
h. Message Dropdown
i. Notification Dropdown
j. User Profile with Dropdown
k. Horizontal Menu

