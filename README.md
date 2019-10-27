# JsonFile2Cassandra

Simple script to insert json format to Cassandra with python

First use
```bash
source venv/bin/activate
```

Syntax
```bash
python Json2Cassandra.py [-host <host>] [-port <port>] [-keyspace <keyspace>] [-table <table>] [file]
```

Example
```bash 
python Json2Cassandra.py -host 0.0.0.0 -port 3000 -keyspace movies -table artists -file data.json
```
