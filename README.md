# Clustering Analysis of English Demographic Data

Repository for my summer bursary scheme with the School of Mathematics at the University of Leeds, summer 2025. 

The aim of this project is to use cluster analysis techniques and spatial mapping to investigate how levels of deprivation vary across England.

This project uses the most recent official statistics (June 2025) for English Indices of Deprivation (IoD), published by the Ministry of Housing, Communities & Government (MHCG) in September 2019.

The link to the deployed website is here: https://estubbings.github.io/summer-bursary-project 



## Licensing 

Adapted from data from the Office for National Statistics licensed under the Open Government Licence v.3.0.

This project is built using Jupyter Book and deployed with GitHub Pages.



## Contributing guidance

To contribute to this project:

1. Fork the repository
2. `git clone` to clone the repository to your local machine
3. Create a Python virtual environment and install the dependencies via `pip install -r requirements.txt`
4. Add your virtual environment to IPython so that you can develop in Jupyter Notebooks / JupyterLab: `ipython kernel install --name=<env name>`
5. Make your local modifications and check you can build the book using `jupyter-book build cluster-analysis`
6. Commit and push your changes to the remote
7. Open a pull request to merge your changes


## 🚀 Setup Instructions

This project uses **Git Large File Storage (Git LFS)** to manage large files such as `.geojson` datasets and Jupyter notebooks.

### 1. Install Git LFS (one-time setup per system)

If you haven’t already, install Git LFS:

```bash
# macOS
brew install git-lfs

# Debian/Ubuntu
sudo apt install git-lfs

# Windows (use Git Bash or download from https://git-lfs.github.com/)
git lfs install
```

Then initialise:
```bash
git lfs install
```

### 2. (Optional) Track Files within repository

Go to your git repository and use the commands:
``` bash
git lfs track "*.geojson"
git lfs track "*.ipynb"
```





## Important documentation

- [GeoPandas](https://geopandas.org/)
- [Git](https://git-scm.com/)
- [GitHub](https://docs.github.com/en/get-started)
- [Jupyter](https://docs.jupyter.org/)
- [JupyterBook](https://jupyterbook.org/)
- [Git Large File Storage](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-git-large-file-storage#) 



## Data sources
- [MHCLG & CommunitiesOpenData - Indices of Multiple Deprivation (IMD) 2019](https://communitiesopendata-communities.hub.arcgis.com/search?q=IMD)

