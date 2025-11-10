# grabdocs-galen

# GrabDocs – Galen Test Suite

## How to Run
```bash
galen test tests/grabdocs.test \
  --htmlreport reports \
  --vars "{'baseUrl':'https://grabdocs.com','user':'<email>','pass':'<password>','upload':'/path/to/file.pdf'}"
