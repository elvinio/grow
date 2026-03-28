# Computer Science

## Computer Science Is Not Just Coding

Here is a common misconception worth clearing up immediately: computer science is not the same as knowing how to code. Coding — writing Python scripts, building websites, creating apps — is one tool within a much larger discipline. Computer science is fundamentally about how to think: how to break down complex problems, recognise patterns, design elegant solutions, and reason carefully about what a machine can and cannot do.

Think of it this way. A civil engineer needs to understand physics and materials science, not just how to operate a bulldozer. A computer scientist needs to understand computational thinking, not just how to write a `for` loop. The distinction matters enormously, especially now that AI can generate working code from a plain-English description. What AI cannot replace — at least not yet — is the ability to know whether the code is correct, efficient, and solving the right problem in the first place.

---

## Computational Thinking: The Core Framework

Regardless of whether you are studying O-level Computing or exploring CS for the first time, computational thinking is the foundation everything else rests on. There are four pillars:

**Decomposition** — Breaking a large problem into smaller, manageable parts. If you are building a food delivery app, you do not try to solve the whole thing at once. You break it into: user authentication, restaurant listings, order management, payment, delivery tracking. Each part becomes its own solvable problem.

**Pattern Recognition** — Noticing similarities and regularities. If you have solved a problem before in a slightly different form, you can apply what you already know. This is how experienced programmers see a new problem and immediately think: "This looks like a graph traversal" or "This is basically a sorting problem."

**Abstraction** — Focusing on what matters and hiding what does not. When you call a function in Python, you do not need to know exactly how it works internally — you just need to know what it takes as input and what it returns. Abstraction lets you build on top of layers without getting lost in irrelevant detail.

**Algorithms** — Designing step-by-step procedures that reliably solve a problem. An algorithm is precise, unambiguous, and eventually terminates. Writing an algorithm is different from writing code — it is the thinking that comes before the typing.

These four pillars are not just exam topics. They are a genuinely useful way of approaching problems in any field — project management, scientific research, even writing an essay.

---

## O-Level Computing (Singapore)

MOE's O-level Computing syllabus (subject code 7155) is a well-structured introduction to the discipline. Here is what students cover and why it matters:

**Data Representation**
Numbers, text, images, and sound all need to be stored as binary (0s and 1s) inside a computer. Students learn about binary, denary, and hexadecimal number systems, as well as how characters are encoded using ASCII and Unicode. This content feels abstract at first but becomes essential when you later study networking, databases, or security.

**Algorithms and Programming**
This is the heart of the O-level syllabus. Students write programs in Python and must also be comfortable reading and writing pseudocode — a language-neutral way of describing algorithms. Key concepts include:
- Variables, data types, input/output
- Selection (if/else) and iteration (for/while loops)
- Functions and procedures
- Lists and string manipulation
- File handling basics
- Simple sorting and searching algorithms (bubble sort, linear search, binary search)

**Databases**
Students learn how relational databases work and how to use SQL (Structured Query Language) to create tables, insert data, and run queries. This is genuinely practical knowledge — almost every app and website uses a database behind the scenes.

**Computer Networks**
Basic networking: what the internet is, how data is transmitted in packets, the role of protocols like HTTP and TCP/IP, and introductory cybersecurity concepts. This section helps students understand what is actually happening when they load a website or send a message.

**Hardware and Software**
The logical structure of a computer (CPU, memory, storage), input/output devices, and how operating systems manage resources.

---

## A-Level H2 Computing (Singapore)

The A-level Computing syllabus goes significantly deeper. Students who continue to H2 Computing encounter:

- **Deeper algorithms**: Recursion, dynamic programming, graph algorithms (BFS, DFS, shortest path)
- **Data structures**: Stacks, queues, linked lists, trees, hash tables — understanding when and why to use each
- **Computational complexity**: Big-O notation, understanding why an O(n²) algorithm might be catastrophically slow on large inputs while an O(n log n) solution scales gracefully
- **AI and machine learning concepts**: The syllabus now includes introductory AI — supervised learning, neural network concepts, training and testing models
- **Concurrent and parallel computing**: How modern systems handle multiple tasks simultaneously
- **Software engineering principles**: System design, testing, documentation

H2 Computing is one of the most demanding and rewarding A-level subjects. Students who do well tend to have both strong mathematical reasoning and genuine curiosity about how systems work.

---

## How to Study Computer Science Effectively

CS is a subject where understanding is everything. Students who memorise definitions and code snippets without truly understanding them will hit a wall the moment exam questions present anything unexpected. Here is what actually works:

**Prioritise understanding over memorisation.** Do not memorise bubble sort code — understand why it works. Trace through it manually with a small list. Draw diagrams. If you can explain it to someone who has never heard of it, you understand it.

**Practice pseudocode constantly.** Singapore CS exams regularly ask students to write algorithms in pseudocode. This tests logical thinking, not syntax knowledge. Practice converting your ideas into precise, step-by-step pseudocode even when you are not being examined.

**Do past papers under timed conditions.** MOE's past year papers are invaluable. Work through them section by section. For programming questions, actually run your solutions and test edge cases — what happens with an empty list? With negative numbers? With a single item?

**Trace code by hand.** Before you trust a piece of code, trace through it manually with sample input, tracking the value of each variable at each step. This skill — sometimes called "desk checking" — catches logical errors that syntax checking cannot.

**Build small projects.** The skills you develop writing a simple Python script to sort a list of names or query a database will reinforce exam content far more effectively than re-reading notes.

---

## Approaching CS Exam Questions

When faced with a CS exam question, especially programming or algorithm design questions, use this approach:

1. **Read carefully.** What is the problem actually asking? What are the inputs and outputs?
2. **Decompose.** What sub-problems do you need to solve first?
3. **Plan before you write.** Sketch your algorithm in pseudocode or plain English before writing code.
4. **Consider edge cases.** What if the input is empty? What if there are duplicates?
5. **Review.** Does your solution actually solve the problem as stated? Have you answered all parts of the question?

For MCQ sections, if you are unsure, work backwards: try each answer as if it were true and see which one is consistent with what you know.

---

## Why CS Fundamentals Matter More Than Ever in the Age of AI

It is tempting to think that if AI can write code, there is no point in learning how to code or understand CS fundamentals. This is exactly backwards.

AI tools like GitHub Copilot and ChatGPT can generate code quickly — but they also generate incorrect code, insecure code, and code that solves the wrong problem. The person who can evaluate AI output critically, spot a subtle logical error, understand why a particular data structure is inappropriate for the task, or recognise that a proposed algorithm will not scale — that person is enormously valuable.

Understanding computational thinking also makes you a vastly better user of AI tools. You will know how to structure your prompts as precise problem specifications. You will know when AI output is plausible but wrong. You will understand enough about how machine learning works to have calibrated expectations rather than treating AI as magic.

The fundamentals — algorithms, data structures, computational thinking — are the bedrock. Every new tool, language, and framework is built on top of them.

---

## Resources

- **CS50 (Harvard)** — [cs50.harvard.edu](https://cs50.harvard.edu) — The world's most popular introduction to CS. Free, rigorous, excellent. Available on edX with optional certification.
- **MOE Student Learning Space (SLS)** — Login required. Contains curriculum-aligned lessons, practice questions, and resources keyed directly to the Singapore syllabus.
- **SEAB Past Year Papers** — Available via the SEAB website. Essential for O and A-level exam preparation.
- **BBC Bitesize Computer Science** — Clear, well-explained coverage of concepts like binary, networking, and algorithms. Good for building conceptual understanding before tackling deeper material.
- **Visualgo** — [visualgo.net](https://visualgo.net) — Interactive visualisations of sorting algorithms, data structures, and graph algorithms. Invaluable for understanding how algorithms actually work.
- **Python Tutor** — [pythontutor.com](https://pythontutor.com) — Visualises Python code execution step by step. Perfect for debugging and understanding control flow.
