# User Story description: As a programmer I want to be able to delete a file


## Info
* Colaborator(s): [Iwan](https://github.com/webbasedcode/documentation/blob/main/doc/members/Iwan.md) & [Matthijs](https://github.com/webbasedcode/documentation/blob/main/doc/members/Matthijs.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-55)

## Beschrijving 
Being able to delete a file from a project, right clicking on a file in the file directory and selecting delete file 


## Steps
> precondtion: User is logged in, User is allowed in a project, User is in the page of the allowed project & there is atleast 1 existing file (in the project)
> 1. Programmer right clicked a file
> 2. System shows button to delete file
> 3. Programmer requests to delete the file
> 4. Sytem checks whether the file can be deleted (does it still exist)
> 5. System deletes the file
> 6. System reloads the file directory


## *COMPLEMENTING* images / references
![link to image of wireframe of page where file derectory exists](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

image of wireframe of page where file derectory exists

![image of Sequence Diagram of Account](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/ActionOnFileTreeOptionDelete.png)

Sequence Diagram of deleteing a file (in the file directory)

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
