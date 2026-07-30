# Practical AI Summer Camp Labs

Student lab materials for the UMass Boston AI summer camp.

You do not need to install Python, Git, or any Python libraries. You only need:

- a web browser;
- an internet connection;
- a Google account to save your work.

## Week 1 Labs

| Lab | Topics |
|---|---|
| **Day 1** | Python basics, NumPy, pandas, data splitting, and one-/two-input linear regression |
| **Day 2** | Supervised learning with Linear Regression, Decision Tree, KNN, and a small Neural Network |
| **Day 3** | Unsupervised learning with K-Means and Recursive K-Means |
| **Day 4** | Tiny large language model: tokenization, next-token training, and text generation |

## Recommended: open a notebook directly in Colab

### Day 1

[![Open Day 1 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cook1e-0707/practicalAI-lab/blob/main/day1/student/week1_day1_yourname.ipynb)

### Day 2

[![Open Day 2 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cook1e-0707/practicalAI-lab/blob/main/day2/student/week1_day2_yourname.ipynb)

### Day 3

[![Open Day 3 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cook1e-0707/practicalAI-lab/blob/main/day3/student/week1_day3_yourname.ipynb)

### Day 4

[![Open Day 4 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cook1e-0707/practicalAI-lab/blob/main/day4/student/week1_day4_yourname.ipynb)

1. Click the Colab button.
2. Sign in to your Google account if asked.
3. In Colab, select **File → Save a copy in Drive**.
4. Replace `yourname` in the filename with your own name.

Example:

```text
week1_day1_alex.ipynb
week1_day2_alex.ipynb
week1_day3_alex.ipynb
week1_day4_alex.ipynb
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
6. Open the student notebook for the correct day:

   ```text
   day1/student/week1_day1_yourname.ipynb
   day2/student/week1_day2_yourname.ipynb
   day3/student/week1_day3_yourname.ipynb
   day4/student/week1_day4_yourname.ipynb
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
   │   │   └── bluebikes_june_2025.csv
   │   └── student/
   │       └── week1_day1_yourname.ipynb
   ├── day2/
   │   ├── data/
   │   │   └── lemonade_sales.csv
   │   └── student/
   │       └── week1_day2_yourname.ipynb
   ├── day3/
   │   └── student/
   │       └── week1_day3_yourname.ipynb
   └── day4/
       ├── data/
       │   ├── food_knowledge_corpus.txt
       │   └── verified_food_knowledge.csv
       ├── model/
       │   └── day4_tinygpt_checkpoint.pt
       └── student/
           └── week1_day4_yourname.ipynb
   ```

### Upload the notebook to Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File → Upload notebook**.
3. Select the notebook for the correct day:

   ```text
   week1_day1_yourname.ipynb
   week1_day2_yourname.ipynb
   week1_day3_yourname.ipynb
   week1_day4_yourname.ipynb
   ```
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

Day 1 uses 30 days of real Cambridge Bluebikes trip counts and Boston
temperature observations from June 2025:

```text
day1/data/bluebikes_june_2025.csv
```

Each notebook includes the GitHub raw-data URL. You can use that URL when you
have an internet connection, or upload the CSV and enter its filename instead.
See `day1/data/README.md` for the Cambridge Open Data and NOAA sources.

Day 2 uses 72 fictional lemonade-stand days created for teaching:

```text
day2/data/lemonade_sales.csv
```

The columns describe temperature, whether it is a weekend, whether it rains,
and the number of cups sold. The data includes random variation so students can
compare Linear Regression, Decision Tree, KNN, and Neural Network predictions.
See `day2/data/README.md` for the column descriptions and teaching-data note.

Day 3 uses several kinds of data so students can see clustering in different
forms:

- coordinate datasets generated inside the notebook;
- the handwritten-digits dataset and a sample flower image included with
  scikit-learn;
- the public Free Spoken Digit Dataset, which the notebook downloads when the
  audio case is first run.

The Day 3 notebook needs an internet connection for the spoken-digit download.
In hosted Colab, students may allow microphone access to record their own voice
or use the provided dataset fallback. Record only yourself. Colab files stored
under `/content/` are temporary and disappear when the runtime is deleted or
reset unless you intentionally save them elsewhere.

Day 4 starts from 26 food-knowledge records supported by official FDA,
USDA/FSIS, USDA MyPlate, and NIH ODS sources:

```text
day4/data/verified_food_knowledge.csv
```

The generated training corpus repeats those verified records in deterministic
shuffled orders:

```text
day4/data/food_knowledge_corpus.txt
```

The notebook trains an approximately 0.43-million-parameter character-level
decoder-only
Transformer for a short time, then loads a checkpoint trained for 4,000 steps:

```text
day4/model/day4_tinygpt_checkpoint.pt
```

The notebook follows one focused path: text, character and BPE tokenization,
token IDs, shifted next-token pairs, TinyGPT training, loss, parameter updates,
and generated text. Generated food text is not guaranteed factual. Training and
generation use separate Markdown pipeline diagrams in their corresponding
sections, so Colab does not need to download a separate image.
Day 4 automatically uses a CUDA GPU when available and otherwise follows a
shorter CPU path. The notebook checks required packages and uses pip to install
only missing ones.

For local testing, open the repository as the working folder and run the Day 4
notebook from top to bottom. Its loaders first search these repository files:

```text
day4/data/food_knowledge_corpus.txt
day4/model/day4_tinygpt_checkpoint.pt
```

The output should begin with `local file:` for each of these two resources.
When no local file is found, the same cells use the GitHub raw-data URL, which
is the normal path in Colab. The training and generation diagrams are stored
directly in notebook Markdown, while tokenization and loss figures are produced
by notebook code. No separate pipeline image is required.

## Common problems

| Problem | What to do |
|---|---|
| I cannot edit the notebook. | Select **File → Save a copy in Drive** and edit the copy. |
| My changes were not saved. | Open the copy in Google Drive and check that your name is in the filename. |
| Python says a variable is not defined. | Run the completed cells above it again, starting from the top. |
| The CSV file does not load. | Check your internet connection, then run the data-loading cell again. |
| The Day 3 audio data does not load. | Check the internet connection and rerun the audio setup cell. The first run may take longer because it installs or downloads files. |
| Colab cannot use my microphone. | Allow microphone access when asked, or continue with the dataset recording used as a fallback. |
| Day 4 says the selected device is CPU. | Continue normally. The notebook automatically uses a shorter live-training run and still loads the prepared checkpoint. |
| Day 4 cannot download the text corpus. | Download `day4/data/food_knowledge_corpus.txt`, rerun the data cell, and select the file when the upload button appears. |
| Day 4 cannot load the prepared checkpoint. | Continue with the short live-trained model. Its text may be less clear, but the tokenizer, training, and generation pipeline still works. |
| I see `None` in the output. | Return to the `TODO` lines in that task and complete them. |
| Colab disconnected. | Reconnect, then rerun your completed cells from the top. |

## Files in this repository

```text
day1/
├── data/
│   ├── README.md
│   └── bluebikes_june_2025.csv
└── student/
    └── week1_day1_yourname.ipynb

day2/
├── data/
│   ├── README.md
│   └── lemonade_sales.csv
└── student/
    └── week1_day2_yourname.ipynb

day3/
└── student/
    └── week1_day3_yourname.ipynb

day4/
├── data/
│   ├── README.md
│   ├── food_knowledge_corpus.txt
│   └── verified_food_knowledge.csv
├── model/
│   └── day4_tinygpt_checkpoint.pt
└── student/
    └── week1_day4_yourname.ipynb
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
- [librosa Documentation](https://librosa.org/doc/latest/) — tools for loading audio and creating sound features
- [PyTorch: Learn the Basics](https://docs.pytorch.org/tutorials/beginner/basics/intro.html) — tensors, datasets, models, and training for later lessons
- [tiktoken](https://github.com/openai/tiktoken) — byte-pair encoding and subword tokenization
