# Installation of Python Library

## 1. Install mysql connector
In Terminal / Power Shell
```powersheel
pip install mysql-connector-python
```

Example of Python script
```python
mydb = mysql.connector.connect(
  host="localhost",
  user="yourusername",
  passwd="yourpassword"
)
```