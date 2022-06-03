# User Story description: As a programmer I want to be able to type code (text) in the browser


## Info
* Colaborator(s): {colaborator1}, ...
> voorbeeld: Colaborators: [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md), [Iwan](https://github.com/webbasedcode/documentation/blob/main/doc/members/Iwan.md), [Matthijs](https://github.com/webbasedcode/documentation/blob/main/doc/members/Matthijs.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of {TYPE}]({link})
> voorbeeld: [link to jira of User Story](https://codelaborative.atlassian.net/jira/software/projects/COD/boards/1?selectedIssue=COD-55)


## Beschrijving 
As a programmer i want to be able to type the code in the browser and have this saved in our backend, this should be saved in a redis cache and allow for us to run it later [COD-32: As a programmer I want to be able to run my javascript(nodejs) code from a project in the application](https://codelaborative.atlassian.net/browse/COD-32) This will be done per line, the redis cache should remember the project, the file, which line and what it contains. (int projectid, string filename, int line, string content).
As in Redis we got a database link with the project id, the key is the filename, int line is for the index and string content is what is being saved.
This means file names have to be unique within the project.
The feature will require websockets which we’ll learn with learning story [COD-105: Working with websockets](https://codelaborative.atlassian.net/browse/COD-105).


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


## *COMPLEMENTING* images / references
![link to Activity Diagram of obtaining code](https://github.com/webbasedcode/documentation/blob/main/doc/model/activity_diagram/Activity%20diagram%20obtaining%20code.png)

{explanation by/for image}

![link to image rough scetch redis](https://github.com/webbasedcode/documentation/blob/main/doc/learningstories/redis/Rough%20sketch%20redis.png)

{explanation by/for image}


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
