
# app

## Architecture

* Docker
* GCP Cloud Build
* GCP Container Registry
* GCP Cloud Run
* GCP Firestore

## Technology

* Flask
* Gunicorn
* Python
* Swagger

### Flask

```
# Powershell

$env:FLASK_APP = 'index'
$env:GCP_CREDENTIALS = '{
  "type": "service_account",
  "project_id": "cloudguruchallenge-2108",
  "private_key_id": **redacted**,
  "private_key": **redacted**,
  "client_email": "wheelersadvice-svc@cloudguruchallenge-2108.iam.gserviceaccount.com",
  "client_id": **redacted**,
  "auth_uri": "https://accounts.google.com/o/oauth2/auth",
  "token_uri": "https://oauth2.googleapis.com/token",
  "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
  "client_x509_cert_url": "https://www.googleapis.com/robot/v1/metadata/x509/wheelersadvice-svc%40cloudguruchallenge-2108.iam.gserviceaccount.com"
}'

python -m flask run
```
>https://flask.palletsprojects.com/en/2.0.x/quickstart/

### Swagger

> https://dev.to/sanjan/how-to-add-swagger-ui-to-a-plain-flask-api-project-with-an-openapi-specification-file-1jl8

> https://editor.swagger.io/

> https://github.com/swagger-api/swagger-ui/archive/master.zip
