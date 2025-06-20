🌳 Syntax Tree Visualizer
A C++ GUI application that visualizes syntax (parse) trees, built using the wxWidgets framework. Ideal for students, teachers, and developers working with compilers, data structures, or visual parsing tools.

🔧 Features
Visual representation of syntax/parse trees

Interactive GUI: zoom, pan, and explore tree nodes

Modular design using C++ classes for Nodes, ParseTree logic, and GUI panels

Clean integration with wxWidgets for cross-platform compatibility

📁 Project Structure
plaintext
Copy
Edit
dsmajortaskspr25/
├── src/
│   ├── main.cpp              # Entry point
│   ├── MyFrame.*             # Main window logic
│   ├── Node.*                # Tree node structure
│   ├── ParseTree.*           # Syntax tree creation
│   ├── TreePanel.*           # GUI drawing logic
│   └── build/                # Auto-generated build files
├── .vscode/ and .fleet/      # IDE configuration
🛠 Getting Started
✅ Prerequisites
C++17 compatible compiler

wxWidgets (recommended: 3.1 or higher)

CMake 3.10 or newer

🔨 Build Instructions
bash
Copy
Edit
# Clone the repo
git clone https://github.com/your-username/syntax-tree-visualizer.git
cd syntax-tree-visualizer/dsmajortaskspr25/src

# Create build directory
mkdir -p build && cd build

# Run CMake and build
cmake ..
make

# Run the program
./SyntaxTreeVisualizer  # Adjust name if different
📚 Use Case
This project was built for a Data Structures major task and helps in understanding how syntax trees are constructed and rendered. Useful for:

CS education

Compiler design demos

Tree algorithm visualization

🙋‍♂️ Authors
Developed by:

Bassil Al Safadi

📄 License
This project is open-source and distributed for educational purposes.
If you'd like to use it commercially or modify extensively, please contact the author.

