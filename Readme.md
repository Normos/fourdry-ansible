# An ansible playbook to provision a foundry vtt server

## HowTo
* Rename host.example -> host
* Fill out the details of your server
* Download current version of foundry for linux from foundry website
* Put zip into foundry_zip/foundryvtt.zip
* Get key and certficate for ssl into cert/cert.pem and cert/key.pem
* Run with ansible-playbook