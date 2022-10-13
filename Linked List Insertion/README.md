# Linked List Insertion

Linked List Insertion is a web application that allows you to insert a node at a particular position in a linked list.

## Challenge

Create a function that takes in a linked list, a value, and a position. The function should insert a node with the given value at the given position in the linked list.

## Approach & Efficiency

The approach I took was to create a function that takes in a linked list, a value, and a position. The function should insert a node with the given value at the given position in the linked list. I created a new node with the given value and then traversed the linked list to the given position. I then set the next of the new node to the next of the node at the given position and then set the next of the node at the given position to the new node.

## Rquired

- [x] Create a Node class that has properties for the value stored in the Node, and a pointer to the next Node.
- [x] Within your LinkedList class, include a head property. Upon instantiation, an empty Linked List should be created.
- [x] This object should be aware of a default empty value assigned to head when the linked list is instantiated.
- [x] Define a method called insert which takes any value as an argument and adds a new node with that value to the head of the list with an O(1) Time performance.

## Installation

```bash
git clone https://github.com/sauravhathi/linked-list-javascript.git
```

## Usage

```bash
cd linked-list-insertion
```

```bash
open index.html
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
