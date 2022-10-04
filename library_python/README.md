# Installation of Python Library

## 1. Install mysql connector
```powersheel
pip install mysql-connector-python
```

```python
mydb = mysql.connector.connect(
  host="localhost",
  user="yourusername",
  passwd="yourpassword"
)
```