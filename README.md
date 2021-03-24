# sqlite-rest

# [THIS IS EXTREMELY PRE-ALPHA-DEV-STAGE]

## What is?
Is a SQLite abstraction to use as a REST API with zero config.

## How to install and use
(Not published yet)
```
pip install sqlite-rest
sqlite-rest database.db
```

## Routes
Return all tables
```
/
```

Get all items from a table
```
/table
```

Get a specific item from table
```
/table/item_id
```

## Next steps
- Add WHERE as query string params
- INSERT data with POST requests
- UPDATE data with PUT requests
- DELETE data with DELETE requests

# License
MIT