# Lexical-Analyzer-for-PLSL-Pascal-Like-Simple-Language-
This C++ project implements a lexical analyzer for a small programming language known as Pascal-Like Simple Language (PLSL). The lexical analyzer efficiently tokenizes input source code, identifying identifiers, keywords, strings, integers, floats, and comments. The implementation utilizes a state machine design to handle various lexical states, ensuring accurate and reliable tokenization.

# Key Features:
- Tokenization of PLSL language constructs, including keywords, operators, and literals.
- State machine logic for managing different lexical states such as identifiers, strings, integers, floats, and comments.
- Integration potential for use in larger language processing systems.

# Technologies:
C++, Map Data Structure, State Machine Design, Input Stream Handling

# How to Use:
1. Clone the repository to your local machine.
2. Include the provided `lex.h` header file in your project.
3. Utilize the `getNextToken` and `id_or_kw` functions for lexical analysis.
