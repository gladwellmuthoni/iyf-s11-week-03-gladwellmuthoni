Navigation Commands
-pwd (Print Working Directory): Displays the absolute path of the folder you are currently "inside." 

-ls (List): Lists all files and folders located inside your current directory. It shows you what is inside the "box" you are currently holding.

-cd (Change Directory): Allows you to switch your focus from your current folder to another. It is the primary tool for moving between "boxes."

-cd ..: It moves you one level back toward the root of the file system tree.

-cd ~: The "Home" button; instantly jumps you back to your starting user directory, regardless of how deep you are in the folder structure.

-cd ~/Documents: Navigates directly to the Documents branch. The ~ symbol is a universal shortcut for your user's home folder.

Directory Management
-mkdir (Make Directory): Creates a new folder (directory) within your current location.
 
 Task: Answer these questions using terminal commands only:
 1. How many html files are in your portfolio project? five(5)
 2. Which files contain the word "contact"?
   -about.html
   -contact.html
   -index.html
   -project.html
3. How many lines is your CSS file? 156 style.css
4. What were your last 10 terminal commands?
      - find . -name "*.html" | wc -l
      - grep -l "contact" *.html
      - wc -l style.css
      -  history | tail -10