# Calculator

A basic Calculator made using tkinter and Python
The current version uses the Button class from tkmacosx rather than the default tkinter buttons.
This leads to better and non-broken button-styling on macos.

![GIF-of-Calculator](https://user-images.githubusercontent.com/62864373/110453458-2ec17680-80ec-11eb-8ec8-57ee183960d9.gif)

## How to run this locally?:
- `pip install -r requirements.txt`
- `python calc-gui.py`

## How to contribute to this project?:
- Fork this repo
- Clone your fork of this repo:
  ```
  git clone https://github.com/<your-username>/Calculator
  ```
- Add this repo as upstream:
  ```
  git remote add upstream https://github.com/Vyvy-vi/Calculator
  ```
- Make a new Branch before making changes:
  ```
  git checkout -b <your-branch-name>
  ```
- Make the changes
- Stage the changes and commit the changes:
  ```
  git add <file1, file2>
  git commit -m 'meaningful-commit-message'
  ```
- Push the changes to your repo:
  ```
  git push origin
  ```
- Sync your fork with upstream:
  ```
  git fetch upstream
  git merge upstream/master
  git push -f
  ```
- Open a PR and wait for review and mergure of changes : )
