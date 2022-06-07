# EPIC description: As a programmer I want to participate and be able to execute commands in a shared in-browser Linux terminal so I can show other programmers what certain commands do


## Info
* [link to EPIC in jira](https://codelaborative.atlassian.net/browse/COD-1)


## Beschrijving 
> As a programmer I want to participate and be able to execute commands in a shared in-browser Linux terminal so I can show other programmers what certain commands do
> When a programmer is typing, this should be live shared accross all on the same project users.
> When another programmer starts typing, this should be seen as well within the same line as the original programmer
> After a command is made, and send by pressing enter, the back-end should check if the command is not illegal.
> If the command is illegal, there should be an error thrown.
> If the command is legal, it should be executed in a docker container.
> On a correct executement, the response in the container should be send back to the front-end
> On an error, the error should be send back to the front-end
<!-- {beschrijving van {TYPE}}
> voorbeeld: As a programmer i want to be able to delete a file on the frontend.
> This should send a request with the projectId and {file Identifyer} to the backend after which the backend should look for the project with this id, 
> grab the latest version of the project out of the cache and delete the file if the project contains the {file Identifyer}. 
> Then an (succes) response shoud be returned -->


## User Stories
<details>
<summary>COD44: As a programmer I want to see the outcome of the commands other people run from the shared in-browser Linux terminal</summary>

* [User Story description](https://github.com/webbasedcode/documentation/blob/main/doc/user_stories/COD44.md)
* [Link to jira](https://codelaborative.atlassian.net/browse/COD-44)
</details>


<details>
<summary>COD43: As a programmer I want to run commands in a shared in-browser Linux terminal</summary>

* [User Story description](https://github.com/webbasedcode/documentation/blob/main/doc/user_stories/COD43.md)
* [Link to jira](https://codelaborative.atlassian.net/browse/COD-43)
</details>


<details>
<summary>COD51: As a programmer I want to be able to see the commands other people type from the shared in-browser linux terminal</summary>

* [User Story description](https://github.com/webbasedcode/documentation/blob/main/doc/user_stories/COD51.md)
* [Link to jira](https://codelaborative.atlassian.net/browse/COD-51)
</details>


<details>
<summary>COD58: As a programmer i want to be able to manage the docker containers manually for test purposes</summary>

* [User Story description](https://github.com/webbasedcode/documentation/blob/main/doc/user_stories/COD58.md)
* [Link to jira](https://codelaborative.atlassian.net/browse/COD-58)
</details>
