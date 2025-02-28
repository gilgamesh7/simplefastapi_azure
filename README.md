# simplefastapi_azure
A simple exercise in creating a fastapi endpoint that deploys using CI?CD from Github to Azure web app

# Run app llocally
gunicorn -k uvicorn.workers.UvicornWorker -w 4 app:app

# Endpoints 
- Local : http://127.0.0.1:8000/api/v1/alive
- Azure : https://fastapionazure-b6gph4gzfva3gebp.australiaeast-01.azurewebsites.net/api/v1/alive