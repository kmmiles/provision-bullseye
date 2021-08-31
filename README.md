# provision-bullseye

provision debian 11

## install

```bash
sudo apt update && sudo apt --no-install-recommends install -y ca-certificates curl && \
  curl -s "https://raw.githubusercontent.com/kmmiles/provision-bullseye/main/bin/bootstrap?epoch=$(date '+s')" | bash
```
