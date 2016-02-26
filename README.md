#AzureJavaEE

The AzureJavaEE Project was setup to provide information on running real Java workloads in the Azure WebApp (Paas) environment.  It addresses specifically the following issues:
* Enbling continuous deployment to install TomEE Plume, allowing the use of the full JavaEE stack
* Enabling continuous deployment to update the Tomcat configuration files, allowing the use of container managed resources such as JDBC connection pools
* Enabling continuous deployment to place jar files in the Tomcat lib directory, allowing the use of container managed resources such as JDBC connection pools
* Enabling the relocation of the log and webapps directories to ensure they are where Azure expects them to be
* Enabling the passing of Connection Strings and other environment variables into the Java container, enabling standardisation and externalisation of configuration such as passwords
* Removing the dependancy on Sticky Sessions by enabling Azure Redis Cache as the session store
* Enabling Azure Access Control Service as the Authentication Provider, enabling the use of Azure Active Directory