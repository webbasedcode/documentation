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

## Implementation visible:
- [Backend repository > oauth (& other places)](https://github.com/webbasedcode/backend)
- [Frontend repository > login (& other places)](https://github.com/webbasedcode/frontend)

## Best place to learn:
[GitHub Docs (OAuth apps)](https://docs.github.com/en/developers/apps/building-oauth-apps)

## Used resources
* [link to used resources](https://github.com/webbasedcode/documentation/blob/main/doc/learningstories/oauth/oauth_used_resources.md)
* [met hulp en samenwerking van Tom Kempers](https://github.com/TomKemperNL)
