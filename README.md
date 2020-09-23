# keycloak-11.0.2 --- STANDALONE MODE
## Starting the Keycloak server
1 - Go to the bin directory of the server distribution.

2 - Run the standalone boot script.

Linux/Unix
> $ ./bin/standalone.sh

Windows
> ...\bin\standalone.bat

## Creating the admin account
1 - Open http://localhost:8080/auth in your web browser.

The welcome page opens, confirming that the server is running.

2 - Enter a username and password to create an initial admin user.

## Logging into the admin console
1 - Click the Administration Console link on the Welcome page or go directly to http://localhost:8080/auth/admin/ (the console URL).

2 - Enter the username and password you created on the Welcome page to open the admin console.

The initial screen for the admin console appears.

Now that you can log into the admin console, you can begin creating realms where administrators can create users and give them access to applications. 

For more details, see Creating a realm and a user.
https://www.keycloak.org/docs/latest/getting_started/index.html

# keycloak-11.0.2 --- DOCKER MODE
## Starting the Keycloak server

> npm run docker-up

## Creating the admin account

> npm run docker-admin-up

## Restart the Keycloak Server

> npm run docker-down

> npm run docker-admin-up

OR

> npm run docker-dev

## Logging into the admin console
1 - Click the Administration Console link on the Welcome page or go directly to http://localhost:8099/auth/admin/ (the console URL).

2 - Enter the username and password created on the command line of "docker-admin-up" to open the admin console.
