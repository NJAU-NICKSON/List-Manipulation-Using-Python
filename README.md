# Python List Operations Tutorial

A comprehensive demonstration of essential Python list methods and operations. This repository contains educational code that walks through the most commonly used list manipulation techniques in Python.

##  What You'll Learn

This tutorial covers the following Python list operations:

- Creating empty lists
- Appending elements
- Inserting elements at specific positions
- Extending lists with other lists
- Removing elements
- Sorting lists
- Finding element indices

## Getting Started

### Prerequisites

- Python 3.x installed on your system
- Basic understanding of Python syntax

### Running the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/NJAU-NICKSON/List-Manipulation-Using-Python.git
   cd python-List-Manipulation-Using-Python
   ```

2. Run the script:
   ```bash
   python list_operations.py
   ```

## Code Walkthrough

The script demonstrates each operation step by step:

```python
# Start with an empty list
my_list = []

# Add elements using append()
my_list.append(10)

# Insert at specific position
my_list.insert(1, 15)

# Extend with another list
my_list.extend([50, 60, 70])

# Remove last element
my_list.pop()

# Sort the list
my_list.sort()

# Find element index
index = my_list.index(30)
```

## Expected Output

When you run the script, you'll see the list transformation at each step:

```
1. Created empty list: []
2. After appending 10, 20, 30, 40: [10, 20, 30, 40]
3. After inserting 15 at second position: [10, 15, 20, 30, 40]
4. After extending with [50, 60, 70]: [10, 15, 20, 30, 40, 50, 60, 70]
5. After removing last element: [10, 15, 20, 30, 40, 50, 60]
6. After sorting in ascending order: [10, 15, 20, 30, 40, 50, 60]
7. Index of value 30: 3
```

## 🔧 Key Methods Explained

| Method | Description | Example |
|--------|-------------|---------|
| `append()` | Adds a single element to the end | `list.append(item)` |
| `insert()` | Inserts element at specific index | `list.insert(index, item)` |
| `extend()` | Adds all elements from another iterable | `list.extend(iterable)` |
| `pop()` | Removes and returns element (last by default) | `list.pop()` or `list.pop(index)` |
| `sort()` | Sorts the list in place | `list.sort()` |
| `index()` | Returns the index of first occurrence | `list.index(item)` |


## Contributing

Feel free to fork this project and submit pull requests for improvements or additional examples!

## License

This project is open source and available for all.

## Author

Created as an educational resource for Python learners.

---

**Star this repository if you found it helpful!**