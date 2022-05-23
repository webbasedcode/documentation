# {TYPE} description: {TITLE}
> voorbeeld: Userstory description: As a programmer I want to be able to delete a file]

## Info
* Colaborators: {colaborator1}, ...
> voorbeeld: Colaborators: [Bas](https://github.com/webbasedcode/documentation/blob/main/doc/members/Bas.md), [Iwan](https://github.com/webbasedcode/documentation/blob/main/doc/members/Iwan.md), [Matthijs](https://github.com/webbasedcode/documentation/blob/main/doc/members/Matthijs.md) & [Vincent](https://github.com/webbasedcode/documentation/blob/main/doc/members/Vincent.md) 
<!-- * Sprint: {time-period}
> Sprint: sprint 1 t/m sprint 2 -->
* [link to jira of {TYPE}]({link})
> voorbeeld: [link to jira of User story](https://codelaborative.atlassian.net/jira/software/projects/COD/boards/1?selectedIssue=COD-55)

## Beschrijving 
{beschrijving van {TYPE}}
> voorbeeld: As a programmer i want to be able to delete a file on the frontend.
> This should send a request with the projectId and {file Identifyer} to the backend after which the backend should look for the project with this id, 
> grab the latest version of the project out of the cache and delete the file if the project contains the {file Identifyer}. 
> Then an (succes) response shoud be returned

## Steps
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
> 	  2. System try to reload connection

## *COMPLEMENTING* Images
> voorbeeld:  
> * ![link to {image}]({link})
> * ![link to {image}]({link})
> 
> ...

## *EXTRA* Code
> voorbeeld: 
> ```{coding language}
> some code 
> ```
