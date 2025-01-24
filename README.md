# APEx Keycloak Theme

## Local Development

To facilitate local development of your theme, ensure the following prerequisite is available:

- **Docker**

Start a local Keycloak environment by running the provided `docker-compose.yml` file. Once successfully set up, a
Keycloak instance will be accessible at [http://localhost:8080](http://localhost:8080).

### Configuring the APEx Theme

To configure the APEx theme, follow the official Keycloak
guide: [Configuring a Theme](https://www.keycloak.org/docs/latest/server_development/#configuring-a-theme).

### Testing the Login Theme

To test your login theme:

1. Open a new private browser window.
2. Navigate to [http://localhost:8080/realms/master/account](http://localhost:8080/realms/master/account).
3. Click the **Sign In** button to view the customized login theme.
