# Resto Web API

Repositoy contains code of API for the Resto App.

## **Prerequisites**
---

- Python 3 (or above).

- Python Package manager: `pip`, `conda` or other.

- *Recommended*: `virtualenv`, `conda` or other work development environment manager.


## **Use Guide**
---

This guide is done using `MacOs`, `Python 3.8`, `pip` and `virtualenv`.  

1. Download or clone git, and enter directory:
```ssh
git clone https://github.com/nicosoto0/resto_api.git
cd resto_api
```

2. Optional/Recommended: Create and Activate virtualenv for to start development
```ssh
virtualenv -p python3 resto_api_env
source resto_api_env/bin/activate
```
(If you use a virtualenv with a different name, then remember to add it to  .gitignore)

3. Install requirements:
```ssh
pip install -r requirements.txt
```

4. Start running API Analysis
```shh
python launcher.py
```
