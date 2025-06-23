# Course Planner
# What was the problem you were solving in the projects for this course?
The primary problem was to build a command-line application that helps academic advisors access and display course information, including course titles and prerequisites. This required reading data from a CSV file, storing it in an appropriate data structure, and implementing menu-driven functionality to retrieve and display course information efficiently.

# How did I approach the problem? 
I began by analyzing the requirements and identifying the best data structures to use. I chose to use a `map` to store course information because it allows for fast lookups by course number and automatically keeps keys in alphanumeric order, which is ideal for sorted output. I also used `vector` to store lists of prerequisites. Understanding the trade-offs in runtime and memory helped me select efficient and appropriate structures.

# How did I overcome any roadblocks you encountered?
One major challenge was ensuring the CSV file was read correctly at runtime, especially regarding file path issues in Visual Studio. I resolved this by learning how to correctly configure project file properties and by using robust file I/O checks in code. I also improved error handling for invalid user inputs, and I added in-line comments to make the code more maintainable.

# How has my work on this project expanded my approach to designing software and developing programs?
This project helped reinforce the importance of planning before coding. By working from pseudocode and designing the data structure in advance, I saved time during development and avoided major rewrites. I also became more mindful of how users interact with command-line programs, so I structured menus and feedback messages clearly.

# How has my work on this project evolved the way I write programs that are maintainable, readable, and adaptable?
I now write code with future readability in mind. I used clear function names, added in-line comments, and separated logic into functions to follow single-responsibility principles. This has made my code easier to debug and extend — for example, adding more menu options or loading additional course fields in the future would be straightforward.

