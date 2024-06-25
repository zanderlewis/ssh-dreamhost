# SSH-Dreamhost
Github Action for pushing code to Dreamhost via SSH.

## How to use
### STATIC
1. Setup your secrets: `KNOWN_HOSTS_ENTRY` (if you need help finding it, please go [here.](#finding-known-hosts-entry)), `USERNAME`, `PASSWORD`, and `HOST`.
2. Change the `DEPLOY_PATH` to your Dreamhost website folder.
3. You are done!

### LARAVEL
coming soon

## Finding Known Hosts Entry
To find the `Known Hosts Entry`, go to your Dreamhost Panel, on the left side of your screen, click the `more` tab and then go to `SSH Keys` and you will be able to find the Known Hosts entry there.