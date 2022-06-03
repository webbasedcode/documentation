# User Story description: As a programmer I want to be able to run my javascript(nodejs) code from a project in the application

## Info
* Colaborator(s): [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-32)


## Beschrijving 
As a programmer i want to be able to press the run button on the frontend. This should send a request with the projectId to the backend after which the backend should look for the project with this id, grab the latest version of the project out of the cache and move these files to the run folder. Then a dockerfile should be moved in this folder and a docker container build and run. After a certain amount of time this container should automatically be closed and the output of it should be streamed with a websocket to the frontend.


## Steps
<!-- precondtion: {precondition}
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
<!-- ![link to {image}]({link})

{explanation by/for image}

> voorbeeld:  
> ![test image](https://www.lslegal.nl/wp-content/uploads/2017/03/Test-image-1.jpg)
> 
> this is a test image to show how to implement a image into usecase descriptions
> 
> 
> voorbeeld2:
> [link to learning story](...)
> 
> ... -->


## *EXTRA* Code
<!-- ```{coding language}
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
