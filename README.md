# 🧠 Quiz Runner in Go

A simple terminal-based quiz app written in Go.  
You provide a CSV file with questions and answers, and it quizzes you interactively — optionally with a time limit!

---

## 🚀 Features

- Read questions and answers from a CSV file
- Prompt questions one by one in the terminal
- Optional countdown timer using the `--limit` flag
- Displays final score after quiz or when time runs out

---

## 📦 Prerequisites

- Go installed (version 1.13 or higher recommended)

---

## 📂 CSV Format

Your CSV file should have the following format:

```csv
question,answer
5+5,10
7-3,4
capital of France,Paris

```

# Build

clone the repository

```sh
git clone https://github.com/Rai321han/quiz-runner-in-go.git .
```

build the project & run

```sh
go build .              # build the binary
./quiz-runner --flag    # execute binary
```

flags

```sh
--csv="csv file path"   # specify csv file path
--limit=duration        # set quiz duration
```
