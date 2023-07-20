# Notepad
This project is a simple Notepad application developed in C# using Windows Forms. The application provides basic text editing and file management functionalities. Here are the key features:
New File Creation: The application allows users to create a new file by clearing the existing text in the text editor. This is triggered by clicking on the 'New' option in the menu.
Open File: Users can open existing text files from their system. The application supports all file types but filters for text files by default.
Save File: The application allows users to save their work to a text file. The 'Save' dialog box defaults to the '.txt' extension but allows saving in any format.
Exit: Users can close the application by clicking on the 'Exit' option in the menu.
Text Editing: The application provides basic text editing features such as Cut, Copy, Paste, Delete, and Select All. These options are available in the menu.
The application uses the StreamReader and StreamWriter classes for file reading and writing operations. The OpenFileDialog and SaveFileDialog classes are used for opening and saving files. The text editing operations are performed using the methods provided by the RichTextBox control.
