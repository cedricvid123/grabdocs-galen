# grabdocs-galen

## Branching for Galen Layout Work

- `main` — protected, always green
- `feature/gspec-<area>` — layout/spec changes
- `feature/flow-<area>` — JS flow changes

### Contribution Rules
- PRs require **2 approvals** and **Galen CI must pass**
- Include Galen **HTML report** or screenshots in PR
- Prefer `[data-test]` selectors

### Local Run
```bash
galen test tests/grabdocs.test \
  --htmlreport reports \
  --vars "{'baseUrl':'https://grabdocs.com','user':'<email>','pass':'<pass>','upload':'/abs/path/file.pdf'}"
