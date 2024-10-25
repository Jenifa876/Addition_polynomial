# Addition_polynomial
**Overview**
This C++ program allows users to input two polynomials and computes their addition using a linked list data structure. Each polynomial is represented as a linked list of nodes, where each node contains the coefficient and exponent of a term.

**Features**
Input two polynomials from the user.
Each polynomial can have multiple terms.
The program adds the two polynomials and displays the result.
The polynomials are represented as linked lists, allowing for dynamic memory allocation.
**Classes**
Node
The Node class represents a single term in a polynomial. It contains:

coeff: The coefficient of the term.
expo: The exponent of the term.
next: A pointer to the next node in the linked list.
**Functions**
Node* mulpoly(Node* poly1, Node* poly2): This function takes two polynomial linked lists and returns a new linked list that represents the sum of the two polynomials.

void print(Node* poly): This function takes a polynomial linked list and prints it in a human-readable format.
