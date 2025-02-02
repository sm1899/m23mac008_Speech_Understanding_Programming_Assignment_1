---

### **Speech Understanding Programming Assignment**

This repository contains the code and reports for Speech Understanding Programming Assignment 1.

---

## **Project Structure**
```
m23mac008_Speech_Understanding_Programming_Assignment_1/
│
├── submodules/
│   ├── audio_classification/   # Submodule for audio classification task
│   └── song_analysis/          # Submodule for song analysis task
│
├── m23mac008_report.pdf        # Contains the report for this assignment
├── README.md                   # Project documentation
└── .gitmodules                 # Tracks submodule URLs
```

---

## **Submodules**
### 1. **[audio_classification](https://github.com/sm1899/audio_classification)**
   - This submodule contains the code and results for **Question 2, Task A**.

### 2. **[song_analysis](https://github.com/sm1899/song_analysis)**
   - This submodule contains the code and results for **Question 2, Task B**.

---

## **Getting Started**

1. **Clone the repository with submodules:**

```bash
git clone --recurse-submodules https://github.com/your_username/m23mac008_Speech_Understanding_Programming_Assignment_1.git
```

2. **Navigate into the project:**

```bash
cd m23mac008_Speech_Understanding_Programming_Assignment_1
```

3. **Update and initialize submodules (if not done already):**

```bash
git submodule update --init --recursive
```