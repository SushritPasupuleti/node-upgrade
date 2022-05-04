# `node` Upgrade
Upgrade Node on Unix without disruption

Run the following:

(force) clear you npm cache

```bash
sudo npm cache clean -f
```
install n (this might take a while)

```bash
sudo npm install -g n
```

upgrade to the current stable version

```bash
sudo n stable
```
