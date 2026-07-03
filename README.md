# States Quiz Generator

Generates **US state capital quizzes** with shuffled multiple-choice questions and matching answer cheat sheets — perfect for classroom drills or self-study.

![Python](https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white)

## Features

- All **50 US states + capitals** in `states.py`
- Randomized **4-option multiple choice** per question
- Outputs `quizN.txt` and `cheatsheetN.txt` per run
- Shell wrapper `quizgame.sh` for quick generation

## Quick start

```bash
python3 quizgame.py
# or
bash quizgame.sh
```

Check the generated `.txt` files in the project directory.

## Project layout

```
quizgame.py    # Quiz generator logic
states.py      # State → capital dictionary
quizgame.sh    # Convenience runner
```

## Example output

Each quiz file contains numbered questions with four capital choices; the cheat sheet lists correct answers for the teacher.

---

[malimba](https://github.com/malimba)
