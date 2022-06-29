# User Story description: As a programmer I want to be able to see the commands other people type from the shared in-browser linux terminal


## Info
* Colaborators: [Iwan](https://github.com/webbasedcode/documentation/blob/main/doc/members/Iwan.md), [Matthijs](https://github.com/webbasedcode/documentation/blob/main/doc/members/Matthijs.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-51)

## Beschrijving 
Being able to see live updates on what other people in the shared in browser terminal, typing something yourself or sending a command yourself isn’t a part of this feature and should be done before
This feature is related to the learning story [COD-105: Working with websockets](https://codelaborative.atlassian.net/browse/COD-105) Working with websockets


## Steps
> precondtion: User is logged in, User is allowed in a project, User is in the page of the allowed project
> 1. Programmer typs something in the terminal
> 2. Programmer presses ENTER
> 3. System starts Docker container
> 4. System checks terminal text for malisious intent
> 5. System runs code
> 6. System displays result in FE


## *COMPLEMENTING* Images
![link to wireframe of projectpage](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

Info: On the bottom of the image a terminal will be created where linux commands can be executed on, these commands will be shown live to all users vieuwing this project page.

![link to image of sequence diagram of running code](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/DockerRunProject.png)

image of sequence diagram of running code

![link to image of sequence diagram of running code](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/sequence%20diagram%20-%20codelaborative%20-%20Coder.png)

image of sequence diagram of running code

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
