Oracle JRE Site
===========

### Sample for showing how to host the Oracle JRE using the [nginx-buildpack](https://github.com/cloudcommunity/nginx-buildpack)

Usage:

```
git clone https://github.com/pivotalservices/oracle-jre-site.git
cd oracle-jre/lucid/x86_64 # download the oracle jre and copy it here
cf push oracle-jre-site -b https://github.com/cloudfoundry-community/nginx-buildpack.git
```

Open the url to your application and index.html should happily greet you with a link to the location of files to browse.
