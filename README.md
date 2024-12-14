## How to Clone the Repository

```bash
git clone https://github.com/SNikhilVashista/ADHD-classification-using-Image-Processing-and-AI-classification
```

## How to Access the Dataset

Download the **NYU Dataset** (~45 GB) using the instructions provided [here](https://fcon_1000.projects.nitrc.org/indi/adhd200/download_scripts/Download_Instructions_ADHD200.pdf).

## Dependencies

The following libraries are required:

- `nibabel`
- `numpy`
- `nilearn`
- `pandas`
- `os`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`

### Installation

To install all dependencies, run:

```bash
pip install nibabel numpy nilearn pandas matplotlib seaborn scikit-learn scipy
```


## Running code

After installing all the dependencies follow each cell in the ipynb file for running samples.
Store the directory path as required in below variables.

  - `$nifti_file_path` - for a single subject: located in cell 3 of ipynb
  -  `$root_dir` - directory path for whole NYU dataset: located in cell 4 of ipynb

