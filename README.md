# flask-neo4j

## Create a Driver Instance

### connection string

- `neo4j://localhost:7687`
- `neo4j+s://dbhash.databases.neo4j.io:7687`

### Credentials

- basic username/password authentication by passing them as tuple

```python
# Create a new Driver instance
driver = GraphDatabase.driver("neo4j://localhost:7687",
    auth=("neo4j", "neo"))
```
