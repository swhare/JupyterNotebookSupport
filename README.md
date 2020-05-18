# JupyterNotebookSupport

favicon.ico 
- Some Windows users (including me) run into a problem in which the Jupyter icon seemingly dissapears or goes blank.  This is the icon file.  
  - Windows 10 instructions: 
      1. Copy it to C:\Users\All Users\Anaconda3\Menu.
      2. Right-click the Jupyter Notebook icon in the start menu.
      3. Select More | Open File Location.  
      4. Windows explorer opens to the appropriate folder.  Locate the shortcut to Jupyter Notebook.  Right-click the shortcut.
      5. The shortcut properties window opens.  Click on Change Icon...  A warning message is displayed indicating the icon file cannot be found.  Click OK.
      6.  In the textbox labelled "Look for icons in this file:", type "C:\Users\All Users\Anaconda3\Menu\favicon.ico"
      7.  Problem solved!  Click OK repeatedly to back out and resume whatever it is you were doing before.
