# timestamped-notes
Web app for taking notes on videos with timestamps 

## Running the project
Installation prerequisites:
- Yarn or npm

### Example .env file for development environment

Some of this might be outdated:

```env
DATABASE_NAME=timestamped-notes
POSTGRES_PASSWORD=verysecretpassword
DATABASE_URL=postgresql://postgres:verysecretpassword@postgres:5432/timestamped-notes
REDIS_URL=redis:6379
COOKIE_DOMAIN=.felixtan.me
CORS_ORIGIN=http://localhost:3000
PORT=5000
SESSION_SECRET=laksdjfpq08w439owijhdklmbsdfklqjwyhef98
NEXT_PUBLIC_GRAPHQL_SERVER_URL=http://localhost:5000/graphql
GITHUB_OAUTH_CALLBACK_URL=http://localhost:5000/auth/github/callback
```
|Environment variable|Description|
|-|-|
|`DATABASE_NAME`|Name of database to be created in Postgres|
|`POSTGRES_PASSWORD`|Password used for accessing Postgres database|
|`DATABASE_URL`|Postgres connection URL|
|`REDIS_URL`|Redis connection URL|
|`COOKIE_DOMAIN`|The base domain that cookies will work on. Must be set if using subdomains in production|
|`CORS_ORIGIN`|CORS origin (client URL)|
|`PORT`|Port that the Express server uses/exposes|
|`SESSION_SECRET`|Used for encrypting session data. Put a long, hard to crack string here|
|`NEXT_PUBLIC_GRAPHQL_SERVER_URL`|Endpoint that the client uses to access the GraphQL server|
|`GOOGLE_OAUTH_CLIENT_ID`|Google OAuth client ID|
|`GOOGLE_OAUTH_CLIENT_SECRET`|Google OAuth client secret|
|`GOOGLE_OAUTH_CALLBACK_URL`|Google OAuth callback URL|
|`GITHUB_OAUTH_CLIENT_ID`|GitHub OAuth client ID|
|`GITHUB_OAUTH_CLIENT_SECRET`|GitHub OAuth client secret|
|`GITHUB_OAUTH_CALLBACK_URL`|GitHub OAuth callback URL|
|`FACEBOOK_OAUTH_CLIENT_ID`|Facebook OAuth client ID|
|`FACEBOOK_OAUTH_CLIENT_SECRET`|Facebook OAuth client secret|
|`FACEBOOK_OAUTH_CALLBACK_URL`|Facebook OAuth callback URL|
|`YOUTUBE_DATA_API_KEY`|API key for getting data from the YouTube Data API|
