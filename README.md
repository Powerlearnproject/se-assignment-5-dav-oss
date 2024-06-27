# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions And Answers:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   - Download Visual studio code windows executable file from https://code.visualstudio.com/
   - Run the downloaded file (VSCodeSetup-x64-1.x.x.exe)
   - Accept terms and conditions and continue with the installation process as guided by the installation wizard

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
*** Initial Configurations and Settings ***
Theme and Icons

Color Theme: Choose a color theme that suits your preference. Go to File > Preferences > Color Theme or press Ctrl+K Ctrl+T to select a theme.
File Icon Theme: Choose a file icon theme for better visual differentiation of file types. Go to File > Preferences > File Icon Theme.
Editor Settings

Font Size: Adjust the font size for better readability. Go to File > Preferences > Settings, search for Font Size, and set your preferred size.
Tab Size: Configure tab size and indentation. Search for Tab Size and set it according to your project requirements.
Word Wrap: Enable word wrap to avoid horizontal scrolling. Search for Word Wrap and set it to on.
Auto Save: Enable auto-save to automatically save your changes. Search for Auto Save and set it to afterDelay.
Code Formatting

Format On Save: Enable format on save to automatically format your code upon saving. Search for Format On Save and set it to true.
Default Formatter: Set a default code formatter. Search for Default Formatter and choose a formatter that matches your coding language (e.g., Prettier).
Integrated Terminal

Customize the integrated terminal to match your shell preferences. Go to File > Preferences > Settings, search for Terminal, and adjust settings like font size, shell path...

Extensions 

Python: ms-python.python
JavaScript/TypeScript: esbenp.prettier-vscode
HTML/CSS: ecmel.vscode-html-css
C/C++: ms-vscode.cpptools
Java: redhat.java
Linting and Formatting

ESLint: dbaeumer.vscode-eslint
Prettier: esbenp.prettier-vscode
Stylelint: stylelint.vscode-stylelint

GitLens: eamodio.gitlens
GitHub Pull Requests and Issues: github.vscode-pull-request-github

Path Intellisense: christian-kohler.path-intellisense
Bracket Pair Colorizer 2: coenraads.bracket-pair-colorizer-2
Live Server: ritwickdey.liveserver
TODO Highlight: wayou.vscode-todo-highlight

Docker: ms-azuretools.vscode-docker
Kubernetes: ms-kubernetes-tools.vscode-kubernetes-tools


SQL Server: microsoft.mssql
SQLite: alexcvzz.vscode-sqlite
3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
<img width="1681" alt="vscode UI" src="https://github.com/Powerlearnproject/se-assignment-5-dav-oss/assets/60092325/f02a8e06-4481-41f4-8da8-d33397e428fa">

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   - allows users to execute various commands and operations efficiently without navigating through menus or remembering keyboard shortcuts.
   - To access the Command Palette in VS Code, you can use one of the following methods:
         Keyboard Shortcut: Press Ctrl+Shift+P (Windows, Linux) or Cmd+Shift+P (MacOS)
     - Switching between Editor Tabs, Opening Files and Folders, Changing the Color Theme,...

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
- They allow users to customize their development environment to suit specific needs, making VS Code a versatile editor for various programming tasks.
- Users can find extensions under the marketplace
  Installing extensions
  - Navigate to the extension's page.
- Click on Install to install the extension directly to your VS Code.
- One can disable, update and enable extensions

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   - To open terminal while on vscode use Ctrl + ~ and then start typing commands at the shell
   - Seamless Integration
      Consistency
      Productivity
      Contextual Awareness
      Customization
      Debugging Integration

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?


## Opening Files:

To open an existing file, you can:
Double-click on the file in the File Explorer.
Use the Command Palette (Ctrl+P or Cmd+P on macOS) and start typing the name of the file. VS Code will suggest files matching your input.
Use the File > Open... menu option.

## Opening Folders:

To open a folder in VS Code, you can:
Use File > Open Folder... and select the folder from your file system.
Drag and drop a folder into the VS Code window.
Use the Command Palette (Ctrl+P or Cmd+P on macOS), type > Open Folder and select the folder.
Managing Files and Folders

## Renaming and Deleting:

Renaming: Right-click on a file or folder in the File Explorer and select "Rename", or press F2 with the item selected.
Deleting: Right-click on a file or folder in the File Explorer and select "Delete", or press Delete key with the item selected.

## Moving and Copying:

Moving: You can move files and folders within the File Explorer by dragging them to a new location.
Copying: Hold down Ctrl (or Cmd on macOS) while dragging to copy files and folders within the File Explorer.
Navigating Between Files and Directories

## File Navigation:

Use tabs to keep multiple files open simultaneously. Click on a tab to switch between open files.
Use Ctrl+Tab (or Cmd+Tab on macOS) to cycle through recently opened files.

## Directory Navigation:

Use the File Explorer sidebar to navigate between folders and files within your project.
Use the breadcrumbs at the top of the editor to quickly navigate up through parent directories.

## Search and Navigation Commands:

Use the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS) for quick access to various navigation commands, such as opening files, switching between files, etc.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
## Accessing Settings:
- Open VS Code.
- Access the Settings interface via:
- Menu Bar: Click on File > Preferences > Settings.
- Command Palette: Use Ctrl+Shift+P (or Cmd+Shift+P on macOS) and type Preferences: Open Settings.

## Changing the Theme:

- In the Settings interface, you can search for "theme".
- Click on the "Color Theme" dropdown menu to select from available themes.
- To install new themes, click on "Install Additional Color Themes" at the bottom.

## Adjusting Font Size:

- Search for "font size" in the Settings search bar.
- Adjust the "Editor: Font Size" setting.

## Customizing Keybindings:

- Search for "keybindings" in the Settings search bar.
- Click on "Keyboard Shortcuts" to view and customize keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
## Setup and Debugging
- Open Your Project:
    Open the folder containing your project in VS Code.
- Create a Launch Configuration:
    VS Code uses launch configurations (stored in .vscode/launch.json) to specify how to start your program for debugging.
    Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS).
    Type and select "Debug: Open launch.json".
    Choose the environment and configuration type suitable for your project (e.g., Node.js, Python, etc.).
- Set Breakpoints:
    Navigate to the file where you want to set breakpoints.
    Click in the gutter area next to the line number where you want to set a breakpoint. A red dot indicates the breakpoint.
- Start Debugging:
   Press F5 or click on the green play button in the Debug sidebar to start debugging.
   If prompted to select a debugging configuration, choose the appropriate one from the dropdown.
- Debugging Session:
   Once debugging starts, the program will run until it hits a breakpoint.
   Use the Debug sidebar to control the execution of your program (pause, resume, step into, step over, step out, restart).


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
## Initializing a Repository
- Open VS Code: Launch Visual Studio Code.
- Open or Create a Project: Navigate to your project directory or create a new one. You can open a folder by selecting File -> Open Folder... in VS Code.

## Initialize Git Repository:
- Once your project is open in VS Code, open the integrated terminal by selecting View -> Terminal or by pressing Ctrl+` (backtick).
- In the terminal, navigate to your project directory if you're not already there.
- Initialize a Git repository by running the command:
     git init
  
## Stage Changes:
- After making changes to your files (e.g., creating new files, modifying existing ones), you need to stage these changes to be committed.
- Stage changes using:
      git add .
This stages all changes. Replace . with specific file names to stage only those files.

## Commit Changes:
- Commit the staged changes with a descriptive message:
      git commit -m "Initial Commit"
Replace "Initial Commit" with a brief but descriptive message summarizing the changes made in this commit.

## Pushing Changes to GitHub
## Create a Repository on GitHub:
- Go to GitHub and create a new repository if you haven't already.
- 
## Link Your Local Repository to GitHub:
- Add the GitHub repository as a remote. You can copy the HTTPS or SSH URL from GitHub.
   git remote add origin <remote_repository_URL>
Replace <remote_repository_URL> with the URL you copied from GitHub.

## Push Commits to GitHub:
- Push your committed changes to the GitHub repository:
    git push -u origin master
- This command pushes your local master branch to the origin remote repository on GitHub.
- If you're working with a branch other than master, replace master with your branch name.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

