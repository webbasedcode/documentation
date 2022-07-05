# Learning story: OAuth

### Details:
- Name: Creating and implemening oauth as a secure authentication & authorization tool
- Date: 2-5-2022
- Researcher: Bas Valkonet
- Reason: The website needs a secure and easy tool to authenticate and authorize users into our application.
- Functionality: Letting users authenticate & authorize (log in) via github and being able to save progress based on the signed in github account.

## Why OAuth instead of other solutions
- Expendability & upgradability:
    - OAuth has gives a lot of freedom and expendability, examples of this are:
      - profile picure of github indetifies a person
      - editting existing repos
      - integration of projects from github with our application
      - information gathering of personal preferances
    - OAuth is created by github and as long as github decides to maintain this function, will it be supported and maintainable
- Documentation & explenation of OAuth
    - The documentaion and implementation of OAuth has been made verry clear. this mostly is because it is created by github and well known for its features.

## Conclusion on why:
The constant maintainability of OAuth by GitHub is a good indication of the activity that it is worked on. 
The fact that the end goal is to authorize & authenticate with github only justifies using a github implementation

![sequence of GitHub OAuth2](https://images.ctfassets.net/cdy7uua7fh8z/2nbNztohyR7uMcZmnUt0VU/2c017d2a2a2cdd80f097554d33ff72dd/auth-sequence-auth-code.png)

1. The user clicks Login within the regular web application.
2. Auth0's SDK redirects the user to the Auth0 Authorization Server ([/authorize endpoint](https://auth0.com/docs/api/authentication#authorization-code-grant)).
3. Your Auth0 Authorization Server redirects the user to the login and authorization prompt.
4. The user authenticates using one of the configured login options and may see a consent page listing the permissions Auth0 will give to the regular web application.
5. Your Auth0 Authorization Server redirects the user back to the application with an authorization code, which is good for one use.
6. Auth0's SDK sends this code to the Auth0 Authorization Server ([/oauth/token endpoint](https://auth0.com/docs/api/authentication?http#authorization-code-flow43)) along with the application's Client ID and Client Secret.
7. Your Auth0 Authorization Server verifies the code, Client ID, and Client Secret.
8. Your Auth0 Authorization Server responds with an ID Token and Access Token (and optionally, a Refresh Token).
9. Your application can use the Access Token to call an API to access information about the user.
10. The API responds with requested data.

## Implementation visible:
- [Backend repository > oauth (& other places)](https://github.com/webbasedcode/backend)
- [Frontend repository > login (& other places)](https://github.com/webbasedcode/frontend)

## Best place to learn:
[GitHub Docs (OAuth apps)](https://docs.github.com/en/developers/apps/building-oauth-apps)

## Used resources
* [link to used resources](https://github.com/webbasedcode/documentation/blob/main/doc/learningstories/oauth/oauth_used_resources.md)
* [met hulp en samenwerking van Tom Kempers](https://github.com/TomKemperNL)
