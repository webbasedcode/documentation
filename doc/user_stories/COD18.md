# User Story description: As a project leader I want to be able to create a project

## Info
* Colaborator(s): [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md), [Iwan](https://github.com/webbasedcode/documentation/blob/main/doc/members/Iwan.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-18)


## Beschrijving 
Being able to create a new project, this should automatically be assigned to the current user as project leader. You should set the project language for it when creating it.


## Steps
> precondtion: User is logged in, User is allowed & owner of the project
> 1. Owner presses the button to create a new project
> 2. System shows page to create project
> 3. Owner types: name & picks codelanguage
> 4. Owner presses send
> 5. System checks wheter the project name already exsists
> 6. System creates new project
> 7. System loads page of newly created project


## *COMPLEMENTING* images / references
![link to image of where to create project](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectspage.png)

image of where to create project

![link to image of project page](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

image of project page

![image of Sequence Diagram of Account](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/sequence%20diagram%20-%20codelaborative%20-%20Account.jpg)

image of Sequence Diagram of Account that contains creating project


![link to image of activity diagram of creating project](https://github.com/webbasedcode/documentation/blob/main/doc/model/Activity_diagram/create_project.png)

image of activity diagram of creating project



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
