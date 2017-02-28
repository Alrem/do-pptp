# PPTPD Server for DigitalOcean-likes instances (do-pptp)

1. Uncomment/add user/password to `chap-secrets` file
2. Uncomment/add IP to `xenial_server.ini` file
3. Run `ansible-playbook xenial_pptpd.yml -i xenial_server.ini`
