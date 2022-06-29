# User Story description: As a programmer I want to be able to create a file for a project


## Info
* Colaborator(s): [Iwan](https://github.com/webbasedcode/documentation/blob/main/doc/members/Iwan.md) & [Matthijs](https://github.com/webbasedcode/documentation/blob/main/doc/members/Matthijs.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-54)


## Beschrijving 
Creating a file for a project, a user should enter a name and select a filetype(these will differ depending on code language). There has to be rules excluding special character(.,_)

## Steps
precondtion: User is logged in, User is allowed in a project, User is in the page of the allowed project
1. Programmer right clicks the directory tree
2. Programmer types name of file
3. Programmer clicks confirm
4. System checks whether it can create the project (checks:)
    1. if the file already exists
    2. whether the programmer is allowed to create a file
* [succes] if Everything is all right the System creates the file 
* [fail] the request is ignored
7. System reloads file directory 



## *COMPLEMENTING* images / references
![link to image of wireframe of page where file derectory exists](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

image of wireframe of page where file derectory exists

![image of Sequence Diagram of Account](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/ActionOnFileTreeOptionCreate.png)

Sequence Diagram of creating a new file in the directory tree


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
