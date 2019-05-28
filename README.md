# Minimaldb
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FZAZPRO%2Fminimaldb.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FZAZPRO%2Fminimaldb?ref=badge_shield)


Minimaldb is a very simple document oriented database.

## Supported Python Versions
Minimaldb is tested with Python 3.7

## Installation
From PyPi:
```
$ pip install minimaldb
```

## Example Code
```python
from minimaldb import MinimalDB

db = MinimalDB("database_name.db")

# Setting a value
db.set("key_name", value)

# Getting a value
db.get("key_name")

# Deleting a value
db.delete("key_name")

# Updating a value
db.update("key_name", value)


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FZAZPRO%2Fminimaldb.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FZAZPRO%2Fminimaldb?ref=badge_large)