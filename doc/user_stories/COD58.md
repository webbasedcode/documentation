# User Story description: As a programmer i want to be able to manage the docker containers manually for test purposes
> voorbeeld: Userstory description: As a programmer I want to be able to delete a file


## Info
* Colaborators: [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
* [link to jira of User Story](https://codelaborative.atlassian.net/browse/COD-58)

## Beschrijving 
This feature is mostly functionality for testing out how the connection to docker works with spring, afterwards most of the things this feature does(like starting a container) will be moved inside of other features. For example whenever you run a project one of the first steps it will have to do is start the container. Or whenever you start a project it will have to create a container for it. These basic features will sadly be unable to be tested currently due to difficulties with testing the docker-java plugin we’re currently using


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


<!-- ## *COMPLEMENTING* Images
![link to {image}]({link})

{explanation by/for image}

> voorbeeld:  
> ![test image](https://www.lslegal.nl/wp-content/uploads/2017/03/Test-image-1.jpg)
> 
> this is a test image to show how to implement a image into usecase descriptions
> 
> ... -->


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
