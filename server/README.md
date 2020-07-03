# atm

NodeJS API ATM

## API:

- `/api/balance` [GET]

```
?account=<account-id>
```

- `/api/deposit` [POST]

```
{
  "value": 5,
  "banknotes": [
    {
      "value": "2",
      "amount": 2
    },
    {
      "value": "1",
      "amount": 1
    }
  ],
  "targetAccount": "test"
}
```

- `/api/withdraw` [POST]

```
{
  "value": 1,
  "account": "test"
}
```

## Details

DB needs one single preparations before start using:  
The Collection "Banknote" has the `"notAllowed":false` parameter to be block specific Bank Notes Nominations (such as 1 BRL).

Auth, Tests and local Config are not included at this moment
