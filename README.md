# flask-lambda

# Install serverless package
```
npm install serverless -g
npm i
```


# Install Flask package
```
pip install -r requirements.txt
```

# Local test
```
sls wsgi serve
```

You can use Postman or other tool test api in local environment
Send Get Http method to `http://localhost:5000/`
Then you will get `Hello world`

# Deploy to AWS
```
sls deploy
```
You can see endpoint in console.
# Reference
https://ithelp.ithome.com.tw/articles/10213432
https://www.serverless.com/blog/flask-python-rest-api-serverless-lambda-dynamodb