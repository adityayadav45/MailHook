## To create a virtual environment (Optional)
```
python -m venv myenv
myenv\Scripts\activate     # For Windows
```
## To install all dependancies

```
pip install --upgrade pip
pip install -r requirements.txt
```

## To run the code 

```
uvicorn main:app --reload
uvicorn main:app --host 0.0.0.0 --port 80
```
- **Note:-** This above command should be run in proper main.py directory or specify path 
---