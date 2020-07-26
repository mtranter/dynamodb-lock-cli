# Dynamodb Lock CLI


Uses DynamoDB as a lock to manage concurrent processes that should run in isolation.

usage:
```
./dynamodb-lock-cli run-command \
    -l <some-lock-name> \
    -t <your-dynamo-table> \
    "<some command>"
```