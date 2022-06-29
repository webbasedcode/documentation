# User Story description: As a programmer I want to run commands in a shared in-browser Linux terminal


## Info
* Colaborators: [Matthijs](https://github.com/webbasedcode/documentation/blob/main/doc/members/Matthijs.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-43)


## Beschrijving 
Being able to send command to project’s container for setup purposes, the command should be send from the front end, received from the backend and passed to the docker container


## Steps
Precondition: Logged in, authorized, within project.
1. Programmer selects terminal
2. Programmer enters text
3. Programmer sends run command
4. System checks text for illegal statements
    <br> a. System returns error for found illegal statements
    <br> b. System skips execute [COD-54](https://codelaborative.atlassian.net/browse/COD-54)
5. System executes text
6. Programmer receives result
    <br> a. Feedback from Linux terminal
    <br> b. Error for illegal statements
    <br> c. Error for runtime exception <br>
* Any time, the connection with back-end is lost:
1. System display error message
2. System try to reload connection


## *COMPLEMENTING* Images
![link to wireframe of projectpage](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

Info: On the bottom of the image a terminal will be created where linux commands can be executed on, these commands will be shown live to all users vieuwing this project page.

![link to image of sequence diagram of running code](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/DockerRunProject.png)

simple image of sequence diagram of running code

![link to image of sequence diagram of running code](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/sequence%20diagram%20-%20codelaborative%20-%20Coder.png)

Detailed image of sequence diagram of running code
![link to image](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/RunTerminal.drawio%20(1).png?raw=true)



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
