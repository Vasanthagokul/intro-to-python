# Python Introduction Lab - Completion Status

## ✅ Completed Files

### Core Structure
- [x] **README.md** - Complete setup instructions, learning objectives, 8-notebook structure
- [x] **requirements.txt** - Jupyter, numpy, pandas, matplotlib
- [x] **.gitignore** - Python, Jupyter, venv exclusions
- [x] **data/students.csv** - Sample CSV for file operations exercises
- [x] **data/sample.txt** - Sample text file for reading/writing practice

### Jupyter Notebooks (Completed: 3/8)
- [x] **01_Python_Basics.ipynb** (30-35 min)
  - Variables, data types (int, float, str, bool)
  - Operators (arithmetic, comparison, logical)
  - Type conversion and f-strings
  - User input
  - 4 practice exercises with solutions
  
- [x] **02_Control_Flow.ipynb** (30-35 min)
  - If/elif/else statements
  - For loops with range() and enumerate()
  - While loops
  - Break and continue
  - Nested loops
  - 6 practice exercises with solutions
  
- [x] **03_Functions.ipynb** (30-35 min)
  - Defining and calling functions
  - Parameters and return values
  - Default parameters
  - Variable scope (local vs global)
  - Docstrings and lambda functions
  - 6 practice exercises with solutions

---

## 📝 Remaining Notebooks to Create (5/8)

### 04_Data_Structures.ipynb (30-35 min)
**Topics to Cover:**
- Lists: creation, indexing, slicing, methods (append, extend, insert, remove, pop, sort, reverse)
- List comprehensions [x for x in range(10) if x % 2 == 0]
- Dictionaries: creation, accessing keys/values, methods (get, keys, values, items, update, pop)
- Dictionary comprehensions
- Tuples: immutability, packing/unpacking, use cases
- Sets: creation, operations (union, intersection, difference, symmetric_difference)
- Set comprehensions
- When to use each data structure

**Practice Exercises (6-8):**
1. List manipulation: add, remove, sort students
2. Find duplicates using sets
3. Build a dictionary from two lists (zip)
4. Count word frequency in a sentence
5. Merge two dictionaries
6. Tuple unpacking in loops
7. Set operations on two lists
8. Nested dictionary (student records)

---

### 05_File_Operations.ipynb (25-30 min)
**Topics to Cover:**
- Opening files: open() function and modes ('r', 'w', 'a', 'r+')
- Reading files: read(), readline(), readlines()
- Writing files: write(), writelines()
- with statement for automatic file closing
- Reading CSV files manually (split by comma)
- Writing CSV files
- File paths (relative vs absolute)
- Error handling with try/except for FileNotFoundError

**Practice Exercises (5-6):**
1. Read sample.txt and print line by line
2. Count lines, words, characters in a file
3. Write user input to a file
4. Read students.csv and calculate average marks
5. Create a new CSV from filtered data
6. Append new data to existing file

---

###06_String_Processing.ipynb (25-30 min)
**Topics to Cover:**
- String indexing and slicing
- String methods: upper(), lower(), strip(), split(), join(), replace()
- String formatting: %, .format(), f-strings
- Checking string properties: isdigit(), isalpha(), startswith(), endswith()
- Finding substrings: find(), index(), count()
- String concatenation and repetition
- Escape characters and raw strings

**Practice Exercises (6-7):**
1. Reverse a string
2. Count vowels and consonants
3. Check if string is palindrome
4. Extract email username and domain
5. Format phone numbers
6. Remove punctuation from text
7. Create acronym from phrase

---

### 07_Practice_Problems.ipynb (40-50 min)
**Mixed exercises - Easy to Medium:**

**Easy (15-20 min):**
1. **Temperature Converter**: Celsius ↔ Fahrenheit with menu
2. **List Statistics**: Find min, max, average, median from list
3. **Simple Calculator**: Add, subtract, multiply, divide with menu
4. **Password Validator**: Check length, has digit, has uppercase

**Medium (25-30 min):**
5. **Student Grade Manager**:
   - Store student names and marks in dictionary
   - Calculate average, find topper
   - Display sorted list by marks
   
6. **Word Frequency Counter**:
   - Read text from file or input
   - Count frequency of each word
   - Display top 10 most common words
   
7. **Shopping Cart**:
   - Add items with prices to dictionary
   - Calculate total with tax
   - Apply discount codes
   - Display receipt

8. **Number Guessing Game**:
   - Random number between 1-100
   - User gets 7 attempts
   - Provide hints (higher/lower)
   - Track number of games won

---

### 08_Advanced_Challenges.ipynb (40-50 min)
**Hard Problems (2-3 challenges):**

**Challenge 1: Library Management System (20-25 min)**
- Store books in list of dictionaries
- Functions: add_book(), search_book(), issue_book(), return_book()
- Track available vs issued books
- Display all books in formatted table
- Save/load data from file

**Challenge 2: Text Analysis Tool (15-20 min)**
- Read file and perform:
  - Count total words, unique words
  - Find longest word
  - Calculate average word length
  - List words by frequency
  - Find all words starting with specific letter
- Display results in formatted report

**Challenge 3 (Bonus): Simple Contact Manager (15-20 min)**
- Store contacts: name, phone, email in dictionary
- Functions: add, search, update, delete, display_all
- Input validation (phone format, email format)
- Save to CSV, load from CSV
- Menu-driven interface

---

## 🎯 Total Time Breakdown
- Part 1 (Foundations): 01-02 = 60-70 min ✅
- Part 2 (Building Blocks): 03-04 = 60-70 min (03 ✅, 04 pending)
- Part 3 (Practical): 05-06 = 50-60 min (both pending)
- Part 4 (Challenges): 07-08 = 80-100 min (both pending)

**Total: 250-300 minutes (4-5 hours)**

---

## 📋 Next Steps

### To Complete the Repo:

1. **Create Notebook 04** - Data Structures (lists, dicts, tuples, sets)
2. **Create Notebook 05** - File Operations (read/write files, CSV)
3. **Create Notebook 06** - String Processing (methods, formatting)
4. **Create Notebook 07** - Practice Problems (easy to medium)
5. **Create Notebook 08** - Advanced Challenges (2-3 hard problems)

### Each Notebook Should Include:
- Clear learning objectives at top
- Estimated time
- Step-by-step explanations with examples
- Code cells ready to run
- Practice exercises (6-8 for topics, 4-8 for challenges)
- Solutions in collapsible `<details>` sections
- "Congratulations" section at end
- Link to next notebook

### Formatting Standards:
- Use markdown headers (##, ###)
- Code comments for clarity
- Consistent naming conventions
- F-strings for output formatting
- Include edge cases in examples

---

## 🚀 Quick Start for Students

Once all notebooks are complete:

```bash
# Clone repo
git clone https://github.com/vasanthagokul/python-intro-labs
cd python-intro-labs/intro-to-python

# Setup environment
python -m venv venv
venv\Scripts\activate  # Windows
pip install -r requirements.txt

# Start Jupyter
jupyter notebook

# Open 01_Python_Basics.ipynb and begin!
```

---

## 📊 Progress Checklist

Students can track progress:
- [ ] 01_Python_Basics (✅ Ready)
- [ ] 02_Control_Flow (✅ Ready)
- [ ] 03_Functions (✅ Ready)
- [ ] 04_Data_Structures (📝 To create)
- [ ] 05_File_Operations (📝 To create)
- [ ] 06_String_Processing (📝 To create)
- [ ] 07_Practice_Problems (📝 To create)
- [ ] 08_Advanced_Challenges (📝 To create)

---

**Session Ready!** The first 3 notebooks (90-105 min of content) are complete and tested. Students can start learning immediately while you complete notebooks 4-8.
