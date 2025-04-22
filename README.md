# Aim:
  To display the word "Hello World" in message box through Uipath Studio

# Date:
   3/3/2025

# Software Requirements:
    UiPath Studio Community or Enterprise Edition
    NET Framework (automatically handled by UiPath)

# Project Structure:
```
Main.xaml: The main workflow file containing a sequence that shows the message box.
project.json: The configuration file that defines dependencies, runtime version, etc.
README.md:  Detailed explanation of the project, its purpose, usage, and structure.
```

# Procedure:
```
 Step 1: Open UiPath Studio
    Launch UiPath Studio from your desktop or Start menu.
    Wait for the home screen to load.

 Step 2: Create a New Project
   On the home screen, click on "Process".
   Fill in the details:
       Name: HelloWorld
       Location: Choose a folder where you want to save the project.
       Description (optional): Simple Hello World message box using UiPath
   Click Create.

 Step 3: Add a Sequence to Main.xaml
  UiPath will automatically open the Main.xaml workflow.
  If it doesn't show a sequence already:
     Go to the Activities panel (on the left).
     Search for "Sequence".
  Drag and drop the Sequence into the empty Main.xaml canvas.

 Step 4: Add a Message Box Activity
  In the Activities panel, search for: Message Box.
  Drag and drop the Message Box activity inside the Sequence.

 Step 5: Configure the Message Box
   Click on the Message Box activity.
   In the Properties panel (usually on the right side), find the field labeled Text.

 Step 6: Save the workflow and run the workflow.

 
 ```

# Output:
   ![image](https://github.com/user-attachments/assets/b5943d02-d2db-45ad-91de-41641eb47b72)

# Result:
  You will see the word "Hello World" in the message box as a result of output. 





