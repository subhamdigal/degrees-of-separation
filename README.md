# Degrees of Separation

This Python project determines how many “degrees of separation” apart two actors are, based on the movies they've starred in.

## 📁 Files

- `degrees.py`: Main program using Breadth-First Search to find the shortest connection between two actors.
- `util.py`: Includes Node and Frontier classes to manage the search algorithm.
- `people.csv`, `movies.csv`, `stars.csv`: Datasets used to form actor/movie relationships.

## 🚀 How to Run

Place the three CSV files in a folder (e.g., `large/`), then run:

```bash
python degrees.py large


📦 Sample Output

Name: Emma Watson
Name: Jennifer Lawrence
3 degrees of separation.
1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix
2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us
3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class
