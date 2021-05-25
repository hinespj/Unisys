# unisys

To deploy with Helm:
helm install unisys --repo https://cprice-ping.github.io/helm-charts ping-sample-ciam -f unisys.yaml

Once Deployed, you can access a Dashboard at:
https://facile.pingidentity.cloud/dashboard/unisys

Environment Name: unisys

Product Consoles:
My Ping:       https://console.pingone.com?env=aaf54acd-b7ca-41a5-a133-f95aa58316d9#/home?nav=home

PingData:      https://pingdataconsole-unisys.ping-devops.com
PingFederate:  https://pingfederate-admin-unisys.ping-devops.com/pingfederate
PingAccess:    https://pingaccess-admin-unisys.ping-devops.com
Delegator:     https://unisys.ping-devops.com/delegator/

Delegated Administration:
Documentation can be found at: https://github.com/cprice-ping/Profile-DelAdmin

External Hostname:
unisys.ping-devops.com

Authentication Policy Samples:SAML (Verify): https://unisys.ping-devops.com/idp/startSSO.ping?PartnerSpId=Sample-Verify
SAML (Single_Factor): https://unisys.ping-devops.com/idp/startSSO.ping?PartnerSpId=Sample-SAML
OIDC (Multi_Factor):  https://unisys.ping-devops.com/as/authorization.oauth2?response_type=code&client_id=PingLogon&redirect_uri=https://decoder.pingidentity.cloud/oidc&scope=openid%20profile

Profile Management:
https://unisys.ping-devops.com.ping-devops.com/pf/idprofile.ping?LocalIdentityProfileID=regIdentityProfile

Sample Users:
user.[0-4] | 2FederateM0re

OIDC Decoder Info:
Issuer:        https://unisys.ping-devops.com
Client ID:     PingLogon
Client Secret: 2FederateM0re

Access Management Demos:
Server-Side Headers: https://unisys.ping-devops.com/headers
Client-Side SPA:     https://unisys.ping-devops.com/spa
-----------------------------------