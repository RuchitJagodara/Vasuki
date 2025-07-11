# Vasuki
The name of this programming language comes from Hindu mythology, where Vasuki is the name of a serpent king who is often depicted as a powerful and wise figure. The programming language is named after him to symbolize strength, flexibility, or the ability to handle complex tasks. 
A compiler for a custom language made by me and my friends.

# Updates

You can try out our new Vasuki extension which is live on VS code! Just search "Vasuki extension" in the extension window and it will appear.

# Note

After internal discussions, we've decided to keep the full source code private until the official language launch. However, we are excited to share that the second milestone of our project is now available for you to try. This is a working version, and we welcome your feedback. We look forward to eventually open-sourcing the entire project. 

And sorry for the lack of documentation on the same, the documentation on how to download and use the language will be published in August, 2025.

# Language Documentation 
[LINK](https://pranjal15195gaur.github.io/Vasuki/)

# Presenetation Link

[LINK](https://www.canva.com/design/DAGioldU_lE/pAPgbXVjm6OvF0VJSiTFaw/edit?utm_content=DAGioldU_lE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

# Folder structure

**compiler** : This folder contains the main code of the Vasuki compiler.

**Vasuki_docs**: This folder contains the code of the documentation website.

**Vasuki_extension**: This folder contains the code of the Vasuki extension which is currently live on VS Code!

**Tests**: This folder contains all the test cases for the Vasuki compiler. NOTE: currently we are migrating from this naive method of testing to something similar to what LISP does, like writing tests in the same format as we write the code and providing details about tests in the Vasuki code itself, so we are planning to build a robust test system which can identify all the paths of the code which are not being covered and until everything is covered the user won't be able to merge its PR.

**repl.py**: This file contains the code for the repl implementation.
