# git pull / git fetch Practice

A small repo used to practice `git fetch` and `git pull`, with a few Python scripts as content.

| File | Contents |
|---|---|
| `calculator.py` | Simple calculator (add, subtract, multiply, divide) |
| `show.py` | Prints sample output |
| `script.py` | Practice script (contains a deliberate typo, `pint(...)`, so it raises a `NameError`) |
| `TODO.md` | Calculator task list |

## Run

```bash
python calculator.py
```

## Practice

```bash
git fetch origin          # download remote changes without merging
git diff main origin/main # inspect them
git pull origin main      # fetch + merge
```
