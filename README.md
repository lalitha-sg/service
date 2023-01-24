# Customer CRUD operations

#### GET
```shell
curl --location --request GET 'http://localhost:8080/customers'
```


#### POST
```shell
curl --location --request POST 'http://localhost:8080/customers' \
--header 'Content-Type: application/json' \
--data-raw '{
    "id": 4,
    "firstName": "zxc",
    "lastName": "vbn",
    "emailId": "zxcvbn@mail.com"
}'
```

#### PUT
```shell
curl --location --request PUT 'http://localhost:8080/customers/2' \
--header 'Content-Type: application/json' \
--data-raw '{
    "id": 2,
    "firstName": "change",
    "lastName": "vbn",
    "emailId": "zxcvbn@mail.com"
}'
```

#### DELETE
```shell
curl --location --request DELETE 'http://localhost:8080/customers/1'
```