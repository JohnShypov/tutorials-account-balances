# tutorials-account-balances
curl 'http://70.34.211.203:3000/' -H 'Accept-Encoding: gzip, deflate, br' -H 'Content-Type: application/json' -H 'Accept: application/json' -H 'Connection: keep-alive' -H 'DNT: 1' -H 'Origin: http://70.34.211.203:3000' --data-binary '{"query":"query {\n  accounts(first:15, orderBy:BALANCE_ASC){\n    nodes{\n      account\n      balance\n    }\n  }\n}"}' --compressed
