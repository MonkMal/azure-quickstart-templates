# Deploy Azure Database for PostgreSQL with VNet

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsavjani%2Fazure-quickstart-templates%2Fmaster%2F101-managed-postgresql-with-vnet%2Fazuredeploy.json" target="_blank">
  <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template provides a easy way to deploy Azure database for PostgreSQL with VNet Integration. The template also showcases how to use ARM template to set server parameters and set security policies like Advanced threat protection on the server. In the template, we set the server parameter log_min_messages to INFO and set Advanced threat protection ON by default when the server is provisioned using the template.
