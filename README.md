# Practical AI Summer Camp Labs

Student lab materials for the UMass Boston AI summer camp.

You do not need to install Python, Git, or any Python libraries. You only need:

- a web browser;
- an internet connection;
- a Google account to save your work.

## Week 1 Labs

| Lab | Topics |
|---|---|
| **Day 1** | Python basics, NumPy, pandas, and one-/two-input linear regression |
| **Day 2** | Lemonade sales, training/validation/test data, MAE, and linear regression |

## Recommended: open a notebook directly in Colab

### Day 1

[![Open Day 1 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cook1e-0707/practicalAI-lab/blob/main/day1/student/week1_day1_yourname.ipynb)

### Day 2

[![Open Day 2 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cook1e-0707/practicalAI-lab/blob/main/day2/student/week1_day2_yourname.ipynb)

1. Click the Colab button for the correct day.
2. Sign in to your Google account if asked.
3. In Colab, select **File → Save a copy in Drive**.
4. Replace `yourname` in the filename with your own name.

Examples:

```text
week1_day1_alex.ipynb
week1_day2_alex.ipynb
```

Work only in your saved copy. Changes made to the notebook opened directly from
GitHub are not saved back to this repository.

## Another way: open the GitHub repository from Colab

Use this method if the direct Colab button does not work.

1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File → Open notebook**.
3. Select the **GitHub** tab.
4. Paste this repository address:

   ```text
   https://github.com/cook1e-0707/practicalAI-lab
   ```

5. Select the `main` branch if Colab asks for a branch.
6. Open the notebook for the correct day:

   ```text
   day1/student/week1_day1_yourname.ipynb
   day2/student/week1_day2_yourname.ipynb
   ```

7. Select **File → Save a copy in Drive**.
8. Replace `yourname` in the filename with your own name.

## Another way: download and upload the notebook

Use this method if you want to download the course files to your computer first.

### Download the repository

1. Open the
   [practicalAI-lab GitHub repository](https://github.com/cook1e-0707/practicalAI-lab).
2. Click the green **Code** button.
3. Click **Download ZIP**.
4. Open the downloaded ZIP file.
5. Find:

   ```text
   practicalAI-lab-main/
   ├── day1/
   │   ├── data/
   │   │   └── moon_crystal_sales.csv
   │   └── student/
   │       └── week1_day1_yourname.ipynb
   └── day2/
       ├── data/
       │   └── lemonade_sales.csv
       └── student/
           └── week1_day2_yourname.ipynb
   ```

### Upload the notebook to Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File → Upload notebook**.
3. Select the Day 1 or Day 2 notebook from the folder you downloaded.
4. After it opens, select **File → Save a copy in Drive**.
5. Replace `yourname` in the filename with your own name.

## Run the notebook

Complete the notebook from top to bottom.

1. Click a code cell.
2. Press **Shift+Enter** or click the ▶ button.
3. Read the output below the cell.
4. Complete only the lines marked `TODO`.
5. Run the cell again after changing the code.
6. Open the hints only when needed.

Do not skip earlier import or data-loading cells. Later code may need variables
created by earlier cells.

## Save and reopen your work

- Confirm that the notebook title contains your name.
- Colab automatically saves the Drive copy while you work.
- To reopen it later, open Google Drive or select
  **File → Open notebook** in Colab.
- Make sure you reopen your Drive copy, not the original GitHub notebook.
- If Colab disconnects, your notebook is still saved, but Python variables may
  be gone. Run your completed cells again from the top.

## Data files

Day 1 uses a small fictional sales table from a crystal shop on the Moon:

```text
day1/data/moon_crystal_sales.csv
```

Day 2 uses fictional lemonade-sales data:

```text
day2/data/lemonade_sales.csv
```

The notebooks download their CSV files from GitHub automatically. You do not
need to upload the CSV files separately when you have an internet connection.

## Common problems

| Problem | What to do |
|---|---|
| I cannot edit the notebook. | Select **File → Save a copy in Drive** and edit the copy. |
| My changes were not saved. | Open the copy in Google Drive and check that your name is in the filename. |
| Python says a variable is not defined. | Run the completed cells above it again, starting from the top. |
| The CSV file does not load. | Check your internet connection, then run the data-loading cell again. |
| I see `None` in the output. | Return to the `TODO` lines in that task and complete them. |
| Colab disconnected. | Reconnect, then rerun your completed cells from the top. |

## Files in this repository

```text
day1/
├── data/
│   ├── README.md
│   └── moon_crystal_sales.csv
└── student/
    └── week1_day1_yourname.ipynb
day2/
├── data/
│   ├── README.md
│   └── lemonade_sales.csv
└── student/
    └── week1_day2_yourname.ipynb
```

## Official help

### Colab and GitHub

- [Google Colab FAQ](https://research.google.com/colaboratory/faq.html)
- [GitHub: Downloading files from a repository](https://docs.github.com/en/get-started/start-your-journey/downloading-files-from-github)

### Python and libraries

- [Python Tutorial](https://docs.python.org/3/tutorial/) — Python basics such as numbers, text, lists, `if`, loops, and functions
- [NumPy Learn](https://numpy.org/learn/) — beginner tutorials for arrays and numerical calculations
- [pandas Getting Started](https://pandas.pydata.org/getting_started.html) — beginner guides for tables, columns, and data analysis
- [scikit-learn Getting Started](https://scikit-learn.org/stable/getting_started.html) — machine-learning tools for training, prediction, data splitting, and model evaluation
- [PyTorch: Learn the Basics](https://docs.pytorch.org/tutorials/beginner/basics/intro.html) — tensors, datasets, models, and training for later lessons
