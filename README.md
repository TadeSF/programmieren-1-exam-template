# Getting Started

1. Clone this repository
```bash
git clone https://github.com/tadesf/programmieren-1-exam-template.git
```

2. Unlink the repository from the original one
```bash
git remote rm origin
```

3. Create a new repository on GitHub (optional)
```bash
git remote add origin https://github.com/OWNER/REPOSITORY.git

# Verify new remote
git remote -v

git push -u origin master
```

Now you can start working on your project. Your commits will be pushed to your new repository.

# This template includes
- Sample Data (in `./data`)
- Necessary Libraries (in `./lib`)
- Predefined necessary Classes (in `./src`)
- Exam Paper (`./PZ1 - Pruefungsaufgabe.pdf`)

```
.
├── PZ1 - Pruefungsaufgabe.pdf
├── README.md
├── bin
│   ├── Analysis.class
│   ├── EntryManager.class
│   ├── HIVEntry.class
│   └── PopulationEntry.class
├── data
│   ├── GDBx_HIVdata.csv
│   ├── GDBx_HIVdata_four.csv
│   ├── UN_popIndicators.csv
│   └── UN_popIndicators_four.csv
├── lib
│   └── B13 Programmierung 1 xchart 3.8.1.jar
└── src
    ├── Analysis.java
    ├── EntryManager.java
    ├── HIVEntry.java
    └── PopulationEntry.java
```