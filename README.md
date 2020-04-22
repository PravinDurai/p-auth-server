# p-auth-server


# Swagger UI provide the template of the payload along with list of fields that has to be populated for any given end points.
# Please have a look at the swagger UI for accessing all the below endpoints -> Choose authentication Controller
# https://p-api-gateway.cfapps.io/auth/swagger-ui.html

# https://p-api-gateway.cfapps.io/auth/generate
#used for generating the jwt token

#  https://p-api-gateway.cfapps.io/auth/isexpired/{token}
# Validates the given jwt token and returns true/false

# https://p-api-gateway.cfapps.io/auth/user
# Used to create new user with userName, Password and role

#  https://p-api-gateway.cfapps.io/auth/role/{rolename}
# Used to add roles to user and it can be either "User" or "Admin"

#------------------------------------------------------------------------------------------------------------------------------------------------------------------
# PCF DB Credentials for Auth Server 
#------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Host Name : us-cdbr-iron-east-01.cleardb.net
# DB Name   : ad_ae6dabd5e495167
# User Name : b08dc5bddbb79b
# Password  : 1e522924