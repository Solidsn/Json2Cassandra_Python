# cassandra_python_json

Simple script to insert json format to Cassandra

First use
```bash
source venv/bin/activate
```

Syntax
```bash
python cassandra_insert_json.py --host [Host] --port [Port] --keyspace [Keyspace name] --table [Table name] --file [File.json]
```

Example
```bash 
python cassandra_insert_json.py --host 0.0.0.0 --port 3000 --keyspace movies --table artists --file data.json
```
