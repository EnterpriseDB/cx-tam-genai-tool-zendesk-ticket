# ZenDesk Tools

## create .venv

```
python3.12 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Archive the Tool to zip file

```
zip -r ../zendesk_tool.zip . -x "*.git*" -x "*__pycache__*" -x "*.venv/lib/python*/site-packages/*"
```

## upload the Data Lake

## create a Tools

