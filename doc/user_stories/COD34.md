# User Story description: As a program leader I want to be able to invite other people to my project


## Info
* Colaborator: [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md)
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-34)

## Beschrijving 
Having an invite page to your project, there a user can select user to add to your users. 
This should be done with an input field where you have to put in atleast 3 letters and gives you back 5 users which names match. 
This also includes validation for only allowing users in the project to do stuff to the project. 


## Steps
> Precondition: Logged in, authorized, within project, created a project & is in project settings.
> 1. Project owner searches for a programmer by name
> 2. Programmers with similar names show up
> 3. Project owner selects a programmer he/she wants to add
> 4. Project owner pushes add user button
> 5. System checks text for:
>      1. if the current user is allowed in the application
>      2. if the current user is this project owner
>      3. if the programmer is allowed in the application
>      4. if the programmer isn’t already in the project
>      5. if the project is full
>
> * [if all true]:  system adds programmer
> * [if one (or more) false]:  system shows exception message
> 6. (AFTER): reload current page



## *COMPLEMENTING* images / references
![wireframe where to add new programmers to project](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectinfopage.png)

this is a wireframe where/how to add new programmers to project

![Sequence Diagram](https://github.com/webbasedcode/documentation/blob/main/doc/Sequence_diagram/AddUserToProject.png)

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
