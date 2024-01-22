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
    - With GitHub Website
        Make sure to leave the checkbox for initializing the repository with a README and .gitignore unchecked.
    - With Github CLI (Command Line Interface)
        ```bash
        # If you use github cli for the first time, you have to login first
        gh auth login

        # Create a new repository – Dont forget to replace OWNER with your GitHub username
        gh repo create OWNER/programmieren-1-exam --private --source=. --remote=origin
        ```

4. Link the local repository to the remote one on GitHub (optional)
    ```bash
    # Dont forget to replace OWNER with your GitHub username
    git remote add origin https://github.com/OWNER/programmieren-1-exam.git

    # Verify new remote
    git remote -v

    # Push changes to new remote
    git push -u origin main
    ```

Now you can start working on your project. Your commits will be pushed to your new repository.

# This template includes
- Sample Data (in `./data`)
- Necessary Libraries (in `./lib`)
- Predefined necessary Classes (in `./src`)
- Exam Paper (`./PZ1 - Pruefungsaufgabe.pdf`)
- VSCode Settings, if you want to use VSCode as your IDE (`./.vscode`)

```
.
├── PZ1 - Pruefungsaufgabe.pdf
├── README.md
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
