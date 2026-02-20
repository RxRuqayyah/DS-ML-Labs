# Python Data Structures (Lists, Tuples, and Dictionaries)

---

## 🎯 Objective  

The objective of this lab was to develop a strong understanding of fundamental Python data structures commonly used in data science.

This lab focused on:

- Creating and modifying **lists**
- Understanding the immutability of **tuples**
- Creating and managing **dictionaries**
- Retrieving dictionary **keys** and **values**

These concepts are foundational for organizing, storing, and manipulating structured data in real-world data science workflows.

---

## 🛠️ Tools Used  

- **Python 3**
- **Google Colab**
- **GitHub** for documentation

---

## 📌 Step-by-Step Process  

### 1️⃣ Working with Lists  

- Created a list containing multiple elements.
- Used the `append()`,`insert()`, method to add new items.
- Used the `remove()` method to delete specific elements.
- Printed the updated list to verify changes.

### 2️⃣ Working with Tuples  

- Created a tuple to store fixed values.
- Accessed elements using indexing.
- Observed that tuple elements cannot be modified after creation.

### 3️⃣ Working with Dictionaries  

- Created a dictionary using key-value pairs.
- Updated a dictionary 
- Accessed values using their corresponding keys.
- Extracted keys and values using built-in dictionary methods.

## 💻 Commands Executed  

### List Methods
```python
list_name.append()
list_name.remove()
```

### Tuple Creation
```python
tuple_name = (value1, value2, value3)
```

### Dictionary Methods
```python
dict_name.keys()
dict_name.values()
dict_name.items()
```

---

## 🖼️ Screenshots of Results  

Screenshots of notebook outputs will be stored in the `screenshots/` folder within this repository.

| Activity | Screenshot |
|----------|------------|
| List Operations Output | ![List Output](screenshots/list_output.png) |
| Tuple Output | ![Tuple Output](screenshots/tuple_output.png) |
| Dictionary Keys & Values Output | ![Dictionary Output](screenshots/dictionary_output.png) |

---

## 🔍 Key Observations / Lessons Learned  

- Lists are mutable and allow dynamic modification using methods like `append()` and `remove()`.
- Tuples are immutable, making them suitable for storing fixed or constant data.
- Dictionaries organise data in key-value pairs, which is highly efficient for structured data storage.
- Methods such as `.keys()`, `.values()`, and `.items()` are essential for accessing and iterating through dictionary data.
- Mastery of these data structures forms the foundation for more advanced data science tasks such as data cleaning, transformation, and analysis.
