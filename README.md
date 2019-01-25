# phpLDAPadmin-helm-chart

A helm chart for phpLDAPadmin.

## Usage

```
helm install \
  --name phpldapadmin \
  --set LDAP.host=openldap-service.default.svc.cluster.local:389 \
  https://github.com/DavidCai1993/phpLDAPadmin-helm-chart/releases/download/v0.1.9/phpLDAPadmin-helm-chart-0.1.9.tgz
```

For more configurable values, check [values.yaml](https://github.com/DavidCai1993/phpLDAPadmin-helm-chart/blob/master/values.yaml).
