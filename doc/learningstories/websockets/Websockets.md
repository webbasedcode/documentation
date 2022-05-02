# Learning story: Websockets

### Details:

- Name: Creation and working with websockets
- Date: 25-4-2022
- Researcher: Iwan van der Kolk
- Reason: For our website its crucial that we use websockets,
  as we want to show live updates to other users.
- Functionality: Using websockets to let people write at the same time and update this for other users. 
  So that the users can code together.
  

## Why not ... instead of websockets

- Restful api calls:
  - Too brute.
  - Too slow.
  - Against the principle of the logic itself, due to being highly inefficient.
  - Far too many api calls per minute. As it would require an update call every second or so.
- Server-Sent Events:
  - Limited to 6 HTTPS connections for each server.
  - Limited support. 
  - More secure due to limits.
- Firebase:
  - Lack of specific operations on queries.
  - Is an implementation of websockets.

## Conclusion on why:

Websockets might be rather complex, yet for what it delivers once set up. It is what we need.
Where the other researched lack, websockets provide an option. Even though firebase is an implementation of websockets.
Which would make it easier to implement at a first, yet is limiting when we go in depth for our program.
With things like **redis** and **postgres**, hence its easier to go from scratch instead of firebase.
As once its set up, and learned, it has massive profits.

## Implementation visible:

- [In the demo repository](https://github.com/webbasedcode/demo/tree/main/backend-demo/src/main/java/com/demowebsocket)
- [Backend repo, for terminal](https://github.com/webbasedcode/backend/tree/main/src/main/java/hu/quintor/project/webbasedcode)

## Best place to learn:

If it's necessary to learn, it is best to go to view it [in the demo repository](https://github.com/webbasedcode/demo/tree/main/backend-demo/src/main/java/com/demowebsocket)
<br>As a new learner can use that, change some code on that, implement something on that person's own without influencing anything.

