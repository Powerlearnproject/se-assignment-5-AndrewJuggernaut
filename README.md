[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285871&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   Prerequisites:
   a. Esure that your widows 11 sysytem meeets the minimum requirements
   b. A stable internet connection
   To download the VS Code, 
     a. Visit the official Visual Studio Code website at code.visualstudio.com.
     b. Click on th e"Download for Windows" button and download the suitable one.
     c. Once download completes, open the downloaded installer file adn follow the instructions on the installation wizard;
          i. Accep the license agreement.
          ii. Choose the destination folder for installation or use the default.
          iii. Click Instal to begin the installation process.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
     Once installed, launch VS Code from your desktop. VS Code is better integrated with good extensions. install the extensions that suit your programming needs; 
      - Click on the Extensions view icon on the sidebar or press "Ctrl+Shift+X"
      - Search for the Extensions like Python, JavaScript, Gitlens and click Install and let them install.
    You also need to configure your VS Code to your own preferences by;
      - Click on the 'settings' icon on the sidebar or press "Ctrl+,"
      Modify settings to your liking.
    Integrate VS Code with versio control by installing Git or any other version control systems, in this case, install Git on your system if not installed. 
    Configure VS Code to use by integrating them through open a repository and using commands to link

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   Main Components of VS Code user interface.
    1. Title bar; Located at the top of the window displaying name of current file and providing options to minimize or close application.
    2. Activity Bar; It's located on the far left and contains icons for different views and functionalities like Explore allowing you to navigate through folders and files, Search button providing the tools for searching within files and folders, Source Control which integrates wit version control sysytems like Git, Run and Debug which manages the debugging of sessions and eecutiopon of tasks and lastly, Extensions which enables the user to install and manage the VS Code extensions.
    3. Side Bar; Its directly adjacent to the Activity Bar and it typically shows additional navigation and information panels based on the active view
    4. Editor Group; This is where you write and edit code. It includes Tbs where each represents an open file, Code Editor which supports code editing features depending on the language and extension used and the Status Bar which displays infromation about the current file and various actions to use like line ending settings located at the bottom.
    5. Integrated Terminal; You can access it via the shortcut 'Ctrl+'' and allows you to run command line tasks without leaving VS Code making it convenient for using other version command controls.
    6. Status Bar; Located at the bottom of the window, this interface provides information of the current state of VS Code language mode(displays the programming language used), Git Branch(showing current branh and Git status if the project is under version control) and Indicators.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   The Command Palette in VS Code sserves as a versatile and efficient tool for accessing and executing commands quickly making the flexibility of the user better and enhancing user-friendliness of the editor without strain.
   The Command Palette can be accessed by pressing the 'Ctrl+Shift+P' for Windows sytem or click on the 'View' the 'Command Palette' from the menu bar. Examples of tasks that can be performed;
      - File and Work management; ope a file, folder or workspace, save current files and open files
      - Editing and navigating in the ctive file
   

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
    The role of extension in VS Code is to significanly enhance the capabilities of VS Code beyond its core features enabling diverse development requiremens and enhances prouctivity, collaboration and customization options fro developers worldwide.
    Examples of essential extensions for web development include HTML,JavaScript, Version control like GitlLens and REST API Testing.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   Using the shortcut 'Ctrl+'', open a new terminal.
   Once the terminal is open you can perfom commands like, 
     - Navigting directories using the command 'cd' to change directories or 'cd foldername 
     - Run commands supported by your OS and istalled tools like 'git pull' to fetch changes from a repository
     - Manage multiple terminals by running simultaneous terminals where you can right-click on the terminsl tsb snd choose options like 'split terminal' to split for multitasking
     - Customise terminals by clicking the dropdown arrow in the terminal header 
     - Closing the terminal by clicking the X button to close or b using 'Ctrl+C'

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
      - To create new file, click the Explorer icon on the Activity Bar or press 'Ctrl+Shift+E'. Right-click on the folder where you want to create the file and select 'New File' om the menu, enter the desired name and press Enter to create.
      - To create new foler, right-click on the folder where you want to create the new folder, select 'New folder', enter folder name and press Enter to create.
      - To open anexisting file, navigate to the file in the Explorer view, double-click on the file name to open it in the editor. You can also use 'Ctrl+P' to open the dialog and type the file name to find it fast and press Enter to open.
      - To open a folder, use the File Menu, or by dragging and dropping the folder into the VS Code window. Once open you can view and navigate through files and subfolders.
      - T copy files and folders, hold 'Ctrl+'' while dragging and dropping. 
      - To delete folders and files, right-click on the file name or folder and select 'Delete' then press Enter toconfirm.
      - To rename files and folders, right-click on the file or folder name and slect 'Rename', enter new name then press Enter to confirm.
      - Use the search view or 'Ctrl+Shift+F' to search for files by name or content within the foler or workspace. 
      - Use 'Ctrl+Shift+E' to browse through files or the Activity bar
      - Use 'Ctrl+Tab' to switch between recently opened file
      -  Use 'Alt+Left Arrow' and 'Alt+Right Arrow' to navigate backward an forward through navigation history history within files.
      - To navigate through directories, 'Ctrl+Shift+F' to search within files eithin the current directory, use 'Ctrl+K Ctrl+0' to open keyboard shortcut editor.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
      - Settings are fund on the Settings icon on the sidebar or by clicking 'Ctrl+,".  
      To change the theme, click 'Ctrl+,', type 'color theme' in the search bar, and select your preferred theme.
       - To change font size, open settings by clicking 'Ctrl+,', type 'font size' in the search bar, look for the 'Editor: Font Size' and adust your font sie as preferred.
       To chnage the keybindings, click 'Ctrl+K Ctrl+S' to open the shortcuts editor, you can search for specific commands or keybindings using the search box n the editor. Find the command you want to modify, find the pencil icon that appears next to the command or right-click and select 'Change keybindig', press the key combinaion you wish to assign, resolve if there are any conflicting existing keybindings and change.

 9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   Steps to Set up and start debugging a progra in VS Code.
    1. Installed the required extensions
    2.Open your project in VS Code 

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    1. Install Git  if not already installed
    2. Set up a GitHub Account at github.com if you haven't already.
    3. Install VS Code, after downloading from code.visualstudio.com
    To initialize a Git Repository
     a. Open VS Code and navigate to the folder where you want to initialize the Git Repoitory
     b. Initialize Git; Open the integrated terminal in Vs Code, 'Ctrl+'' use the commands 'git init' to initialize the Git in the current directory. Create and modify files in your project folder.
   To make commits
     a. Stage changes 
      use 'git status' to see changes
      Stage files for commit using 'git add' :
            'git add filename>   #stage a specific file
            'git add.            #stage all files
     b. Commit changes 
      Commit staged changes with a commit message 
             'git commit -m "Commit message"
   Pushing changes to GitHubg
     a. Go to GitHub and create a new repository and follow the instructions without initializing it with a README file if you've already done that.
     b. Link Local repository to gitHub Repository;
       Add the GitHub repository as a remote
           git remote add origin <repository_URL>
           Replace repositroy_URL with your GitHub repository URLfound in the GitHub repository page.
     c. Push changes to GitHub by using the comands
         git push -u origin master
        Enables the changes to be effected in your GitHub repository.



