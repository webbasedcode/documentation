# User Story description: As an user I want to be able to Log out of my account


## Info
* voorbeeld: Colaborator: [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md)
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-10)


## Beschrijving 
Creating a simple react component for logging out with a redirect to the login page


## Steps
> precondtion: User is logged in (and is in a page where the navbar is visible)
> 1. User presses the button
> 2. System logs out of the applciation
> 3. System redirects to landing page


## *COMPLEMENTING* Images
![link of image that includes logout button](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/navbar.png)

image of where and how the logout button is displayed


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
