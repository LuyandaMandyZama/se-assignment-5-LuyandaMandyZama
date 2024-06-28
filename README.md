[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15327595&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Prerequisites that might be needed is reliable internet connection and a windows operating system
   STEPS:
   1.Open your preferred web browser and navigate to https://code.visualstudio.com
   2.On the official website homepage,click on the download button and select 'download for windows' and installation will begin
   3.Once the download is complete,open the downloaded file and run the installer,choose where to install the file and accept prompts and license agreements and install
   4.When installation is complete,launch Visual Studio Code

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   Enabling auto save to save files automatically and prevent any loss of any work
   Installing debugger for chrome for debugging in chrome and GitHub copilot
   Installing extensions such as live server for live previews of HTML,CSS,JavaScript and development of a local server,CodeRunner to run code without any problems and language support extensions such as python,c/c++,java,javascript and prettier for code formatting.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   VSCode user interface contains many main components such as the Activity Bar which let's users switch between views and provides quick access to often used tools, the Side Bar displays information and tools related to a file such as extensions debugging tools,source control,file explorer.The Editor Group is the main workspace where you can write and edit code,it allows for the opening and editing of multiple files at the same time.The Status bar which can be found at the bottom of the window displays information such as information about a file,error messages,extension-specific information,line and column numbers and indicates the programming language of the current file and a MENU Bar which provides access to the different menus that contain commands and features.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette is a feature on Visual Studio Code that allows quick access and execution of commands and features without having to navigate through menus and allows for you to work more efficiently.It can be accessed using the shortcut 'CTRL+Shift+P' OR go on view>command palette on the menu bar.Common tasks include quickly accessing settings,running and debugging code, opening a new terminal or a new file or folder,toggling of sidebar,creating and closing files,opening a new window and being able to change the mode of language of the editor.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions play an essential role in enhancing functionality in VSCode by allowing users to add new features and customize their development environment making it more powerful and versatile.Extensions add support for new programming languages and they integrate different tools and services.Extensions provide shortcuts and simplify tasks thereby improving productivity.Users can install extensions via the command palette by pressing CTRL+SHIFT+P and typing out 'install extensions', another option would be via the official visual studio code website whereby on the homepage you select extensions and search for the extension you wish to download or the extensions marketplace in Visual studio code which can be accessed by clicking on the extensions icon on the side bar and install from there.Users can manage extensions by enabling and disabling extensions.They can also uninstall extensions that are no longer needed,update to latest versions and configure extensions to tailor for specific workflow.These help users easily manage extensions to enchance their experience.
   Debugger for Chrome,Live Server,Prettier,GitHub Pull requests and ESLint are some examples of essential extensions needed for web development.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

    Open the Command Palette(CTRL+Shift+P) and type ' terminal ' and select 'Terminal:Create new terminal' and a new terminal will open or press CTRL+Shift+` and a new terminal will open.To use the integrated terminal once it has been opened type in the commands and press enter to execute the commands.The terminal can be used for running commands,compiling code and debugging applications.Advantages of using the integrated terminal compared to an external terminal is that it allows easy access within Visual Studio Code and there will be no need to jump from app to app,it makes navigation between files,folders and projects easier and command execution is more efficient.Additionally,it allows for seamless debugging and better integration allowing for features like:Automatic syntax highlighting,git integration and debugging tools.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   On the Menu bar(on top of the window) click on file>open new file or use the command palette and type 'file' and click 'new file' or 'new folder' to open a new file or folder.Keyboard shortcut ' CTRL+O ' also opens up a new file or folder.Drag and drop files and folders to move them,to rename a file or folder press the f2 button or right click and select rename.To delete a file or folder press the delete button or right click on the file/folder and select delete.To open a file press ' CTRL+P ' and type in the file name to open it, for a folder press ' CTRL+Shift+E ' and type in the folder name to open it.To switch between open files use keyboard shortcut CTRL+Tab and also browse and navigate through files and directories in the explorer sidebar.CTRL+P can be used to quickly switch between files.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   On the activity bar there is a gear icon and click on it to open the settings or the keyboard shortcut 'CTRL+' ,alternatively you can use the command palette type and select 'Preferences:Open SETTINGS'.VScode stores it's setting value in a 'settings.json' file,users can edit and review files by opening it in the editor.
   To change the theme use the keyboard shortcut ' CTRL+K CTRL+T ' to switch between themes efficiently 
   To change the font size,to enlarge press' CTRL & the plus icon(+) ' and to decrease press 'CTRL & the minus icon(-) ' you can also search for these setting preferences on the command palette.TO change keybindings open the command palette,type and select 'Preferences:Open Keyboard Shortcuts,click on the keybinding you want to change,press the new key combination you would like to use and click enter to save the changes.To return to default right-click on the keybinding and select reset keybinding.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   1.Open VSCode,open a folder and create a new file
   2.Write code and save the file
   3.Click on 'Run and Debug' on the activity bar or press ' CTRL+Shift+D ' or press on the F5 button 
   4.Open or create a launch.json file
   5.Adjust the program path to match the file and save the launch.json file
   6.Run the debugger by pressing the F5 key or the green button at the top bar of the run and debug view and start debugging
 
 Key debugging features include:
 Setting up breakpoints to pause and inspect code
 Controlling the execution flow of code(Step controls)
 Inspecting variable values,objects and arrays in the 'Variables' panel
 Viewing the call stack panel to understand the state of the program and see the sequence of function cells
 Using the debug console to execute expressions and commands to evaluate code and to interact with the program as it is debugging

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    1.Install Git
    2.Open VSCode,open a project folder and open a new terminal
    3.To create a new git branch run the ' git branch < insert branch name> ' command
    4.In the terminal panel run the command ' git init ' to initialize a new repository
    5.To add files to the initial commit use ' git add . ' to add all files or ' git add <insert file name> ' to add a specific file
    6.Use the ' git commit ' command to commit changes, ' git commit -m "insert a brief message of your changes"
    7.To verify that the repository has been initialized run ' git status '
    8.If the local repository is not linked to the user's github repository run the ' git remote add origin <"insert repository url>  command
    9.Run ' git push origin main/master ' to push changes to GitHub


    REFERENCES:
    docs.github.com
    blog.hubspot.com
    stackoverflow.com
    github.com
    code.visualstudio.com
    microsoft.github.io


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

