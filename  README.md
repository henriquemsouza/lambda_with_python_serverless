# LAMBDA PYTHON LOCAL WITH SERVERLESS


## Requirements:
```sh
npm i -g serverless
```

## Initialize your project by running:

```sh
serverless
```

## Test lambda with:
```sh
serverless invoke local --data '{"body": "{\"email\": \"test@example.com\"}"}' --function main
```

### Response: 
```json
{
    "statusCode": 200,
    "body": "{\"result\": true}"
}
```