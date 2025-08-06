## Setup and Installation

Follow these steps to set up the local environment and run the project.

**1. Clone the Repository**
```bash
git clone <your-repository-url>
cd ASD_Detection_Framework
```

**2. Create and Activate a Virtual Environment**
It is highly recommended to use a virtual environment to manage project dependencies.
```bash
# Create the virtual environment
python -m venv venv

# Activate the environment
# On Windows:
.\venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

**3. Install Dependencies**
The required libraries are listed in the `requirements.txt` file.
```bash
pip install -r requirements.txt
```

**4. Download the Datasets**
This study uses three publicly available datasets from the UCI Machine Learning Repository. Please download them and place them in their respective folders (`children_dataset/`, `adolescent_dataset/`, `adult_dataset/`).

* **Children:** [Download Link](https://archive.ics.uci.edu/dataset/419/autistic+spectrum+disorder+screening+data+for+children)
* **Adolescent:** [Download Link](https://archive.ics.uci.edu/dataset/420/autistic+spectrum+disorder+screening+data+for+adolescent)
* **Adult:** [Download Link](https://archive.ics.uci.edu/dataset/426/autism+screening+adult)

## How to Run

The analysis for each dataset is contained within a separate Jupyter Notebook.

1.  **Activate the Virtual Environment** (if not already active).
    ```bash
    source venv/bin/activate
    ```
2.  **Launch Jupyter Notebook** from the root project directory.
    ```bash
    jupyter notebook
    ```
3.  **Navigate and Run:** In the Jupyter interface that opens in your browser, navigate to one of the dataset folders (e.g., `children_dataset/`).
4.  Open the corresponding notebook (e.g., `ASD_Analysis_Child.ipynb`).
5.  Run all cells in the notebook to execute the full analysis pipeline and view the results.
6.  Repeat the process for the other two datasets.
