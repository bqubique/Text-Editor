# Text-Editor
This program implements a text editor using Linked List and Stack data structures.

Each line of text is saved into a linked list node, which consists of a data portion holding the text and a pointer to the next node of the linked list, which is the next line of the text. The program makes use of Stack data structure to implement the Undo function.

## Features:

- Open an existing file and parse every line to a linked list.

- Save into a file

- Insert text into line n (user given line number and text)

- Delete line n (user given line number)

- Move line n to line m (interchanging two user given lines)

- Replace text in line n (user given line number and text)

- Next page

- Previous page

- Undo (Implemented using Stack data structure) (Slightly buggy)
