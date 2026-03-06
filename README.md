## Hackathon Project

## Requirements

- Python 3.10+

### Install dependencies

```bash
python -m pip install -r requirements.txt
```

## Git Workflow

Each teammate works on their own branch and merges into `main` when ready.

| Person | Branch        |
|--------|---------------|
| Arnas  | `dev/arnas`   |
| David  | `dev/david`   |
| Ruchit | `dev/ruchit`  |

```bash
# Create your branch
git checkout -b dev/yourname

# Push your branch
git push -u origin dev/yourname

# When ready to merge into main
git push origin dev/arnas
git switch main
git pull origin main
git merge dev/arnas
git push origin main

# When pulling from main
git switch dev/arnas
git pull origin main
```

## Team

- Arnas
- David
- Ruchit
