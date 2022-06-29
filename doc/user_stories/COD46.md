# User Story description: As a programmer I want to be able to view other users messages in my projects messages

## Info
* Colaborator: [Iwan](https://github.com/webbasedcode/documentation/blob/main/doc/members/Iwan.md) & [Bas's profile](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md)
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-46)


## Beschrijving 
> As a programmer I want to activly chat with the other project members; so communication & teamwork is made easier & better. This is done by having the programmers connected by a websocket and updating all the messages live to everyone in the project.


## Steps
> precondition: the user is signed in, the user is allowed to use the application, the programmer is in a project, the programmer is in the main screen of the project
> 
> **[RE-ACTIVE]**
> 1. System detects a change in messages
> 2. System updates all messages
> 3. System returns all messages
> 4. System displays all messages

## *COMPLEMENTING* images / references
![link to wireframe of projectpage](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

image of where the chat is displayed


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
> ```
