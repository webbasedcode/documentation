# User Story description: As an user I want to sign into the application with github


## Info
* Colaborator: [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md)
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-88)


## Beschrijving 
Being able to login to the application using github, this feature is in relation of [learning story 98 learning to work with oath](https://github.com/webbasedcode/documentation/blob/main/doc/learningstories/oauth/oauth.md)


## Steps
> 1. The User presses the github login button 
> 2. System redirects the User to mutiple github auth pages with info (see [working with oauth](https://github.com/webbasedcode/documentation/blob/main/doc/learningstories/oauth/oauth.md))
> 3. System logs in / creates account with information
> 4. System redirects User (Now programmer) to the home page


## *COMPLEMENTING* images / references
![link to image of using github oauth](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/loginpage.png)

image how github oauth is predicted to be implemented (wireframe)

![link toHome page](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectspage.png)

image of homepage that the system redirect you to after oauth

* [learning to work with oath](https://github.com/webbasedcode/documentation/blob/main/doc/learningstories/oauth/oauth.md)


<!-- ## *EXTRA* Code
```{coding language}
{code} 
```

> voorbeeld: 
> ```js
> function onload() {
>        let user = window.location.href.replace("http://localhost:3000/login", "");
>        if (user.length > 6) {
>            store.dispatch(userToken(user.replace("?user=", "")));
>            redirect();
>        } 
>    }
> ``` -->
