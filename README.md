# Monty-and-the-Beanstalk
An AWS Elastic Beanstalk example using Python


### Start the API

PowerShell
```powershell
> .venv/Scripts/Activate.ps1 # -- optional
> uvicorn --app-dir .\app\ main:app
```

Bash
```bash
> source .venv\Scripts\source # -- optional
> uvicorn --app-dir ./app/ main:app
```

### Create an AWS source code bundle

```bash
git archive -v -o monty-and-the-beanstalk.zip --format=zip HEAD
```

See: [https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/applications-sourcebundle.html](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/applications-sourcebundle.html)
