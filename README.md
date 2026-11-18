# emasomo-spider

Fetch questions and sources from  quizes and assignments on lms and save on system


## requirments

```python 3.0 > ```

Create virtual environment

```bash
python -m venv .venv

```
Activate virtual environment

```bash
source .venv/bin/activate

```
Install dependancies

```bash
pip install rich 

```
## Run

1. Fetch cookie session token from browser

2. Replace session cookie with the current session cookie

```bash
sed -i 's/^COOKIE=.*/COOKIE=new_value/' emasomo-spider.py

```
new_value should be the new session token 

3. Run

```bash
python3 emasomo-spider.py

```
