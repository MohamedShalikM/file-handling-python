File Handling System - Python Console App
  A comprehensive Python console application demonstrating complete file I/O operations with an interactive menu-driven interface.
  
Features:
  Complete File Operations: Write, read, append, display line-by-line, delete, and existence checking
  Interactive Menu: User-friendly numbered menu for all operations
  Error Handling: Robust exception handling for all file operations
  Real-time Feedback: Clear success/error messages for every action
  Persistent File: All operations work on a single sample.txt file

Tech Stack:
  Python 3.13 | os module | Exception Handling | Console I/O

Functionality:
  Write Mode: Creates or overwrites sample.txt with new content
  Read Mode: Displays complete file content
  Append Mode: Adds new content with automatic newline
  Line Display: Shows file content line-by-line (clean formatting)
  Delete: Safely removes the file with existence check
  File Check: Verifies if sample.txt exists

Quick Demo:
  ========= FILE HANDLING MENU =========
  1. Write to File (Create/Overwrite)  
  2. Read File                         
  3. Append to File                     
  4. Display File Line by Line          
  5. Delete File                        
  6. Check if File Exists               
  7. Exit                              
  ======================================

 Sample Usage:
  Enter your choice (1-7): 1
  Enter text to write into the file:
  Hello, this is my first file content!
  Data successfully written to sample.txt

Learning Outcomes:
  File I/O modes ('w', 'r', 'a')
  Exception handling (FileNotFoundError, ValueError)
  os.path.exists() for file checking
  strip() for clean line display
  Menu-driven console applications

Built for learning Python file operations
