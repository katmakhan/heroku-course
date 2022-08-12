# Heroku Course

- Setup Heroku Account
- Free tier consist of `5 apps` with 2 dynos each
- `Dynos` are like single python programs, One single project can contain multiple dynos
- `Max 2 dynos` can be run `concurrently`
- Check the usage https://dashboard.heroku.com/account/billing
- Once you add a `credit card` you will get `1000 FREE dyno hours` per month
- You can also add `FREE add ons` like `Schedulers` when you add a credit card `No extra charge`
- If not provide any credit card, then only `550 FREE dyno hours`
- PS: You cannot add Indian Credit/Debit as of now, due to `RBI Restriction`
- Kindly get any other dubai/us/canadian credit card to activate these `FREE Features`

### Initial Setup
- One `Python` File/ `Node Js`
- One `Procfile` without Extensions
- One `requirements.txt` file with modules name and version
- one `runtime.txt` explaining which python/node to be installed in the cloud.

### Procfile
- <service_name> : <program> <path_to_the_program>
```console
fetch_service: python fetch_firebase_data.py
delete_service: python delete_firebase_data.py

```

### requirements.txt
```console
requests==2.25.1
firebase-admin==3.1.0
pathlib==1.0.1
fyers-apiv2==2.0.5
requests-html==0.10.0
pandas==0.25.1
```

### runtime.txt
```console
python-3.7.13
```


### Checking usage of `FREE dynos`
https://dashboard.heroku.com/account/billing


