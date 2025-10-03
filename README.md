# decap-github-auth

custom backend for Decap CMS using GitHub OAuth, containerized with Docker Compose. This backend will:

Authenticate users with GitHub

Return a token that Decap CMS can use

Use Node.js (Express) and Passport.js for GitHub OAuth

```
decap-github-auth/
├── docker-compose.yml
├── Dockerfile
├── .env
├── package.json
├── server.js
└── config.yml      # Decap CMS config (optional)


```
