# Typical Azure CLI commands

## account commands
### login

```
$ az login
To sign in, use a web browser to open the page https://aka.ms/devicelogin and enter the code <CODE_TO_ENTER> to authenticate.
[
  {
    "cloudName": "AzureCloud",
    "id": "__ID_SHOWN_HERE__",
    "isDefault": true,
    "name": "Free Trial",
    "state": "Enabled",
    "tenantId": "__TENANT_ID_SHOWN_HERE__",
    "user": {
      "name": "james7088@gmail.com",
      "type": "user"
    }
  }
]
```
### show
```
$ az account show
{
  "cloudName": "AzureCloud",
  "id": "__ID_SHOWN_HERE__",
  "isDefault": true,
  "name": "Free Trial",
  "state": "Enabled",
  "tenantId": "__TENANT_ID_SHOWN_HERE__",
  "user": {
    "name": "james7088@gmail.com",
    "type": "user"
  }
}
```
### list
```
$ az account list
[
  {
    "cloudName": "AzureCloud",
    "id": "__ID_SHOWN_HERE__",
    "isDefault": true,
    "name": "Free Trial",
    "state": "Enabled",
    "tenantId": "__TENANT_ID_SHOWN_HERE__",
    "user": {
      "name": "james7088@gmail.com",
      "type": "user"
    }
  }
]
```


## WebApp
```
$ az webapp list
```