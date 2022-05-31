# User Story description: As a programmer I want to be able to see the commands other people type from the shared in-browser linux terminal


## Info
* Colaborators: [Iwan](https://github.com/webbasedcode/documentation/blob/main/doc/members/Iwan.md), [Matthijs](https://github.com/webbasedcode/documentation/blob/main/doc/members/Matthijs.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-51)

## Beschrijving 
Being able to see live updates on what other people in the shared in browser terminal, typing something yourself or sending a command yourself isn’t a part of this feature and should be done before
This feature is related to the learning story [COD-105: Working with websockets](https://codelaborative.atlassian.net/browse/COD-105) Working with websockets


<!-- ## Steps
precondtion: {precondition}
1. {step 1}
2. {step 2}
    1. {step 2.1}
    2. {step 2.2}
3. {step 3}
...

> voorbeeld:
> 
> Precondition: Logged in, authorized, within project.
> 1. Programmer selects terminal
> 2. Programmer enters text
> 3. Programmer sends run command
> 4. System checks text for illegal statements
>     1. System returns error for found illegal statements
>     2. System skips execute  
> 5. System executes text
> 6. Programmer receives result
> 	  1. Feedback from Linux terminal
> 	  2. Error for illegal statements
> 	  3. Error for runtime exception
> 
> * Any time, the connection with back-end is lost:
> 	  1. System display error message
> 	  2. System try to reload connection -->


## *COMPLEMENTING* Images
![link to wireframe of projectpage](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

Info: On the bottom of the image a terminal will be created where linux commands can be executed on, these commands will be shown live to all users vieuwing this project page.


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
