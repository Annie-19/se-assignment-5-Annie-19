[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281758&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

1.Visit the Official VS Code Page:
-Go to the VS Code download page.
2.Choose the Correct Version:
-Download the version specific to your OS (Windows).
-You can choose between the User Installer (recommended) or the System Installer.
3.Run the Installer:
-Once the download is complete, open the downloaded file (e.g., VSCodeUserSetup-{version}.exe).
-Accept the license terms and conditions.
4.Installation Location:
-By default, VS Code is installed under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code.
-Alternatively, you can download the Zip archive, extract it, and run VS Code from there

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

1.Python Environments:
-If you’re working with Python, create a local environment using virtual environments or Anaconda. These allow you to manage packages without affecting other environments.
-Use the Python: Create Environment command in VS Code to set up virtual or conda environments1.
2.Configure Settings:
-Customize VS Code settings to enhance your workflow. Adjust preferences related to themes, fonts, indentation, and more.
-Explore extensions in the VS Code Marketplace to add features like Git integration, debugging tools, and language support.
3.Environment Variables:
-In your project’s launch.json, configure environment variables using the "env" field. Specify variables like "NODE_ENV": "development"2.
4.Extensions and Themes:
-Install extensions relevant to your programming language (e.g., Python, JavaScript, Java).
-Choose a theme that suits your preference (e.g., light, dark, or custom)

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

1. ACTIVITY BAR
-It is located on the far left-hand side.
-It lets you switch between views and gives you additional context-specific indicatiors, like the number of outgoing changes when git is enabled.
2. SIDE BAR
-It contains different views like the Explore to assist you while working on your project.
3.EDITOR GROUP
-It is the main area to edit your files.
-You can open as many editors as you like side by side vertically and horizontally.
4.STATUS BAR.
-Information about the opened project and files you edit.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

COMMAND PALETTE
-It is where all commands are found.
-You can access it by clicking Ctrl+Shift+P
-You can run editor commands, open files, search for symbols and see the outline of a file.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

ROLE OF EXTENSIONS
-They let you add languages, tools and debuggers to your installation to support your development work flow.
HOW TO INSTALL, FIND AND MANAGE EXTENSIONS
-Click on the extensions icon in the active bar to bring up extensions view or Ctrl+Shift+X.
-You can search in the search box at the top of the extension view the extensions.
-Vs code makes it easier to manage extensions. You can install, disable, update and uninstall extensions through the extension view, the command palette or command-line switches.
EXTENSIONS FOR WEB DEVELOPMENT
1.Prettier
2.Javascript booster
3.ESLint
4.GitLens
5.Live Server
6.CSS Peek
7.Intellisense for CSS Class Names in HTML
8.JavaScript(ES6) Code Snippets
9.Visual Studio Intellicode
10.VSCode Icons

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

HOW TO OPEN AND USE INTERGRATED TERMINAL
-From the menu,use the terminal menu commands
-From the command palette use the view;toggle terminal command
-You can use the open in intergrated terminal context menu command to open a new terminal from a folder in the explorer.
ADVANTAGES OF USING INTEGRATED TERMINAL COMPARED TO AN EXTERNAL TERMINAL
-It provides intergration with the editor to support features like links and error detection.
-It can run commands like git

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

HOW TO CREATE, OPEN AND MANAGE FILES AND FOLDERS IN VS CODE
-You can use the new file and the new folder buttons at the top of the explorer view.
-You can also right click in the explorer view to create files and folders.
-You can add, name and remane files and folders directly from the explorer view.
HOW TO NAVIGATE
-You can press the Ctrl+Tab to view a list of files open in an editor group, release the Ctrl to view the selected command.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

-To navigate settings on the vs code, open the settings editor from the command pallete(Ctrl+Shift+P)
HOW TO CHANGE THEME
1.Select the File> Preferences> Colour theme menu item or use command (Ctrl+K Ctrl+T) to display the colour theme picker.
2.Use the Up and Down keys to navigate through the list and preview the clours of the theme.
3.Select the theme you want and press enter.
FONT SIZE
1.Click on the settings at the bottom left.
2.Click font size
3.Type in the font size you want.
KEYBINDINGS
-On the menu bar, choose Tools> Options, expand environment, and then choose keyboard.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

-Press F5 or select the green start debugging button in the debug toolbar
Steps:
*Reproduce the bug
*Locate the bug
*Identify the root cause
*Fix the bug
*Test the fix
*Document the process
Debugging features:
-Built-in debugger
-Breakpoints
-Watch variables
-Conditional breakpoints
-

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

PROCESS
1.Initialize a Repository:
-To start a new project with Git, you have two options: git init or git clone.
-If you’re starting a new project locally, use git init. It transforms the current directory into a Git repository by creating a hidden .git directory that stores Git-related information.
-If the repository already exists on a remote (like GitHub), use git clone to fetch the existing repository to your local machine.
2.Making Commits:
-After initializing the repository, create or modify files in your project.
-Use git add to stage changes (select which files to include in the next commit).
-Then, commit your changes using git commit. Write a descriptive commit message to explain what you’ve done.
-Commits create a snapshot of your project’s state at that moment.
3.Pushing Changes to GitHub:
-First, create a remote repository on GitHub.
-Add the remote URL to your local repository using git remote add origin <URL>.
-Push your changes to the remote using git push -u origin main (replace main w

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

