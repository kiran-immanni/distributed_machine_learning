# Instructions to run Distributed Computing for Sentimental Analysis.ipynb
Certainly! Here are combined instructions to run the Jupyter Notebook from the GitHub repository and keep the Kaggle dataset in the same folder:

### Step 1: Open Anaconda Navigator

Open the Anaconda Navigator application.

### Step 2: Launch Jupyter Notebook

In the Anaconda Navigator interface, find Jupyter Notebook and click the "Launch" button.

### Step 3: Open a Terminal within Jupyter Notebook

In the Jupyter Notebook interface, click on "New" and select "Terminal" to open a new terminal within the Jupyter environment.

### Step 4: Clone the GitHub Repository and Download the Dataset

In the terminal, use the following commands to clone the GitHub repository and download the Kaggle dataset:

```bash
git clone https://github.com/kiran-immanni/distributed_machine_learning.git
cd distributed_machine_learning
wget https://www.kaggle.com/datasets/kazanova/sentiment140/download -O sentiment140.zip
unzip sentiment140.zip
```

### Step 5: Open the Jupyter Notebook

Now, you can open the Jupyter Notebook from the terminal. Run the following command:

```bash
jupyter notebook "Distributed Computing for Sentimental Analysis.ipynb"
```

### Step 6: Adjust the Notebook Code

In your Jupyter Notebook, make sure the code that loads the dataset reflects the correct path to the dataset. Update the path if needed.

```python
import pandas as pd

# Assuming the dataset file is named "sentiment140.csv"
dataset_path = "sentiment140.csv"  # Adjust if needed
df = pd.read_csv(dataset_path, encoding='latin-1')
```

### Step 7: Run the Notebook

Run your Jupyter Notebook cells. If everything is set up correctly, the notebook should be able to access the dataset in the specified location.

### Note:

Make sure to keep the dataset files and the Jupyter Notebook file in the same directory or adjust the path in the notebook accordingly. If your notebook uses relative paths, it should work seamlessly.
