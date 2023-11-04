# SAP-BTP-NodeJS-SSO
Protect NodeJS Application with OAuth2 using BTP XSUAA Service | Approuter

This open project for enabling OAuth2 Authentication as well adding scope to user role to limit view access for specific api endpoint.

## installation
```
git clone https://github.com/Jonathan-Prime/sap_btp-sso-nodejs
cd myapp
npm i
cd web
npm i
```
* To create XSUAA service using role template: 

CLI command:
```
cd security
cf create-service xsuaa application nodeuaa -c xs-security.json
```
