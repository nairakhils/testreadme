# idresearch <img src="https://github.com/nairakhils/testreadme/blob/main/idrlogo1.png" width="200" height="200">
## Documentation


[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=latest)]([http://ansicolortags.readthedocs.io/?badge=latest](https://idresearch.readthedocs.io/en/latest/idresearch.html))
[![GitHub contributors](https://img.shields.io/github/contributors/Naereen/badges.svg)](https://GitHub.com/Naereen/badges/graphs/contributors/)

idresearch is a package aimed to help researchers help identify relevant papers and see the development trend in that particular subfield. The package will provide a list of recommended papers and their abstracts. Additionally, it also allows the user to summarize the abstract, find common keywords from the abstract and save the recommended papers in csv format.

- Semantic Scholar API for paper recommendations
- spacy models for Natural Lanugage Processing
- ✨Allows query from websites like arxiv, semantic scholar, biorxiv✨


## Installation

**idsearch** requires additional direct dependencies to work.

Install the dependencies before installing idsearch (https://spacy.io/models/en#en_core_web_md).

```sh
python -m spacy download en_core_web_md
```

After installing the **en_core_web_md** spacy model...

```sh
pip install idresearch
```
