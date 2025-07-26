# quiz-runner-in-go

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

# How it works?

You give a csv file full of questions answers in (question, answer) format.
Give the path of the csv file using `--csv` flag.
Done. Play the quiz and get your score.

Need a timer?
Set desired duration with `--limit` flag.

```sh
--csv       # specify the required csv file
--limit     # set quiz duration
```
