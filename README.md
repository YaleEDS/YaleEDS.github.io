# Certificate program in Environmental Data Science (CEDS)
Documentation site for Certificate in Environmental Data Science program

## Development
The documentation is created using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), which recommends using pip for intallation as well as using a [virual environment](https://realpython.com/what-is-pip/#using-pip-in-a-python-virtual-environment).

Use the following steps to contribute to the development of this documentation

0. Clone this repository
```bash
git clone put-link-here
```

1. Create a virtual environment:
```bash
python -m venv venv/
```

2. Activate the environment:
```bash
source venv/bin/activate
```

2. Update `pip` and install `material mkdocs`
```bash
pip install --upgrade pip
pip install mkdocs-material
```

3. Preview the site on a local server
```bash
mkddocs serve
```
4. Make modifications to the source and make sure the site it stable before pushing or submitting a merge request
```bash
git push
```
