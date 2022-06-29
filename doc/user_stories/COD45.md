# User Story description: As a programmer I want to be able to view the results of my run javascript(nodejs) code from a project in the browser


## Info
* Colaborator(s): [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-45)


## Beschrijving 
Getting a response from the run javascript code and displaying this in a console like window, this will be text only(for example the outcome of a calculation)


## Steps

 Precondition: Logged in, authorized, within project, code written.
 1. Programmer clicks on run button
 2. System tries to run code
    1. System returns errors  
 3. Programmer receives result
	  1. Run output
	  2. Error from run issues

## *COMPLEMENTING* images / references
![link of sequence diagram of running code](https://github.com/webbasedcode/documentation/blob/main/doc/model/Sequence_diagram/sequence%20diagram%20-%20codelaborative%20-%20Coder.png)

image of sequence diagram of running code

![link to image where to vieuw the result of the runed code](https://github.com/webbasedcode/documentation/blob/main/doc/wireframes/projectpage.png)

image where to vieuw the result of the runed code


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
