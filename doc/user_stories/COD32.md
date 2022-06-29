# User Story description: As a programmer I want to be able to run my javascript(nodejs) code from a project in the application

## Info
* Colaborator(s): [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-32)


## Beschrijving 
As a programmer i want to be able to press the run button on the frontend. This should send a request with the projectId to the backend after which the backend should look for the project with this id, grab the latest version of the project out of the cache and move these files to the run folder. Then a dockerfile should be moved in this folder and a docker container build and run. After a certain amount of time this container should automatically be closed and the output of it should be streamed with a websocket to the frontend.


## Steps

 Precondition: Logged in, authorized, within project, code written.
 1. Programmer clicks on run button
 2. System tries to run code
    1. System returns errors  
 3. Programmer receives result
	  1. Run output
	  2. Error from run issues


## *COMPLEMENTING* images / references
![link to image of wireframe of page where file derectory exists](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

image of wireframe of page where code is run

![image of Sequence Diagram of Account](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/DockerRunProject.png)

Sequence diagram van Account run code/project

![image of Sequence Diagram of Coder](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/sequence%20diagram%20-%20codelaborative%20-%20Coder.png)

Sequence diagram van de Coder run code/project




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
