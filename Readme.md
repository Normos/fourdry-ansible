# An ansible playbook to provision a foundry vtt server

## Instrucitons
* Rename host.example -> host
* Fill out the details of your VPS
* Download current version of foundry for linux from foundry website
* Put zip into foundry_zis/foundryvtt.zip
* Get key and certficate for ssl into cert/cert.pem and cert/key.pem
* Run with ansible-playbook