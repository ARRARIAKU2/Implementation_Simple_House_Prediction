# Implementation_Simple_House_Prediction

#### How to run this app in a local server using [conda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/environments.html) :
1. First, install [`conda`](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) on your device. I personally recommended the _***Miniconda***_
2. Clone this repository and go to the repo directory
   - `git clone https://github.com/ARRARIAKU2/Implementation_Simple_House_Prediction.git`
   - `cd Implementation_Simple_House_Prediction`
3. Create conda environment with the configuration file `flask.yml`
   - `conda env create -f flask.yml`
4. Activate the conda environment
   - `conda activate flask`
5. Run **main.py**
   - `python app.py`
6. It will run on `http://localhost:5000` or `http://127.0.0.1:5000` by default
7. Create an account (just random data) and then login to access the main page. After logged in, you can upload the heart image scan and get the segmentation result.

> Note : if the .h5 file is corrupted while cloning the repository, please do a manual download that file :)
