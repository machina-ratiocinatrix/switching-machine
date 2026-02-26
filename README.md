# Switching Machine
Switching-Machine replaces a switchman.
```bash
  echo '[{"role": "user", "content": "I have a question..."}]' \
    | uvx switching-machine \
        --provider-api-key=sk-ant-api... \
        --github-token=ghp_... \
        --mode=single
```
Or:
```bash
  pip install switching-machine
```
Then:
```Python
  # Python
  import switching_machine
```
