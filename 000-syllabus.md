# C Programming — 100% Complete Syllabus

## Complete Beginner → Advanced → System Programming → Embedded → Professional C Roadmap

---

# Table of Contents

1. Introduction to C
2. History and Evolution of C
3. C Standards
4. C Programming Environment
5. C Program Structure
6. Compilation Process
7. C Tokens
8. Keywords
9. Identifiers
10. Comments
11. Variables
12. Constants
13. Literals
14. Data Types
15. Integer Types
16. Floating-Point Types
17. Character Types
18. Boolean Types
19. `void` Type
20. Type Qualifiers
21. Storage Classes
22. Scope
23. Lifetime and Storage Duration
24. Linkage
25. Operators
26. Operator Precedence
27. Expressions
28. Type Conversion
29. Type Casting
30. Input and Output
31. Conditional Statements
32. Loops
33. Jump Statements
34. Functions
35. Function Parameters
36. Function Return Values
37. Recursion
38. Arrays
39. Multidimensional Arrays
40. Strings
41. Character Arrays
42. Pointers
43. Pointer Arithmetic
44. Pointer Types
45. Pointer and Arrays
46. Pointer and Functions
47. Function Pointers
48. `const` and Pointers
49. `void *`
50. Null Pointers
51. Structures
52. Nested Structures
53. Self-Referential Structures
54. Unions
55. Enumerations
56. `typedef`
57. Bitwise Programming
58. Bit Fields
59. Dynamic Memory
60. Memory Management
61. Preprocessor
62. Macros
63. Header Files
64. Multi-File Programs
65. External/Internal Linkage
66. Static and Shared Libraries
67. Error Handling
68. Assertions
69. `errno`
70. File Handling
71. Text Files
72. Binary Files
73. Command-Line Arguments
74. Environment Variables
75. Variadic Functions
76. Standard C Library
77. Character Handling Library
78. String Library
79. Memory Library
80. Mathematics Library
81. Time and Date Library
82. Localization
83. Wide Characters
84. Complex Numbers
85. Floating-Point Environment
86. Non-Local Jumps
87. Signals
88. Standard Integer Types
89. Standard Definitions
90. Generic Programming
91. `_Generic`
92. `inline`
93. `restrict`
94. Alignment
95. `_Static_assert`
96. Atomics
97. Threads
98. Thread-Local Storage
99. C Memory Model
100. Object Representation
101. Object Lifetime
102. Effective Type
103. Strict Aliasing
104. Evaluation Order
105. Undefined Behavior
106. Implementation-Defined Behavior
107. Unspecified Behavior
108. Integer Overflow
109. Floating-Point Behavior
110. Endianness
111. Structure Padding
112. Memory Layout
113. Stack
114. Heap
115. Data Segment
116. BSS
117. Text Segment
118. Dynamic Linking
119. Compilation and Linking Internals
120. ABI
121. Object Files
122. Executable Formats
123. Debugging
124. Compiler Warnings
125. Sanitizers
126. Static Analysis
127. Testing
128. Unit Testing
129. Integration Testing
130. Fuzz Testing
131. Performance
132. Profiling
133. Optimization
134. CPU Cache
135. Data-Oriented Programming
136. Data Structures
137. Algorithms
138. Complexity Analysis
139. Searching
140. Sorting
141. Linked Lists
142. Stacks
143. Queues
144. Deques
145. Hash Tables
146. Trees
147. Heaps
148. Tries
149. Graphs
150. Disjoint Set
151. Recursion and Backtracking
152. Dynamic Programming
153. Greedy Algorithms
154. Parsing
155. Lexical Analysis
156. Finite State Machines
157. C API Design
158. Library Design
159. Opaque Data Types
160. Callbacks
161. Error and Resource Management
162. Secure C Programming
163. Common C Vulnerabilities
164. Defensive Programming
165. POSIX
166. Linux System Programming
167. File Descriptors
168. System Calls
169. Processes
170. Process Control
171. IPC
172. Pipes
173. Signals
174. Shared Memory
175. Memory Mapping
176. Threads and POSIX Threads
177. Mutexes
178. Condition Variables
179. Semaphores
180. Read-Write Locks
181. Concurrency Problems
182. Atomic Programming
183. Lock-Free Programming
184. Networking
185. Socket Programming
186. TCP Programming
187. UDP Programming
188. DNS
189. HTTP
190. TLS/HTTPS Concepts
191. Client-Server Programming
192. Embedded C
193. Microcontrollers
194. Hardware Registers
195. Memory-Mapped I/O
196. Interrupts
197. Timers
198. GPIO
199. UART
200. SPI
201. I2C
202. CAN
203. ADC
204. PWM
205. DMA
206. Watchdog
207. RTOS
208. Real-Time Programming
209. Cross Compilation
210. C and Assembly
211. Compiler Internals
212. Linker Internals
213. Build Systems
214. Make
215. CMake
216. Ninja
217. Package Management
218. Cross Platform C
219. Portability
220. Coding Standards
221. MISRA C
222. CERT C
223. Documentation
224. Git
225. CI/CD
226. C23
227. Advanced C Projects
228. System Programming Projects
229. Embedded Projects
230. Interview Preparation
231. Final C Mastery Checklist

---

# 1. Introduction to C

## 1.1 What is C?

- Definition of C
- General-purpose programming language
- Procedural programming language
- Structured programming
- Compiled language
- Statically typed language
- Low-level programming capabilities
- Systems programming language

## 1.2 Characteristics of C

- Fast execution
- Small runtime
- Direct memory access
- Pointer support
- Portability
- Hardware interaction
- Modular programming
- Manual memory management
- Deterministic resource management

## 1.3 Applications of C

- Operating systems
- Embedded systems
- Firmware
- Device drivers
- Compilers
- Interpreters
- Databases
- Networking
- System utilities
- Game engines
- Graphics libraries
- Scientific software
- High-performance applications
- Security software

---

# 2. History and Evolution of C

## 2.1 Origins

- BCPL
- B language
- Dennis Ritchie
- Bell Labs
- UNIX

## 2.2 K&R C

- The C Programming Language book
- Traditional C
- K&R function declarations

## 2.3 Standardization

- ANSI C
- ISO C
- Standardization process

---

# 3. C Standards

## 3.1 C89

- ANSI C
- Original standardized C

## 3.2 C90

- ISO standard
- Compatibility with C89

## 3.3 C95

- Library amendments
- Wide character improvements

## 3.4 C99

- `//` comments
- `inline`
- Variable-length arrays
- `long long`
- Designated initializers
- Compound literals
- Mixed declarations and code
- `stdint.h`
- `stdbool.h`

## 3.5 C11

- `_Generic`
- `_Static_assert`
- `_Atomic`
- `<stdatomic.h>`
- `<threads.h>`
- Thread-local storage
- Anonymous structures/unions
- Unicode-related additions

## 3.6 C17

- Defect corrections
- Clarifications
- Library updates

## 3.7 C23

- `nullptr`
- `true`
- `false`
- `constexpr`
- `typeof`
- `typeof_unqual`
- Binary integer constants
- Digit separators
- Attributes
- Improved enumerations
- Modern declarations
- New library functionality

---

# 4. C Programming Environment

## 4.1 Editors

- VS Code
- Vim
- Neovim
- Emacs
- Visual Studio
- CLion
- Xcode

## 4.2 Compilers

- GCC
- Clang
- MSVC
- ICC/ICX
- ARM compilers
- Embedded compiler toolchains

## 4.3 Terminal

- Windows Terminal
- PowerShell
- Linux shell
- macOS Terminal

---

# 5. C Program Structure

## 5.1 Basic Program

- `#include`
- `main()`
- Statements
- Blocks
- Braces
- Semicolon

## 5.2 Program Entry Point

- `main()`
- `argc`
- `argv`
- Return value

## 5.3 Basic Program Organization

- Header files
- Source files
- Functions
- Global declarations
- Local declarations

---

# 6. Compilation Process

## 6.1 Preprocessing

- Header inclusion
- Macro expansion
- Conditional compilation
- Comment removal
- Line control

## 6.2 Compilation

- Parsing
- Semantic analysis
- Type checking
- Optimization
- Code generation

## 6.3 Assembly

- Assembly generation
- Assembler
- Object code

## 6.4 Linking

- Symbol resolution
- Relocation
- Static linking
- Dynamic linking

## 6.5 Loading

- Executable loading
- Dynamic loader
- Process creation

---

# 7. C Tokens

## 7.1 Token Categories

- Keywords
- Identifiers
- Constants
- String literals
- Operators
- Punctuators

## 7.2 Tokenization

- Lexical analysis
- Preprocessing tokens
- Token boundaries

---

# 8. Keywords

## 8.1 Traditional Keywords

- `auto`
- `break`
- `case`
- `char`
- `const`
- `continue`
- `default`
- `do`
- `double`
- `else`
- `enum`
- `extern`
- `float`
- `for`
- `goto`
- `if`
- `inline`
- `int`
- `long`
- `register`
- `restrict`
- `return`
- `short`
- `signed`
- `sizeof`
- `static`
- `struct`
- `switch`
- `typedef`
- `union`
- `unsigned`
- `void`
- `volatile`
- `while`

## 8.2 Modern Keywords

- `_Alignas`
- `_Alignof`
- `_Atomic`
- `_Bool`
- `_Complex`
- `_Generic`
- `_Imaginary`
- `_Noreturn`
- `_Static_assert`
- `_Thread_local`

## 8.3 C23 Keywords

- `alignas`
- `alignof`
- `bool`
- `constexpr`
- `nullptr`
- `static_assert`
- `thread_local`
- `typeof`
- `typeof_unqual`

---

# 9. Identifiers

## 9.1 Identifier Rules

- Alphabetic characters
- Digits
- Underscore
- First-character rules
- Case sensitivity

## 9.2 Identifier Categories

- Variable names
- Function names
- Type names
- Structure names
- Enumeration names
- Labels

## 9.3 Reserved Identifiers

- Standard library names
- Underscore rules
- Implementation-reserved names

---

# 10. Comments

## 10.1 Single-Line Comments

```c
// comment
```

## 10.2 Multi-Line Comments

```c
/*
   comment
*/
```

## 10.3 Documentation Comments

- API documentation
- Doxygen
- Function documentation

---

# 11. Variables

## 11.1 Declaration

- Variable declaration
- Multiple declarations

## 11.2 Definition

- Object definition
- Function definition

## 11.3 Initialization

- Initialization at declaration
- Zero initialization
- Partial initialization
- Designated initialization

## 11.4 Assignment

- Assignment operator
- Compound assignment

---

# 12. Constants

## 12.1 Integer Constants

- Decimal
- Octal
- Hexadecimal
- Binary in modern C

## 12.2 Floating Constants

- Decimal notation
- Exponential notation
- Suffixes

## 12.3 Character Constants

- Normal characters
- Escape sequences
- Universal character names

## 12.4 String Literals

- String literal
- Adjacent string literals
- Escape sequences
- Wide string literals
- UTF string literals

---

# 13. Escape Sequences

## 13.1 Common Escape Sequences

- `\n`
- `\t`
- `\r`
- `\b`
- `\a`
- `\f`
- `\v`
- `\\`
- `\'`
- `\"`
- `\?`
- `\0`

## 13.2 Numeric Escapes

- Octal escape
- Hexadecimal escape

## 13.3 Universal Character Names

- `\u`
- `\U`

---

# 14. Data Types

## 14.1 Basic Types

- `char`
- `short`
- `int`
- `long`
- `long long`
- `float`
- `double`
- `long double`
- `_Bool`
- `void`

## 14.2 Derived Types

- Arrays
- Pointers
- Functions

## 14.3 User-Defined Types

- `struct`
- `union`
- `enum`
- `typedef`

---

# 15. Integer Types

## 15.1 Signed Types

- `signed char`
- `short`
- `int`
- `long`
- `long long`

## 15.2 Unsigned Types

- `unsigned char`
- `unsigned short`
- `unsigned int`
- `unsigned long`
- `unsigned long long`

## 15.3 Integer Properties

- Minimum range
- Maximum range
- Representation
- Width
- Promotion
- Conversion
- Overflow

---

# 16. Floating-Point Types

## 16.1 Types

- `float`
- `double`
- `long double`

## 16.2 Concepts

- Precision
- Range
- Rounding
- Accuracy
- NaN
- Infinity
- Signed zero
- Subnormal numbers
- Floating-point exceptions

## 16.3 `<float.h>`

- `FLT_MIN`
- `FLT_MAX`
- `DBL_MIN`
- `DBL_MAX`
- Precision macros
- Rounding macros

---

# 17. Character Types

## 17.1 `char`

- Character storage
- Character constants
- Signedness

## 17.2 `signed char`

- Signed byte-like integer

## 17.3 `unsigned char`

- Byte/object representation access

## 17.4 Wide Characters

- `wchar_t`
- `wint_t`

## 17.5 Unicode Character Types

- `char8_t`
- `char16_t`
- `char32_t`

---

# 18. Boolean Types

## 18.1 `_Bool`

- Boolean values
- Conversion to boolean

## 18.2 `<stdbool.h>`

- `bool`
- `true`
- `false`

## 18.3 C23 Boolean Syntax

- Modern `bool`
- Modern `true`
- Modern `false`

---

# 19. `void`

## 19.1 Void Return

```c
void function(void);
```

## 19.2 Void Parameter List

```c
int main(void);
```

## 19.3 Void Pointer

- `void *`
- Generic object pointer

---

# 20. Type Qualifiers

## 20.1 `const`

- Read-only access through qualified type
- Const variables
- Pointer to const
- Const pointer
- Const pointer to const

## 20.2 `volatile`

- Memory-mapped I/O
- Hardware registers
- Signal-related usage
- Limitations of `volatile`

## 20.3 `restrict`

- Aliasing contract
- Optimization
- Pointer-based APIs

## 20.4 `_Atomic`

- Atomic objects
- Atomic operations

---

# 21. Storage Classes

## 21.1 `auto`

- Automatic storage duration
- Block scope

## 21.2 `register`

- Register storage hint/history
- Address restrictions

## 21.3 `static`

- Static storage duration
- Local static
- Internal linkage

## 21.4 `extern`

- External linkage
- External declarations

## 21.5 `_Thread_local`

- Thread storage duration

---

# 22. Scope

## 22.1 Block Scope

- Local variables
- Nested blocks

## 22.2 Function Scope

- Labels

## 22.3 Function Prototype Scope

- Parameter names

## 22.4 File Scope

- Global declarations

---

# 23. Lifetime and Storage Duration

## 23.1 Automatic Storage Duration

- Local variables
- Function parameters

## 23.2 Static Storage Duration

- Global variables
- Static variables

## 23.3 Allocated Storage Duration

- `malloc`
- `calloc`
- `realloc`
- `free`

## 23.4 Thread Storage Duration

- `_Thread_local`

---

# 24. Linkage

## 24.1 No Linkage

- Local variables

## 24.2 Internal Linkage

- File-scope `static`

## 24.3 External Linkage

- Global functions
- External variables

---

# 25. Operators

## 25.1 Arithmetic

- `+`
- `-`
- `*`
- `/`
- `%`

## 25.2 Relational

- `<`
- `>`
- `<=`
- `>=`
- `==`
- `!=`

## 25.3 Logical

- `&&`
- `||`
- `!`

## 25.4 Assignment

- `=`
- `+=`
- `-=`
- `*=`
- `/=`
- `%=`
- `&=`
- `|=`
- `^=`
- `<<=`
- `>>=`

## 25.5 Increment/Decrement

- `++`
- `--`

## 25.6 Bitwise

- `&`
- `|`
- `^`
- `~`
- `<<`
- `>>`

## 25.7 Conditional

- `?:`

## 25.8 Other Operators

- `sizeof`
- `_Alignof`
- `&`
- `*`
- `.`
- `->`
- `[]`
- `()`
- `,`

---

# 26. Operator Precedence

## 26.1 Precedence Levels

- Postfix
- Unary
- Multiplicative
- Additive
- Shift
- Relational
- Equality
- Bitwise AND
- Bitwise XOR
- Bitwise OR
- Logical AND
- Logical OR
- Conditional
- Assignment
- Comma

## 26.2 Associativity

- Left-to-right
- Right-to-left

## 26.3 Parentheses

- Explicit grouping
- Readability
- Avoiding precedence mistakes

---

# 27. Expressions

## 27.1 Primary Expressions

- Identifiers
- Constants
- String literals
- Parenthesized expressions

## 27.2 Unary Expressions

- Address-of
- Dereference
- Unary plus
- Unary minus
- Logical NOT
- Bitwise NOT
- Increment/decrement
- `sizeof`
- `_Alignof`

## 27.3 Binary Expressions

- Arithmetic
- Relational
- Logical
- Bitwise
- Assignment

## 27.4 Conditional Expressions

- `condition ? x : y`

## 27.5 Comma Expressions

- Comma operator
- Evaluation sequencing

---

# 28. Type Conversion

## 28.1 Implicit Conversion

- Integer conversion
- Floating conversion
- Pointer conversion

## 28.2 Integer Promotions

- `char`
- `short`
- `_Bool`

## 28.3 Usual Arithmetic Conversions

- Signed/unsigned
- Integer/floating
- Rank

## 28.4 Pointer Conversions

- Object pointers
- `void *`
- Qualification conversion

---

# 29. Type Casting

## 29.1 Explicit Cast

```c
(int)value
```

## 29.2 Cast Categories

- Integer to integer
- Integer to floating
- Floating to integer
- Pointer to pointer
- Pointer to integer
- Integer to pointer

## 29.3 Dangerous Casts

- Alignment violations
- Invalid pointer conversions
- Truncation
- Signedness issues

---

# 30. Input and Output

## 30.1 Standard Streams

- `stdin`
- `stdout`
- `stderr`

## 30.2 Output

- `printf`
- `fprintf`
- `sprintf`
- `snprintf`
- `puts`
- `fputs`
- `putchar`
- `fputc`

## 30.3 Input

- `scanf`
- `fscanf`
- `sscanf`
- `fgets`
- `getchar`
- `fgetc`

---

# 31. Format Specifiers

## 31.1 Integer

- `%d`
- `%i`
- `%u`
- `%o`
- `%x`
- `%X`

## 31.2 Floating Point

- `%f`
- `%e`
- `%E`
- `%g`
- `%G`

## 31.3 Character/String

- `%c`
- `%s`

## 31.4 Pointer

- `%p`

## 31.5 Length Modifiers

- `hh`
- `h`
- `l`
- `ll`
- `j`
- `z`
- `t`
- `L`

## 31.6 Formatting Flags

- `-`
- `+`
- space
- `0`
- `#`

## 31.7 Width and Precision

- Fixed width
- Dynamic width
- Fixed precision
- Dynamic precision

---

# 32. Conditional Statements

## 32.1 `if`

- Single condition
- Nested conditions

## 32.2 `if-else`

- True branch
- False branch

## 32.3 `else-if`

- Multiple conditions

## 32.4 `switch`

- `case`
- `default`
- `break`
- Fall-through

---

# 33. Loops

## 33.1 `for`

- Initialization
- Condition
- Increment/decrement

## 33.2 `while`

- Entry-controlled loop

## 33.3 `do-while`

- Exit-controlled loop

## 33.4 Nested Loops

- Loop inside loop

## 33.5 Infinite Loops

- Intentional infinite loops
- Termination conditions

---

# 34. Jump Statements

## 34.1 `break`

- Loop termination
- Switch termination

## 34.2 `continue`

- Skip current iteration

## 34.3 `return`

- Return value
- Function termination

## 34.4 `goto`

- Labels
- Cleanup patterns
- Error handling
- Limitations

---

# 35. Functions

## 35.1 Function Declaration

- Prototype
- Parameter types
- Return type

## 35.2 Function Definition

- Function body
- Parameters
- Return statement

## 35.3 Function Call

- Arguments
- Return values

## 35.4 Function Types

- No parameters
- Parameters
- Return values
- `void` functions

---

# 36. Function Parameters

## 36.1 Pass by Value

- Primitive values
- Structure values

## 36.2 Pointer Parameters

- Modify caller objects
- Output parameters

## 36.3 Array Parameters

- Array-to-pointer adjustment

## 36.4 Structure Parameters

- Pass by value
- Pass by pointer

---

# 37. Function Return Values

## 37.1 Returning Basic Types

- Integer
- Floating point
- Character

## 37.2 Returning Structures

- Structure return

## 37.3 Returning Pointers

- Lifetime considerations
- Static storage
- Dynamic storage

## 37.4 Never Return

- Pointer to dead automatic local object

---

# 38. Recursion

## 38.1 Basic Recursion

- Base case
- Recursive case

## 38.2 Types

- Direct recursion
- Indirect recursion
- Tail recursion
- Mutual recursion

## 38.3 Applications

- Tree traversal
- DFS
- Divide and conquer
- Backtracking

---

# 39. Arrays

## 39.1 One-Dimensional Arrays

- Declaration
- Initialization
- Indexing
- Traversal

## 39.2 Array Size

- `sizeof`
- Number of elements

## 39.3 Array Initialization

- Full initialization
- Partial initialization
- Zero initialization
- Designated initialization

## 39.4 Array Bounds

- Valid indices
- Out-of-bounds behavior

---

# 40. Multidimensional Arrays

## 40.1 Two-Dimensional Arrays

- Matrix
- Rows
- Columns

## 40.2 Higher Dimensions

- 3D arrays
- N-dimensional arrays

## 40.3 Memory Layout

- Row-major layout

## 40.4 Function Parameters

- Array dimension requirements
- Variable-length array parameters

---

# 41. Strings

## 41.1 C String Definition

- Character array
- Null terminator

## 41.2 String Initialization

- String literal
- Character array

## 41.3 String Length

- `strlen`

## 41.4 String Copy

- `strcpy`
- `strncpy`

## 41.5 String Concatenation

- `strcat`
- `strncat`

## 41.6 String Comparison

- `strcmp`
- `strncmp`

## 41.7 String Searching

- `strchr`
- `strrchr`
- `strstr`

---

# 42. Character Arrays

## 42.1 Character Array vs String

- Null termination
- Array size
- String literals

## 42.2 Mutable Strings

- Character arrays

## 42.3 String Literals

- Storage
- Modification restrictions

---

# 43. Pointers

## 43.1 Pointer Definition

- Address
- Pointer variable
- Pointee

## 43.2 Address-of Operator

- `&`

## 43.3 Dereference Operator

- `*`

## 43.4 Pointer Initialization

- Valid address
- NULL
- Address of object

---

# 44. Pointer Arithmetic

## 44.1 Addition

- `p + n`

## 44.2 Subtraction

- `p - n`

## 44.3 Increment

- `p++`

## 44.4 Decrement

- `p--`

## 44.5 Pointer Difference

- `ptrdiff_t`

## 44.6 Pointer Comparison

- Equality
- Ordering where valid

## 44.7 One-Past-End Pointer

- Valid pointer formation
- Cannot be dereferenced

---

# 45. Pointer Types

## 45.1 Basic Pointer Types

- `int *`
- `char *`
- `float *`
- `double *`

## 45.2 Pointer to Structure

- `struct X *`

## 45.3 Pointer to Union

- `union X *`

## 45.4 Pointer to Pointer

- `int **`

## 45.5 Pointer to Array

- `int (*p)[10]`

## 45.6 Array of Pointers

- `int *p[10]`

---

# 46. Arrays and Pointers

## 46.1 Array-to-Pointer Conversion

- Array expression
- Pointer to first element

## 46.2 Array Indexing

```text
a[i]
*(a + i)
```

## 46.3 `sizeof` Difference

- Array size
- Pointer size

## 46.4 Passing Arrays

- Pointer parameters

---

# 47. Pointers and Functions

## 47.1 Pointer Parameters

- Modify caller data

## 47.2 Output Parameters

- Returning multiple values

## 47.3 Function Pointer

- Function address
- Function pointer type

---

# 48. Function Pointers

## 48.1 Declaration

```c
int (*operation)(int, int);
```

## 48.2 Calling

- Direct call
- Indirect call

## 48.3 Arrays of Function Pointers

- Dispatch tables

## 48.4 Callback Functions

- Event handling
- Sorting
- Custom operations

---

# 49. `const` and Pointers

## 49.1 Pointer to Const

```c
const int *p;
```

## 49.2 Const Pointer

```c
int *const p;
```

## 49.3 Const Pointer to Const

```c
const int *const p;
```

## 49.4 API Design

- Read-only parameters
- Const correctness

---

# 50. `void *`

## 50.1 Generic Pointer

- Generic object access

## 50.2 Conversion

- Object pointer conversion

## 50.3 Generic Data Structures

- Linked lists
- Arrays
- Containers

---

# 51. Null Pointers

## 51.1 NULL

- Null pointer constant
- Pointer comparison

## 51.2 C23 `nullptr`

- Null pointer constant

## 51.3 Null Dereference

- Invalid operation
- Undefined behavior

---

# 52. Structures

## 52.1 Structure Declaration

- Structure tag
- Members

## 52.2 Structure Definition

- Structure object

## 52.3 Member Access

- `.`
- `->`

## 52.4 Structure Initialization

- Positional initialization
- Designated initialization

---

# 53. Nested Structures

## 53.1 Structure Inside Structure

- Embedded objects

## 53.2 Structure Pointers

- Nested pointer members

## 53.3 Complex Data Models

- Employee
- Address
- Date
- Product
- Network packet

---

# 54. Self-Referential Structures

## 54.1 Linked List

- Node
- Next pointer

## 54.2 Tree

- Left pointer
- Right pointer

## 54.3 Graph

- Adjacency structures

---

# 55. Structure Padding

## 55.1 Alignment

- Member alignment

## 55.2 Padding

- Internal padding
- Tail padding

## 55.3 `sizeof(struct)`

- Why structure size differs from member-size sum

## 55.4 Portable Structure Design

- Avoid layout assumptions

---

# 56. Unions

## 56.1 Union Declaration

- Union members
- Shared storage

## 56.2 Union Size

- Largest member
- Alignment

## 56.3 Union Access

- Active member considerations

## 56.4 Applications

- Variant data
- Protocols
- Embedded programming

---

# 57. Enumerations

## 57.1 Enum Declaration

- Enumeration constants

## 57.2 Explicit Values

- Custom enum values

## 57.3 Applications

- State machines
- Status codes
- Flags

## 57.4 C23 Enumeration Improvements

- Modern enumeration features

---

# 58. `typedef`

## 58.1 Basic Typedef

- Alias for types

## 58.2 Structure Typedef

- Simplified structure declarations

## 58.3 Function Pointer Typedef

- Callback types

## 58.4 Opaque Types

- Library API design

---

# 59. Bitwise Programming

## 59.1 Bitwise AND

- `&`

## 59.2 Bitwise OR

- `|`

## 59.3 Bitwise XOR

- `^`

## 59.4 Bitwise NOT

- `~`

## 59.5 Left Shift

- `<<`

## 59.6 Right Shift

- `>>`

---

# 60. Bit Manipulation

## 60.1 Set Bit

- OR mask

## 60.2 Clear Bit

- AND with inverted mask

## 60.3 Toggle Bit

- XOR mask

## 60.4 Test Bit

- AND mask

## 60.5 Bit Masks

- Single-bit masks
- Multi-bit masks

## 60.6 Flags

- Permission flags
- Configuration flags

---

# 61. Bit Fields

## 61.1 Bit-Field Declaration

- Width
- Member type

## 61.2 Applications

- Flags
- Hardware registers

## 61.3 Limitations

- Implementation-defined layout
- Portability issues

---

# 62. Dynamic Memory

## 62.1 `malloc`

- Allocation
- Uninitialized bytes

## 62.2 `calloc`

- Allocation
- Zero initialization

## 62.3 `realloc`

- Resize allocation
- Move possibility
- Failure handling

## 62.4 `free`

- Deallocation

---

# 63. Memory Management

## 63.1 Memory Ownership

- Owner
- Borrower
- Transfer

## 63.2 Memory Lifetime

- Allocation
- Usage
- Release

## 63.3 Memory Leak

- Lost allocation

## 63.4 Dangling Pointer

- Pointer to dead object

## 63.5 Use-After-Free

- Access after deallocation

## 63.6 Double Free

- Releasing same allocation twice

## 63.7 Invalid Free

- Freeing non-allocated memory

---

# 64. Preprocessor

## 64.1 `#include`

- System headers
- Local headers

## 64.2 `#define`

- Object macros
- Function macros

## 64.3 `#undef`

- Remove macro

## 64.4 Conditional Compilation

- `#if`
- `#ifdef`
- `#ifndef`
- `#elif`
- `#else`
- `#endif`

## 64.5 Other Directives

- `#error`
- `#warning` where supported
- `#line`
- `#pragma`

---

# 65. Macros

## 65.1 Object-Like Macros

- Constants

## 65.2 Function-Like Macros

- Parameters
- Parentheses

## 65.3 Variadic Macros

- `...`
- `__VA_ARGS__`

## 65.4 Stringification

- `#`

## 65.5 Token Pasting

- `##`

## 65.6 Macro Pitfalls

- Multiple evaluation
- Operator precedence
- Side effects
- Name collisions

---

# 66. Header Files

## 66.1 Header Purpose

- Declarations
- Types
- Macros
- API definitions

## 66.2 Include Guards

- `#ifndef`
- `#define`
- `#endif`

## 66.3 `#pragma once`

- Compiler support
- Portability considerations

## 66.4 Public and Private Headers

- Public API
- Internal implementation

---

# 67. Multi-File Programs

## 67.1 `.c` Files

- Implementation

## 67.2 `.h` Files

- Interface

## 67.3 Compilation

- Separate compilation

## 67.4 Linking

- Combine object files

## 67.5 Dependency Management

- Header dependencies

---

# 68. External and Internal Linkage

## 68.1 External Symbols

- Global functions
- Global variables

## 68.2 Internal Symbols

- `static`

## 68.3 `extern`

- External declarations

## 68.4 API Visibility

- Public symbols
- Private symbols

---

# 69. Static Libraries

## 69.1 Object Files

- `.o`
- `.obj`

## 69.2 Static Library

- `.a`
- `.lib`

## 69.3 Static Linking

- Symbol extraction
- Link-time inclusion

---

# 70. Shared Libraries

## 70.1 Linux

- `.so`

## 70.2 macOS

- `.dylib`

## 70.3 Windows

- `.dll`

## 70.4 Dynamic Linking

- Dynamic loader
- Symbol resolution
- Runtime dependencies

---

# 71. Error Handling

## 71.1 Return Codes

- Success
- Failure
- Error codes

## 71.2 `errno`

- Error state

## 71.3 `perror`

- Human-readable error

## 71.4 `strerror`

- Convert error code to text

## 71.5 Cleanup

- Resource release
- Error paths

---

# 72. Assertions

## 72.1 `assert`

- Runtime assertions

## 72.2 `NDEBUG`

- Disable assertions

## 72.3 Assertions vs Error Handling

- Programmer errors
- Runtime failures

---

# 73. `errno`

## 73.1 `<errno.h>`

- `errno`

## 73.2 Common Errors

- `EINVAL`
- `ENOMEM`
- `EIO`
- `ENOENT`

## 73.3 Error Reporting

- `perror`
- `strerror`

---

# 74. File Handling

## 74.1 `FILE`

- File stream

## 74.2 Opening Files

- `fopen`

## 74.3 Closing Files

- `fclose`

## 74.4 File Modes

- `r`
- `w`
- `a`
- `r+`
- `w+`
- `a+`

## 74.5 Binary Modes

- `rb`
- `wb`
- `ab`
- Update variants

---

# 75. Text Files

## 75.1 Reading

- `fgetc`
- `fgets`
- `fscanf`

## 75.2 Writing

- `fputc`
- `fputs`
- `fprintf`

## 75.3 End of File

- `EOF`
- `feof`

## 75.4 File Errors

- `ferror`

---

# 76. Binary Files

## 76.1 Reading

- `fread`

## 76.2 Writing

- `fwrite`

## 76.3 Binary Serialization

- Object representation
- Byte order
- Padding

---

# 77. File Positioning

## 77.1 `fseek`

- Relative positioning

## 77.2 `ftell`

- Current position

## 77.3 `rewind`

- Reset position

## 77.4 Position Constants

- `SEEK_SET`
- `SEEK_CUR`
- `SEEK_END`

---

# 78. Command-Line Arguments

## 78.1 `argc`

- Argument count

## 78.2 `argv`

- Argument vector

## 78.3 Command Parsing

- Options
- Flags
- Values
- Validation

## 78.4 Portable Argument Handling

- Manual parsing
- Platform-specific parsers

---

# 79. Environment Variables

## 79.1 `getenv`

- Read environment variable

## 79.2 Environment

- `PATH`
- `HOME`
- `USER`

## 79.3 Environment Security

- Untrusted environment
- Configuration validation

---

# 80. Variadic Functions

## 80.1 `<stdarg.h>`

- `va_list`
- `va_start`
- `va_arg`
- `va_end`
- `va_copy`

## 80.2 Variadic Function Design

- Parameter count
- Type information
- Sentinel values

## 80.3 Examples

- Logging
- Formatting
- `printf`-style APIs

---

# 81. Standard C Library

## 81.1 Core Headers

- `<assert.h>`
- `<ctype.h>`
- `<errno.h>`
- `<float.h>`
- `<limits.h>`
- `<locale.h>`
- `<math.h>`
- `<setjmp.h>`
- `<signal.h>`
- `<stdarg.h>`
- `<stddef.h>`
- `<stdint.h>`
- `<stdio.h>`
- `<stdlib.h>`
- `<string.h>`
- `<time.h>`

## 81.2 Modern Headers

- `<stdatomic.h>`
- `<threads.h>`
- `<uchar.h>`
- `<stdalign.h>`
- `<stdbool.h>`
- `<stdnoreturn.h>`
- `<inttypes.h>`
- `<complex.h>`
- `<fenv.h>`
- `<tgmath.h>`

---

# 82. Character Handling Library

## 82.1 Classification

- `isalpha`
- `isdigit`
- `isalnum`
- `isspace`
- `islower`
- `isupper`
- `ispunct`
- `isprint`
- `iscntrl`
- `isxdigit`

## 82.2 Conversion

- `tolower`
- `toupper`

---

# 83. String Library

## 83.1 Length

- `strlen`

## 83.2 Copy

- `strcpy`
- `strncpy`

## 83.3 Concatenation

- `strcat`
- `strncat`

## 83.4 Comparison

- `strcmp`
- `strncmp`

## 83.5 Searching

- `strchr`
- `strrchr`
- `strstr`

## 83.6 Tokenization

- `strtok`

## 83.7 Span Functions

- `strspn`
- `strcspn`
- `strpbrk`

## 83.8 Locale-Aware Functions

- `strcoll`
- `strxfrm`

---

# 84. Memory Library

## 84.1 Copy

- `memcpy`
- `memmove`

## 84.2 Compare

- `memcmp`

## 84.3 Set

- `memset`

## 84.4 Search

- `memchr`

## 84.5 Important Differences

- `memcpy` vs `memmove`
- Overlapping memory
- Object representation

---

# 85. Mathematics Library

## 85.1 Basic

- `fabs`
- `fmod`
- `sqrt`

## 85.2 Powers

- `pow`
- `exp`
- `log`
- `log10`

## 85.3 Trigonometry

- `sin`
- `cos`
- `tan`
- `asin`
- `acos`
- `atan`
- `atan2`

## 85.4 Rounding

- `floor`
- `ceil`
- `round`
- `trunc`

## 85.5 Classification

- `isnan`
- `isinf`
- `isfinite`
- `isnormal`

---

# 86. Time and Date

## 86.1 Time Types

- `time_t`
- `clock_t`
- `struct tm`

## 86.2 Functions

- `time`
- `clock`
- `difftime`
- `mktime`
- `localtime`
- `gmtime`
- `strftime`

## 86.3 Concepts

- Calendar time
- CPU time
- Local time
- UTC

---

# 87. Localization

## 87.1 Locale

- `setlocale`

## 87.2 Categories

- `LC_ALL`
- `LC_COLLATE`
- `LC_CTYPE`
- `LC_MONETARY`
- `LC_NUMERIC`
- `LC_TIME`

---

# 88. Wide Characters

## 88.1 Types

- `wchar_t`
- `wint_t`

## 88.2 Wide I/O

- `wprintf`
- `fwprintf`
- `fgetwc`
- `fputwc`

## 88.3 Wide Strings

- `wcslen`
- `wcscpy`
- `wcscmp`

---

# 89. Complex Numbers

## 89.1 Types

- `float complex`
- `double complex`
- `long double complex`

## 89.2 Functions

- `creal`
- `cimag`
- `cabs`
- `carg`
- `conj`
- `csqrt`
- `cpow`

---

# 90. Floating-Point Environment

## 90.1 `<fenv.h>`

- Floating-point environment

## 90.2 Rounding

- FE_TONEAREST
- FE_DOWNWARD
- FE_UPWARD
- FE_TOWARDZERO

## 90.3 Exceptions

- Divide by zero
- Invalid operation
- Overflow
- Underflow
- Inexact

---

# 91. Non-Local Jumps

## 91.1 `<setjmp.h>`

- `jmp_buf`
- `setjmp`
- `longjmp`

## 91.2 Applications

- Error recovery
- Non-local control flow

## 91.3 Limitations

- Resource cleanup
- Automatic variables
- Complex control flow

---

# 92. Signals

## 92.1 Standard Signal Concepts

- Signal
- Signal handler
- Signal delivery

## 92.2 Common Signals

- `SIGINT`
- `SIGTERM`
- `SIGSEGV`
- `SIGABRT`
- `SIGFPE`

## 92.3 Signal Functions

- `signal`
- `raise`

## 92.4 Signal Safety

- Async-signal-safe functions
- Handler restrictions

---

# 93. Standard Integer Types

## 93.1 Exact-Width Types

- `int8_t`
- `int16_t`
- `int32_t`
- `int64_t`
- `uint8_t`
- `uint16_t`
- `uint32_t`
- `uint64_t`

## 93.2 Minimum-Width Types

- `int_leastN_t`
- `uint_leastN_t`

## 93.3 Fast Types

- `int_fastN_t`
- `uint_fastN_t`

## 93.4 Pointer-Sized Types

- `intptr_t`
- `uintptr_t`

---

# 94. Standard Definitions

## 94.1 `size_t`

- Object sizes
- Array sizes
- Memory functions

## 94.2 `ptrdiff_t`

- Pointer differences

## 94.3 `max_align_t`

- Maximum alignment

## 94.4 `offsetof`

- Structure member offset

## 94.5 `NULL`

- Null pointer macro

---

# 95. Generic Programming

## 95.1 C Generic Techniques

- `void *`
- Function pointers
- Macros
- `_Generic`

## 95.2 Generic Containers

- Generic vector
- Generic list
- Generic hash table

---

# 96. `_Generic`

## 96.1 Generic Selection

- Compile-time type selection

## 96.2 Type-Based Macros

- Generic math
- Generic utilities

## 96.3 Limitations

- Compile-time dispatch
- No template-style type generation

---

# 97. `inline`

## 97.1 Inline Functions

- `inline`
- `static inline`

## 97.2 Inline and Linkage

- External definitions
- Internal definitions

## 97.3 Optimization

- Compiler decision
- Inline does not force machine-code inlining

---

# 98. `restrict`

## 98.1 Purpose

- Aliasing contract

## 98.2 Usage

- Pointer parameters
- Array processing

## 98.3 Optimization

- Compiler alias analysis

---

# 99. Alignment

## 99.1 Alignment Concepts

- Natural alignment
- Required alignment
- Padding

## 99.2 `_Alignof`

- Query alignment

## 99.3 `_Alignas`

- Specify alignment

## 99.4 C23

- Modern alignment syntax

---

# 100. `_Static_assert`

## 100.1 Compile-Time Assertion

- Validate assumptions

## 100.2 Applications

- Structure size
- Type size
- Configuration validation
- Compile-time constraints

## 100.3 C23

- `static_assert`

---

# 101. Atomic Programming

## 101.1 `_Atomic`

- Atomic types
- Atomic objects

## 101.2 Atomic Operations

- Load
- Store
- Exchange
- Fetch-add
- Fetch-sub
- Compare-exchange

## 101.3 Memory Orders

- Relaxed
- Acquire
- Release
- Acquire-release
- Sequentially consistent

---

# 102. Threads

## 102.1 C11 Threads

- `thrd_create`
- `thrd_join`
- `thrd_exit`

## 102.2 Mutex

- `mtx_init`
- `mtx_lock`
- `mtx_unlock`
- `mtx_destroy`

## 102.3 Condition Variables

- `cnd_init`
- `cnd_wait`
- `cnd_signal`
- `cnd_broadcast`

---

# 103. Thread-Local Storage

## 103.1 `_Thread_local`

- Thread-local objects

## 103.2 Applications

- Thread-specific state
- Per-thread buffers
- Error state

---

# 104. C Memory Model

## 104.1 Objects

- Object
- Value
- Representation

## 104.2 Memory Access

- Read
- Write
- Modification

## 104.3 Sequencing

- Sequenced-before
- Happens-before
- Synchronization

## 104.4 Data Races

- Conflicting accesses
- Undefined behavior

---

# 105. Object Representation

## 105.1 Bytes

- Object representation
- Character representation

## 105.2 Padding

- Padding bytes
- Structure padding

## 105.3 Representation Access

- `unsigned char`
- Character-type access

---

# 106. Object Lifetime

## 106.1 Object Creation

- Definition
- Allocation

## 106.2 Object Lifetime

- Start
- Active lifetime
- End

## 106.3 Lifetime Errors

- Use after lifetime
- Dangling pointers

---

# 107. Effective Type

## 107.1 Effective Type Rules

- Declared objects
- Allocated objects

## 107.2 Accessing Objects

- Compatible types
- Qualified types
- Corresponding signed/unsigned types
- Character types

---

# 108. Strict Aliasing

## 108.1 Aliasing

- Multiple pointers
- Same storage

## 108.2 Valid Aliasing

- Compatible types
- Character access

## 108.3 Invalid Aliasing

- Incompatible object access

## 108.4 Optimization Impact

- Compiler assumptions
- `-fstrict-aliasing`

---

# 109. Evaluation Order

## 109.1 Evaluation

- Operators
- Operands
- Function arguments

## 109.2 Side Effects

- Increment
- Assignment
- Function calls

## 109.3 Sequencing

- Sequenced-before
- Unsequenced operations

---

# 110. Undefined Behavior

## 110.1 Common Causes

- Out-of-bounds access
- Null dereference
- Use-after-free
- Double free
- Invalid pointer
- Signed overflow
- Invalid shift
- Division by zero
- Invalid format string
- Data race
- Uninitialized usage

## 110.2 Consequences

- Crash
- Incorrect output
- Compiler optimization surprises
- Security vulnerabilities

---

# 111. Implementation-Defined Behavior

## 111.1 Definition

- Implementation chooses behavior
- Implementation documents behavior

## 111.2 Examples

- `char` signedness
- Integer representation properties
- Type sizes
- Certain shifts

---

# 112. Unspecified Behavior

## 112.1 Definition

- Multiple permitted behaviors
- Implementation can choose

## 112.2 Difference

- Undefined
- Implementation-defined
- Unspecified

---

# 113. Integer Overflow

## 113.1 Signed Overflow

- Undefined behavior

## 113.2 Unsigned Overflow

- Modular arithmetic

## 113.3 Conversion

- Signed/unsigned conversion
- Truncation

## 113.4 Safe Integer Programming

- Range checks
- Correct types
- Checked arithmetic patterns

---

# 114. Floating-Point Behavior

## 114.1 Precision

- Representation limitations

## 114.2 Rounding

- Rounding error

## 114.3 Comparison

- Exact comparison
- Tolerance-based comparison

## 114.4 Special Values

- NaN
- Infinity
- Signed zero

---

# 115. Endianness

## 115.1 Little Endian

- Least significant byte first

## 115.2 Big Endian

- Most significant byte first

## 115.3 Network Byte Order

- Big-endian convention

## 115.4 Detecting Endianness

- Runtime techniques
- Portable considerations

---

# 116. Structure Layout

## 116.1 Member Ordering

- Declaration order

## 116.2 Padding

- Internal padding
- Tail padding

## 116.3 Alignment

- Member alignment
- Structure alignment

## 116.4 `offsetof`

- Member offsets

---

# 117. Process Memory Layout

## 117.1 Text

- Machine code

## 117.2 Read-Only Data

- String literals
- Constant data

## 117.3 Data

- Initialized global/static objects

## 117.4 BSS

- Zero-initialized global/static objects

## 117.5 Heap

- Dynamic allocation

## 117.6 Stack

- Automatic storage
- Function call frames

---

# 118. Stack

## 118.1 Stack Frame

- Parameters
- Local variables
- Return address
- Saved registers

## 118.2 Stack Overflow

- Deep recursion
- Large local objects

## 118.3 Stack vs Heap

- Lifetime
- Allocation
- Performance

---

# 119. Heap

## 119.1 Dynamic Allocation

- `malloc`
- `calloc`
- `realloc`
- `free`

## 119.2 Heap Fragmentation

- Internal fragmentation
- External fragmentation

## 119.3 Custom Allocators

- Free lists
- Memory pools
- Arenas

---

# 120. Compilation and Linking Internals

## 120.1 Preprocessor

- Macro expansion
- Header expansion

## 120.2 Compiler

- Lexer
- Parser
- Semantic analysis
- Optimization
- Code generation

## 120.3 Assembler

- Assembly to object code

## 120.4 Linker

- Symbol resolution
- Relocations
- Libraries

---

# 121. ABI

## 121.1 ABI Concepts

- Calling convention
- Data layout
- Type sizes
- Alignment
- Symbol conventions

## 121.2 Function ABI

- Arguments
- Return values
- Registers
- Stack

## 121.3 Binary Compatibility

- Shared libraries
- Versioning

---

# 122. Object Files

## 122.1 Sections

- `.text`
- `.rodata`
- `.data`
- `.bss`

## 122.2 Symbols

- Local symbols
- Global symbols
- Undefined symbols

## 122.3 Relocations

- Relocation entries
- Link-time adjustment

---

# 123. Executable Formats

## 123.1 Linux

- ELF

## 123.2 Windows

- PE/COFF

## 123.3 macOS

- Mach-O

## 123.4 Concepts

- Headers
- Sections
- Segments
- Symbols
- Dynamic libraries

---

# 124. Debugging

## 124.1 Debuggers

- GDB
- LLDB
- Visual Studio debugger

## 124.2 Breakpoints

- Function breakpoint
- Line breakpoint
- Conditional breakpoint

## 124.3 Inspection

- Variables
- Registers
- Memory
- Stack

## 124.4 Execution

- Step
- Next
- Continue
- Finish

## 124.5 Stack

- Backtrace
- Frames

---

# 125. Compiler Warnings

## 125.1 GCC/Clang

- `-Wall`
- `-Wextra`
- `-Wpedantic`
- `-Wconversion`
- `-Wshadow`
- `-Wformat`
- `-Werror`

## 125.2 Warning Strategy

- Enable warnings
- Fix warnings
- Treat important warnings as errors

---

# 126. Sanitizers

## 126.1 AddressSanitizer

- Buffer overflow
- Use-after-free
- Double free

## 126.2 UndefinedBehaviorSanitizer

- Undefined behavior detection

## 126.3 LeakSanitizer

- Memory leaks

## 126.4 ThreadSanitizer

- Data races

---

# 127. Static Analysis

## 127.1 Tools

- Clang Static Analyzer
- clang-tidy
- Cppcheck

## 127.2 Analysis

- Null dereferences
- Resource leaks
- Unreachable code
- Suspicious conversions
- API misuse

---

# 128. Testing

## 128.1 Test Types

- Unit tests
- Integration tests
- System tests
- Regression tests
- Stress tests
- Performance tests

## 128.2 Test Concepts

- Test cases
- Fixtures
- Assertions
- Coverage

---

# 129. Unit Testing

## 129.1 Test Functions

- Inputs
- Expected outputs

## 129.2 Edge Cases

- Empty input
- Zero
- Maximum values
- Invalid values
- NULL

## 129.3 Test Frameworks

- Unity
- CMocka
- Check
- Criterion

---

# 130. Fuzz Testing

## 130.1 Fuzzing

- Random inputs
- Mutation
- Corpus

## 130.2 Targets

- Parsers
- File readers
- Protocol handlers
- Command-line programs

## 130.3 Tools

- libFuzzer
- AFL/AFL++
- Sanitizers

---

# 131. Performance

## 131.1 Performance Metrics

- Execution time
- CPU usage
- Memory usage
- Throughput
- Latency

## 131.2 Bottlenecks

- CPU
- Memory
- I/O
- Network
- Synchronization

---

# 132. Profiling

## 132.1 CPU Profiling

- gprof
- perf
- Instruments

## 132.2 Memory Profiling

- Valgrind
- Heap profilers

## 132.3 Benchmarking

- Microbenchmarks
- End-to-end benchmarks
- Statistical measurement

---

# 133. Optimization

## 133.1 Compiler Optimization

- `-O0`
- `-O1`
- `-O2`
- `-O3`
- `-Os`
- `-Ofast`

## 133.2 Optimization Techniques

- Constant folding
- Dead-code elimination
- Loop optimization
- Inlining
- Vectorization

## 133.3 Programmer Optimization

- Better algorithms
- Better data structures
- Cache locality
- Reduced allocations

---

# 134. CPU Cache

## 134.1 Cache Levels

- L1
- L2
- L3

## 134.2 Locality

- Temporal locality
- Spatial locality

## 134.3 Cache-Friendly Code

- Sequential access
- Compact structures
- Reduced pointer chasing

---

# 135. Data-Oriented Programming

## 135.1 Array of Structures

- AoS

## 135.2 Structure of Arrays

- SoA

## 135.3 Applications

- Games
- Simulation
- High-performance computing
- SIMD workloads

---

# 136. Data Structures

## 136.1 Linear

- Array
- Dynamic array
- Linked list
- Stack
- Queue
- Deque

## 136.2 Non-Linear

- Tree
- Heap
- Graph
- Trie

## 136.3 Associative

- Hash table
- Map
- Set

---

# 137. Algorithms

## 137.1 Algorithm Concepts

- Input
- Output
- Correctness
- Termination
- Complexity

## 137.2 Algorithm Categories

- Searching
- Sorting
- Graph algorithms
- String algorithms
- Greedy algorithms
- Dynamic programming
- Backtracking
- Divide and conquer

---

# 138. Complexity Analysis

## 138.1 Big-O

- O(1)
- O(log n)
- O(n)
- O(n log n)
- O(n²)
- O(2ⁿ)
- O(n!)

## 138.2 Space Complexity

- Auxiliary memory
- Input memory

## 138.3 Cases

- Best case
- Average case
- Worst case

---

# 139. Searching

## 139.1 Linear Search

- Sequential scan

## 139.2 Binary Search

- Sorted data
- Divide and conquer

## 139.3 Hash Search

- Hash function
- Average constant-time lookup

---

# 140. Sorting

## 140.1 Basic Sorting

- Bubble sort
- Selection sort
- Insertion sort

## 140.2 Efficient Sorting

- Merge sort
- Quick sort
- Heap sort

## 140.3 Specialized Sorting

- Counting sort
- Radix sort
- Bucket sort

## 140.4 Sorting Properties

- Stable
- In-place
- Adaptive

---

# 141. Linked Lists

## 141.1 Singly Linked List

- Node
- Head
- Next

## 141.2 Operations

- Insert
- Delete
- Search
- Traverse
- Reverse

## 141.3 Doubly Linked List

- Previous
- Next

## 141.4 Circular Linked List

- Circular traversal

---

# 142. Stack

## 142.1 Operations

- Push
- Pop
- Peek

## 142.2 Implementations

- Array
- Linked list

## 142.3 Applications

- Recursion
- Expression parsing
- DFS
- Undo systems

---

# 143. Queue

## 143.1 Operations

- Enqueue
- Dequeue
- Front
- Rear

## 143.2 Implementations

- Array
- Circular array
- Linked list

## 143.3 Applications

- Scheduling
- BFS
- Producer-consumer

---

# 144. Deque

## 144.1 Operations

- Push front
- Push back
- Pop front
- Pop back

## 144.2 Applications

- Sliding window
- Scheduling

---

# 145. Hash Tables

## 145.1 Hash Functions

- Integer hashing
- String hashing

## 145.2 Collision Handling

- Chaining
- Linear probing
- Quadratic probing
- Double hashing

## 145.3 Operations

- Insert
- Search
- Delete
- Resize
- Rehash

---

# 146. Trees

## 146.1 Binary Tree

- Root
- Child
- Parent
- Leaf
- Height
- Depth

## 146.2 Traversals

- Preorder
- Inorder
- Postorder
- Level-order

---

# 147. Binary Search Tree

## 147.1 Operations

- Search
- Insert
- Delete

## 147.2 Complexity

- Balanced
- Unbalanced

---

# 148. Balanced Trees

## 148.1 AVL Tree

- Balance factor
- Left rotation
- Right rotation
- Double rotation

## 148.2 Red-Black Tree

- Coloring
- Rotations
- Balancing

---

# 149. Heaps

## 149.1 Min Heap

- Minimum at root

## 149.2 Max Heap

- Maximum at root

## 149.3 Operations

- Insert
- Extract
- Heapify

## 149.4 Applications

- Priority queue
- Heap sort

---

# 150. Tries

## 150.1 Trie Structure

- Characters
- Children
- Terminal node

## 150.2 Applications

- Dictionary
- Prefix search
- Autocomplete

---

# 151. Graphs

## 151.1 Graph Types

- Directed
- Undirected
- Weighted
- Unweighted
- Cyclic
- Acyclic

## 151.2 Representation

- Adjacency matrix
- Adjacency list
- Edge list

---

# 152. Graph Traversal

## 152.1 BFS

- Queue
- Level traversal

## 152.2 DFS

- Recursion
- Explicit stack

---

# 153. Graph Algorithms

## 153.1 Shortest Path

- Dijkstra
- Bellman-Ford
- Floyd-Warshall

## 153.2 Minimum Spanning Tree

- Prim
- Kruskal

## 153.3 Other

- Topological sorting
- Cycle detection
- Connected components

---

# 154. Disjoint Set

## 154.1 Union-Find

- Parent array
- Find
- Union

## 154.2 Optimizations

- Path compression
- Union by rank
- Union by size

---

# 155. Backtracking

## 155.1 Concepts

- Candidate
- Choice
- Constraint
- Backtrack

## 155.2 Problems

- N-Queens
- Sudoku
- Permutations
- Combinations
- Maze solving

---

# 156. Dynamic Programming

## 156.1 Concepts

- Overlapping subproblems
- Optimal substructure

## 156.2 Approaches

- Top-down
- Bottom-up

## 156.3 Problems

- Fibonacci
- Knapsack
- Longest common subsequence
- Coin change

---

# 157. Greedy Algorithms

## 157.1 Concept

- Local optimal choice

## 157.2 Problems

- Activity selection
- Fractional knapsack
- Huffman coding
- Minimum spanning tree

---

# 158. Parsing

## 158.1 Parser Concepts

- Input
- Tokens
- Grammar
- Parse tree
- AST

## 158.2 Parser Types

- Recursive descent
- Table-driven parser

---

# 159. Lexical Analysis

## 159.1 Lexer

- Input characters
- Tokens

## 159.2 Token Types

- Identifier
- Keyword
- Number
- Operator
- String
- Character

---

# 160. Finite State Machines

## 160.1 Components

- States
- Events
- Transitions
- Actions

## 160.2 Applications

- Protocol parsing
- Embedded systems
- Command processing
- Lexers

---

# 161. C API Design

## 161.1 API Principles

- Clear names
- Stable interfaces
- Minimal public surface

## 161.2 API Documentation

- Parameters
- Return values
- Errors
- Ownership
- Thread safety

---

# 162. Library Design

## 162.1 Public API

- Public header

## 162.2 Private Implementation

- Private structures
- Internal functions

## 162.3 Versioning

- API compatibility
- ABI compatibility

---

# 163. Opaque Data Types

## 163.1 Opaque Structure

- Forward declaration
- Private fields

## 163.2 Constructor/Destructor

- `create`
- `destroy`

## 163.3 Encapsulation

- Hide implementation details

---

# 164. Callbacks

## 164.1 Callback Function

- Function pointer

## 164.2 User Context

- `void *user_data`

## 164.3 Applications

- Events
- Sorting
- Networking
- Libraries

---

# 165. Error and Resource Management

## 165.1 Resource Lifecycle

- Acquire
- Use
- Release

## 165.2 Resources

- Memory
- Files
- Sockets
- Mutexes
- Threads

## 165.3 Cleanup

- Cleanup labels
- `goto` cleanup patterns

---

# 166. Secure C Programming

## 166.1 Input Validation

- Length validation
- Range validation
- Format validation

## 166.2 Memory Safety

- Bounds checking
- Lifetime checking
- Ownership

## 166.3 Integer Safety

- Overflow
- Truncation
- Signedness

---

# 167. Common C Vulnerabilities

## 167.1 Buffer Overflow

- Stack overflow
- Heap overflow

## 167.2 Use-After-Free

- Dangling pointers

## 167.3 Double Free

- Repeated deallocation

## 167.4 Format String Vulnerability

- Unsafe `printf`

## 167.5 Integer Overflow

- Arithmetic overflow

## 167.6 Null Dereference

- Invalid pointer access

## 167.7 Uninitialized Memory

- Reading indeterminate values

## 167.8 Race Conditions

- Concurrent access

---

# 168. Defensive Programming

## 168.1 Validate Input

- Length
- Type
- Range

## 168.2 Validate Pointers

- NULL checks where appropriate

## 168.3 Validate Allocation

- Check allocation failure

## 168.4 Validate Resources

- Check `fopen`
- Check system calls
- Check socket operations

---

# 169. POSIX

## 169.1 POSIX Concepts

- Portable operating-system interfaces
- Unix-like systems

## 169.2 POSIX APIs

- Files
- Processes
- Threads
- Signals
- Networking
- IPC

---

# 170. Linux System Programming

## 170.1 System Calls

- File operations
- Process operations
- Memory operations

## 170.2 Linux APIs

- `open`
- `read`
- `write`
- `close`
- `stat`
- `mmap`

---

# 171. File Descriptors

## 171.1 Standard Descriptors

- `0` stdin
- `1` stdout
- `2` stderr

## 171.2 Descriptor Operations

- `open`
- `close`
- `read`
- `write`

## 171.3 Descriptor Duplication

- `dup`
- `dup2`
- `dup3`

---

# 172. System Calls

## 172.1 System Call Concept

- User mode
- Kernel mode

## 172.2 Common Calls

- `open`
- `read`
- `write`
- `close`
- `fork`
- `exec`
- `wait`
- `mmap`

---

# 173. Processes

## 173.1 Process Concepts

- PID
- Parent
- Child
- Process image

## 173.2 Process Creation

- `fork`

## 173.3 Program Replacement

- `exec`

## 173.4 Process Termination

- `exit`
- `_exit`

---

# 174. Process Control

## 174.1 Parent/Child

- Parent process
- Child process

## 174.2 Waiting

- `wait`
- `waitpid`

## 174.3 Process Groups

- Sessions
- Process groups

---

# 175. Inter-Process Communication

## 175.1 IPC Types

- Pipes
- Named pipes
- Signals
- Message queues
- Shared memory
- Sockets

---

# 176. Pipes

## 176.1 Anonymous Pipe

- `pipe`

## 176.2 Parent/Child Communication

- Read end
- Write end

## 176.3 Shell Pipelines

```text
command1 | command2
```

---

# 177. Signals

## 177.1 Signal Delivery

- Process
- Signal handler

## 177.2 POSIX Signals

- `sigaction`
- Signal masks
- Pending signals

## 177.3 Signal Safety

- Async-signal-safe operations

---

# 178. Shared Memory

## 178.1 Concepts

- Shared address space
- Synchronization

## 178.2 POSIX

- Shared memory objects
- `mmap`

## 178.3 Synchronization

- Mutex
- Semaphore
- Atomic operations

---

# 179. Memory Mapping

## 179.1 `mmap`

- File mapping
- Anonymous mapping
- Shared mapping

## 179.2 `munmap`

- Release mapping

## 179.3 Applications

- Large files
- Shared memory
- Custom allocators

---

# 180. POSIX Threads

## 180.1 `pthread_create`

- Create thread

## 180.2 `pthread_join`

- Wait for thread

## 180.3 Thread Attributes

- Detached
- Joinable
- Stack configuration

---

# 181. Mutexes

## 181.1 Mutex Concepts

- Lock
- Unlock
- Ownership

## 181.2 POSIX Mutex

- `pthread_mutex_init`
- `pthread_mutex_lock`
- `pthread_mutex_unlock`
- `pthread_mutex_destroy`

---

# 182. Condition Variables

## 182.1 Concepts

- Wait
- Signal
- Broadcast

## 182.2 POSIX

- `pthread_cond_wait`
- `pthread_cond_signal`
- `pthread_cond_broadcast`

---

# 183. Semaphores

## 183.1 Counting Semaphore

- Resource count

## 183.2 POSIX

- `sem_init`
- `sem_wait`
- `sem_post`

---

# 184. Read-Write Locks

## 184.1 Reader Lock

- Multiple readers

## 184.2 Writer Lock

- Exclusive writer

## 184.3 POSIX

- `pthread_rwlock_*`

---

# 185. Concurrency Problems

## 185.1 Race Condition

- Concurrent conflicting access

## 185.2 Deadlock

- Circular wait

## 185.3 Livelock

- Continuous activity without progress

## 185.4 Starvation

- Thread cannot obtain resources

---

# 186. Atomic Programming

## 186.1 Atomic Load

- Read atomically

## 186.2 Atomic Store

- Write atomically

## 186.3 Compare Exchange

- CAS

## 186.4 Memory Ordering

- Relaxed
- Acquire
- Release
- Sequential consistency

---

# 187. Lock-Free Programming

## 187.1 Concepts

- CAS
- Atomic operations
- Progress guarantees

## 187.2 Problems

- ABA problem
- Memory reclamation

## 187.3 Advanced Techniques

- Hazard pointers
- Epoch reclamation

---

# 188. Networking

## 188.1 Networking Fundamentals

- IP
- MAC
- Port
- Protocol
- Client
- Server

## 188.2 Protocols

- TCP
- UDP
- HTTP
- DNS
- TLS

---

# 189. Socket Programming

## 189.1 Socket Creation

- `socket`

## 189.2 Server

- `bind`
- `listen`
- `accept`

## 189.3 Client

- `connect`

## 189.4 Data Transfer

- `send`
- `recv`
- `sendto`
- `recvfrom`

---

# 190. TCP Programming

## 190.1 TCP Concepts

- Connection-oriented
- Reliable stream
- Ordering
- Flow control

## 190.2 TCP Server

- Socket
- Bind
- Listen
- Accept
- Receive
- Send

## 190.3 TCP Client

- Socket
- Connect
- Send
- Receive

---

# 191. UDP Programming

## 191.1 UDP Concepts

- Connectionless
- Datagrams
- No delivery guarantee

## 191.2 UDP APIs

- `sendto`
- `recvfrom`

## 191.3 Applications

- DNS
- Streaming
- Real-time systems

---

# 192. DNS

## 192.1 DNS Concepts

- Domain name
- IP address
- Resolver
- DNS server

## 192.2 Programming

- Name resolution
- Address resolution

---

# 193. HTTP

## 193.1 HTTP Concepts

- Request
- Response
- Headers
- Body

## 193.2 Methods

- GET
- POST
- PUT
- PATCH
- DELETE
- HEAD
- OPTIONS

## 193.3 Status Codes

- 2xx
- 3xx
- 4xx
- 5xx

---

# 194. TLS/HTTPS Concepts

## 194.1 TLS

- Encryption
- Authentication
- Integrity

## 194.2 Certificates

- Certificate
- Public key
- Private key
- Certificate authority

## 194.3 C Networking

- TLS libraries
- Secure sockets

---

# 195. Client-Server Programming

## 195.1 Server

- Socket
- Bind
- Listen
- Accept
- Request processing
- Response

## 195.2 Client

- Connect
- Send request
- Receive response

## 195.3 Concurrency

- Process-per-client
- Thread-per-client
- Thread pool
- Event-driven

---

# 196. Embedded C

## 196.1 Embedded Concepts

- Microcontroller
- Firmware
- Bare metal
- RTOS

## 196.2 Constraints

- Limited RAM
- Limited Flash
- CPU limitations
- Real-time constraints
- Power constraints

---

# 197. Microcontrollers

## 197.1 Components

- CPU
- Flash
- SRAM
- GPIO
- Timers
- ADC
- Communication peripherals

## 197.2 Programming

- Startup code
- Linker script
- Interrupt vector
- Firmware

---

# 198. Hardware Registers

## 198.1 Register Concepts

- Control register
- Status register
- Data register

## 198.2 Bit Manipulation

- Masks
- Set bits
- Clear bits
- Toggle bits

## 198.3 `volatile`

- Hardware register access

---

# 199. Memory-Mapped I/O

## 199.1 Concept

- Hardware address
- Register address

## 199.2 Access

- Volatile pointers
- Register definitions

---

# 200. Interrupts

## 200.1 Interrupt Concept

- Hardware event
- ISR

## 200.2 Interrupt Vector

- Interrupt table

## 200.3 ISR Design

- Short execution
- Avoid unsafe operations
- Shared data protection

---

# 201. Timers

## 201.1 Timer Concepts

- Counter
- Prescaler
- Period

## 201.2 Applications

- Delays
- Scheduling
- PWM
- Time measurement

---

# 202. GPIO

## 202.1 GPIO Concepts

- Input
- Output

## 202.2 Features

- Pull-up
- Pull-down
- Push-pull
- Open-drain

---

# 203. UART

## 203.1 UART Concepts

- TX
- RX
- Baud rate
- Start bit
- Stop bit
- Parity

## 203.2 C Driver

- Initialization
- Send
- Receive
- Interrupt-based UART
- Ring buffer

---

# 204. SPI

## 204.1 SPI Signals

- SCLK
- MOSI
- MISO
- CS

## 204.2 Concepts

- Master
- Slave
- Clock polarity
- Clock phase

---

# 205. I2C

## 205.1 Signals

- SDA
- SCL

## 205.2 Concepts

- Address
- Start
- Stop
- ACK
- NACK

---

# 206. CAN

## 206.1 CAN Concepts

- CAN frame
- Identifier
- Arbitration
- Data field

## 206.2 Applications

- Automotive
- Industrial systems

---

# 207. ADC

## 207.1 Concepts

- Analog input
- Digital output
- Resolution
- Sampling

## 207.2 Applications

- Sensors
- Measurement

---

# 208. PWM

## 208.1 Concepts

- Duty cycle
- Frequency
- Period

## 208.2 Applications

- Motor control
- LED brightness
- Power control

---

# 209. DMA

## 209.1 DMA Concepts

- Direct memory access
- Peripheral-to-memory
- Memory-to-peripheral

## 209.2 Benefits

- Reduced CPU usage
- High throughput

---

# 210. Watchdog

## 210.1 Watchdog Timer

- Timeout
- Reset

## 210.2 Applications

- Fault recovery
- System reliability

---

# 211. RTOS

## 211.1 RTOS Concepts

- Task
- Scheduler
- Priority
- Context switching

## 211.2 RTOS Objects

- Task
- Queue
- Semaphore
- Mutex
- Event flags
- Timer

---

# 212. Real-Time Programming

## 212.1 Hard Real-Time

- Strict deadlines

## 212.2 Soft Real-Time

- Performance targets

## 212.3 Concepts

- Latency
- Jitter
- Deadline
- Determinism

---

# 213. Cross Compilation

## 213.1 Host

- Machine performing compilation

## 213.2 Target

- Machine running program

## 213.3 Toolchain

- Compiler
- Assembler
- Linker
- Libraries

## 213.4 Sysroot

- Target headers
- Target libraries

---

# 214. C and Assembly

## 214.1 Assembly Concepts

- Registers
- Instructions
- Stack
- Branches
- Calls
- Returns

## 214.2 C-to-Assembly

- Function calls
- Loops
- Conditions
- Structures
- Pointer operations

## 214.3 Inline Assembly

- Compiler-specific extensions
- Constraints
- Registers

---

# 215. Compiler Internals

## 215.1 Front End

- Lexer
- Parser
- AST
- Semantic analysis

## 215.2 Middle End

- Intermediate representation
- Optimization

## 215.3 Back End

- Instruction selection
- Register allocation
- Code generation

---

# 216. Linker Internals

## 216.1 Symbol Resolution

- Definitions
- References

## 216.2 Relocation

- Relocation entries
- Addresses

## 216.3 Static Linking

- Archive libraries

## 216.4 Dynamic Linking

- Shared libraries
- Dynamic loader

---

# 217. Build Systems

## 217.1 Make

- Targets
- Dependencies
- Rules
- Variables
- Pattern rules
- Phony targets

## 217.2 CMake

- Targets
- Libraries
- Executables
- Include directories
- Compiler flags
- Link libraries
- Tests
- Install rules

## 217.3 Ninja

- Fast builds
- Generated build files

---

# 218. Package Management

## 218.1 Linux

- System packages
- vcpkg
- Conan

## 218.2 Dependency Management

- Libraries
- Versioning
- Transitive dependencies

---

# 219. Cross-Platform C

## 219.1 Operating Systems

- Linux
- Windows
- macOS
- BSD
- Embedded systems

## 219.2 Platform Detection

- Predefined macros
- Conditional compilation

## 219.3 Platform Abstraction

- Wrapper APIs
- Portable interfaces

---

# 220. Portability

## 220.1 Type Portability

- `stdint.h`
- `size_t`
- `ptrdiff_t`

## 220.2 Platform Portability

- OS APIs
- Compiler extensions

## 220.3 Architecture Portability

- 32-bit
- 64-bit
- ARM
- x86

## 220.4 Endianness

- Big endian
- Little endian

---

# 221. Coding Standards

## 221.1 Naming

- Variables
- Functions
- Types
- Constants

## 221.2 Formatting

- Indentation
- Braces
- Line length

## 221.3 Documentation

- API comments
- Function contracts

---

# 222. MISRA C

## 222.1 MISRA Concepts

- Safety
- Predictability
- Restricted language features

## 222.2 Topics

- Type safety
- Pointer safety
- Control flow
- Error handling
- Static analysis

## 222.3 Applications

- Automotive
- Safety-critical embedded systems

---

# 223. CERT C

## 223.1 Secure Coding

- Integer safety
- Memory safety
- Input validation
- Error handling

## 223.2 Vulnerability Prevention

- Buffer overflow
- Undefined behavior
- Race conditions

---

# 224. Documentation

## 224.1 Function Documentation

- Purpose
- Parameters
- Return value
- Errors

## 224.2 API Documentation

- Ownership
- Thread safety
- Lifetime

## 224.3 Doxygen

- Documentation comments
- API generation

---

# 225. Git

## 225.1 Basic Commands

- `git init`
- `git clone`
- `git status`
- `git add`
- `git commit`
- `git push`
- `git pull`

## 225.2 Branching

- Branch
- Merge
- Rebase
- Conflict resolution

## 225.3 Professional Workflow

- Feature branches
- Pull requests
- Code review
- Tags
- Releases

---

# 226. CI/CD

## 226.1 Continuous Integration

- Build
- Test
- Static analysis
- Sanitizers

## 226.2 Cross-Platform CI

- Linux
- Windows
- macOS

## 226.3 Release

- Debug build
- Release build
- Packaging
- Versioning

---

# 227. C23

## 227.1 Language Improvements

- `nullptr`
- `constexpr`
- `typeof`
- `typeof_unqual`
- Binary literals
- Digit separators
- Attributes

## 227.2 Modern Boolean Syntax

- `bool`
- `true`
- `false`

## 227.3 Modern Static Assertions

- `static_assert`

## 227.4 Enumeration Improvements

- Modern enumeration declarations
- Improved type flexibility

## 227.5 Library Improvements

- New library functionality
- Improved standard facilities

## 227.6 Compiler Support

- GCC support
- Clang support
- MSVC support
- Implementation differences

---

# 228. Advanced C Projects

## 228.1 Beginner Projects

- Calculator
- Unit converter
- Number guessing game
- Quiz
- Student management system
- Employee management system
- Contact manager
- Matrix calculator

## 228.2 Intermediate Projects

- Text editor
- CSV parser
- Configuration parser
- Logging library
- Dynamic array
- Linked-list library
- Hash table
- File manager

## 228.3 Advanced Projects

- JSON parser
- Memory allocator
- Thread pool
- TCP server
- HTTP server
- Database engine
- Shell
- Interpreter
- Compiler

---

# 229. System Programming Projects

## 229.1 File Utility

- File information
- Directory traversal
- Copy
- Move
- Delete

## 229.2 Shell

- Command parsing
- Process creation
- Pipes
- Redirection
- Environment variables
- Signals

## 229.3 Process Monitor

- Process information
- CPU usage
- Memory usage

## 229.4 Thread Pool

- Worker threads
- Task queue
- Synchronization

---

# 230. Embedded Projects

## 230.1 Basic

- LED controller
- Button controller
- UART terminal

## 230.2 Intermediate

- Sensor reader
- PWM controller
- ADC application
- I2C device driver
- SPI device driver

## 230.3 Advanced

- RTOS application
- Bootloader
- Device driver
- Communication protocol
- Embedded networking stack

---

# 231. Interview Preparation

## 231.1 Basic Questions

- Variables
- Data types
- Operators
- Conditions
- Loops
- Functions

## 231.2 Pointer Questions

- Pointer
- Pointer-to-pointer
- Function pointer
- Array pointer
- Pointer array
- Const pointer
- Pointer to const

## 231.3 Memory Questions

- Stack
- Heap
- `malloc`
- `calloc`
- `realloc`
- `free`
- Memory leak
- Dangling pointer

## 231.4 Advanced Questions

- Undefined behavior
- Strict aliasing
- Alignment
- Padding
- ABI
- Linkage
- Atomic operations
- Memory ordering
- Concurrency

---

# 232. C Mastery Checklist

## Language Fundamentals

- [ ] C syntax
- [ ] Tokens
- [ ] Keywords
- [ ] Identifiers
- [ ] Variables
- [ ] Constants
- [ ] Literals
- [ ] Data types
- [ ] Operators
- [ ] Expressions
- [ ] Type conversion
- [ ] Type casting

## Control Flow

- [ ] `if`
- [ ] `else`
- [ ] `switch`
- [ ] `for`
- [ ] `while`
- [ ] `do-while`
- [ ] `break`
- [ ] `continue`
- [ ] `goto`
- [ ] `return`

## Functions

- [ ] Declaration
- [ ] Definition
- [ ] Prototype
- [ ] Parameters
- [ ] Arguments
- [ ] Return values
- [ ] Recursion
- [ ] Function pointers
- [ ] Callbacks

## Arrays

- [ ] One-dimensional arrays
- [ ] Multidimensional arrays
- [ ] Variable-length arrays
- [ ] Array initialization
- [ ] Array parameters
- [ ] Array/pointer relationship

## Strings

- [ ] Character arrays
- [ ] String literals
- [ ] Null terminator
- [ ] String length
- [ ] Copy
- [ ] Concatenation
- [ ] Comparison
- [ ] Searching
- [ ] Tokenization

## Pointers

- [ ] Pointer basics
- [ ] Address-of
- [ ] Dereference
- [ ] Pointer arithmetic
- [ ] Pointer comparison
- [ ] Pointer-to-pointer
- [ ] Array pointer
- [ ] Pointer array
- [ ] Function pointer
- [ ] `void *`
- [ ] NULL
- [ ] `nullptr`
- [ ] Const pointers
- [ ] `restrict`

## User-Defined Types

- [ ] Structures
- [ ] Structure pointers
- [ ] Nested structures
- [ ] Self-referential structures
- [ ] Padding
- [ ] Alignment
- [ ] Unions
- [ ] Enumerations
- [ ] typedef
- [ ] Bit fields

## Memory

- [ ] Stack
- [ ] Heap
- [ ] Static storage
- [ ] Automatic storage
- [ ] Dynamic storage
- [ ] `malloc`
- [ ] `calloc`
- [ ] `realloc`
- [ ] `free`
- [ ] Memory ownership
- [ ] Memory leaks
- [ ] Dangling pointers
- [ ] Use-after-free
- [ ] Double free
- [ ] Buffer overflow

## Preprocessor

- [ ] `#include`
- [ ] `#define`
- [ ] `#undef`
- [ ] `#if`
- [ ] `#ifdef`
- [ ] `#ifndef`
- [ ] `#elif`
- [ ] `#else`
- [ ] `#endif`
- [ ] Macros
- [ ] Variadic macros
- [ ] Stringification
- [ ] Token pasting

## Files

- [ ] `FILE`
- [ ] `fopen`
- [ ] `fclose`
- [ ] `fread`
- [ ] `fwrite`
- [ ] `fgets`
- [ ] `fputs`
- [ ] `fprintf`
- [ ] `fscanf`
- [ ] `fseek`
- [ ] `ftell`
- [ ] `rewind`
- [ ] Text files
- [ ] Binary files

## Standard Library

- [ ] stdio
- [ ] stdlib
- [ ] string
- [ ] ctype
- [ ] math
- [ ] time
- [ ] errno
- [ ] assert
- [ ] stdarg
- [ ] stddef
- [ ] stdint
- [ ] inttypes
- [ ] limits
- [ ] float
- [ ] locale
- [ ] signal
- [ ] setjmp
- [ ] wchar
- [ ] complex
- [ ] fenv
- [ ] stdatomic
- [ ] threads

## Advanced C

- [ ] Scope
- [ ] Lifetime
- [ ] Storage duration
- [ ] Linkage
- [ ] Effective type
- [ ] Object representation
- [ ] Aliasing
- [ ] Strict aliasing
- [ ] Alignment
- [ ] Padding
- [ ] Evaluation order
- [ ] Undefined behavior
- [ ] Implementation-defined behavior
- [ ] Unspecified behavior
- [ ] Integer overflow
- [ ] Floating-point behavior
- [ ] Endianness

## Data Structures

- [ ] Dynamic array
- [ ] Linked list
- [ ] Doubly linked list
- [ ] Circular linked list
- [ ] Stack
- [ ] Queue
- [ ] Deque
- [ ] Priority queue
- [ ] Hash table
- [ ] Binary tree
- [ ] BST
- [ ] AVL tree
- [ ] Red-black tree
- [ ] Heap
- [ ] Trie
- [ ] Graph
- [ ] Union-Find

## Algorithms

- [ ] Big-O
- [ ] Linear search
- [ ] Binary search
- [ ] Bubble sort
- [ ] Selection sort
- [ ] Insertion sort
- [ ] Merge sort
- [ ] Quick sort
- [ ] Heap sort
- [ ] Counting sort
- [ ] Radix sort
- [ ] BFS
- [ ] DFS
- [ ] Dijkstra
- [ ] Bellman-Ford
- [ ] Floyd-Warshall
- [ ] Prim
- [ ] Kruskal
- [ ] Topological sort
- [ ] Dynamic programming
- [ ] Greedy algorithms
- [ ] Backtracking

## Concurrency

- [ ] C11 threads
- [ ] POSIX threads
- [ ] Mutex
- [ ] Condition variable
- [ ] Semaphore
- [ ] Read-write lock
- [ ] Race condition
- [ ] Deadlock
- [ ] Livelock
- [ ] Starvation
- [ ] Atomics
- [ ] Memory ordering
- [ ] Lock-free programming

## System Programming

- [ ] POSIX
- [ ] System calls
- [ ] File descriptors
- [ ] Processes
- [ ] `fork`
- [ ] `exec`
- [ ] `wait`
- [ ] Pipes
- [ ] Signals
- [ ] Shared memory
- [ ] `mmap`
- [ ] Threads
- [ ] IPC

## Networking

- [ ] IP
- [ ] TCP
- [ ] UDP
- [ ] Ports
- [ ] Sockets
- [ ] DNS
- [ ] HTTP
- [ ] HTTPS
- [ ] Client
- [ ] Server
- [ ] TCP server
- [ ] TCP client
- [ ] UDP server
- [ ] UDP client
- [ ] Multi-client server

## Embedded C

- [ ] Microcontrollers
- [ ] Registers
- [ ] Memory-mapped I/O
- [ ] `volatile`
- [ ] Interrupts
- [ ] GPIO
- [ ] Timers
- [ ] UART
- [ ] SPI
- [ ] I2C
- [ ] CAN
- [ ] ADC
- [ ] PWM
- [ ] DMA
- [ ] Watchdog
- [ ] RTOS
- [ ] Real-time programming

## Tooling

- [ ] GCC
- [ ] Clang
- [ ] GDB
- [ ] LLDB
- [ ] Valgrind
- [ ] AddressSanitizer
- [ ] UBSan
- [ ] ThreadSanitizer
- [ ] Static analysis
- [ ] Make
- [ ] CMake
- [ ] Ninja
- [ ] Git
- [ ] CI/CD
- [ ] Profilers

## Professional C

- [ ] API design
- [ ] Library design
- [ ] ABI
- [ ] Portability
- [ ] Security
- [ ] Defensive programming
- [ ] Testing
- [ ] Documentation
- [ ] Code review
- [ ] Performance optimization
- [ ] MISRA C
- [ ] CERT C
- [ ] Cross compilation
- [ ] Release engineering

---

# Final C Learning Path

```text
C Fundamentals
      ↓
Variables + Data Types
      ↓
Operators + Expressions
      ↓
Conditions + Loops
      ↓
Functions
      ↓
Arrays
      ↓
Strings
      ↓
Pointers
      ↓
Structures + Unions + Enums
      ↓
Dynamic Memory
      ↓
File Handling
      ↓
Preprocessor
      ↓
Header Files
      ↓
Multi-File Programs
      ↓
Standard Library
      ↓
Data Structures
      ↓
Algorithms
      ↓
Memory Model
      ↓
Undefined Behavior
      ↓
Compilation + Linking
      ↓
Debugging
      ↓
Testing
      ↓
Sanitizers
      ↓
Performance
      ↓
Concurrency
      ↓
Atomics
      ↓
POSIX
      ↓
System Programming
      ↓
Networking
      ↓
Embedded C
      ↓
Security
      ↓
Build Systems
      ↓
Libraries
      ↓
ABI
      ↓
Portability
      ↓
C23
      ↓
Advanced Projects
      ↓
Professional C Developer
```

# Ultimate C Goal

After completing this syllabus, you should be able to:

- Write C programs from scratch.
- Understand every fundamental C construct.
- Work confidently with pointers.
- Understand arrays and strings internally.
- Manage dynamic memory safely.
- Design structures and data structures.
- Implement algorithms.
- Understand the C memory model.
- Identify undefined behavior.
- Understand compilation and linking.
- Build static and shared libraries.
- Debug segmentation faults and memory errors.
- Use sanitizers and static-analysis tools.
- Write multithreaded C programs.
- Understand atomic operations and memory ordering.
- Write POSIX/Linux system programs.
- Build TCP/UDP socket applications.
- Understand embedded C.
- Work with hardware registers and peripherals.
- Write portable C.
- Write secure C.
- Optimize C programs.
- Design reusable C libraries.
- Build professional C projects.
- Understand modern C23 features.
- Read and understand advanced C code.
- Prepare for C programming interviews.
- Move into operating systems, embedded systems, networking, compilers, databases, or high-performance systems programming.

---

# C Mastery Levels

## Level 1 — Beginner

- Syntax
- Variables
- Data types
- Operators
- Conditions
- Loops
- Functions

## Level 2 — Core C

- Arrays
- Strings
- Pointers
- Structures
- Unions
- Enums
- typedef
- Files

## Level 3 — Intermediate C

- Dynamic memory
- Function pointers
- Preprocessor
- Headers
- Multi-file projects
- Libraries
- Error handling

## Level 4 — Advanced C

- Memory model
- Object representation
- Alignment
- Padding
- Aliasing
- Lifetime
- Linkage
- Undefined behavior
- Atomics

## Level 5 — Systems C

- Linux/POSIX
- Processes
- Threads
- IPC
- File descriptors
- System calls
- Memory mapping
- Sockets

## Level 6 — Specialized C

- Embedded C
- Networking
- Compilers
- Operating systems
- Databases
- High-performance programming
- Security

## Level 7 — Professional C

- API design
- ABI
- Libraries
- Build systems
- Testing
- Static analysis
- Sanitizers
- Profiling
- Optimization
- CI/CD
- Portability
- Security
- Coding standards

## Level 8 — C Mastery

- C23
- ISO C semantics
- Compiler internals
- Linker internals
- ABI
- Advanced concurrency
- Lock-free programming
- Custom allocators
- Compiler development
- OS development
- Embedded firmware
- High-performance systems