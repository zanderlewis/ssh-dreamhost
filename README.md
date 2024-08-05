# SSH-Dreamhost
Github Action for pushing code to Dreamhost via SSH.

## How to use
### STATIC
File: [dreamhost-static.yml](dreamhost-static.yml)
1. Setup your secrets: `KNOWN_HOSTS_ENTRY` (if you need help finding it, please go [here.](#finding-known-hosts-entry)), `USERNAME`, `PASSWORD`, and `HOST`.
2. Change the `DEPLOY_PATH` to your Dreamhost website folder.
3. You are done!

### LARAVEL
File: [dreamhost-laravel.yml](dreamhost-laravel.yml)
1. Use Steps 1 and 2 for the Static Guide.
2. Configure your PHP version in the yml file.
3. Make sure your Laravel `.env` file is already in Dreamhost.
4. You are done! The action will take care of migrations and compiling the front-end!

### PHP
File: [dreamhost-php.yml](dreamhost-php.yml)
1. Follow the steps for Laravel.
2. You are done!

## Finding Known Hosts Entry
To find the `Known Hosts Entry`, go to your Dreamhost Panel, on the left side of your screen, click the `more` tab and then go to `SSH Keys` and you will be able to find the Known Hosts entry there.