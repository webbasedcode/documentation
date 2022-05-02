# Learning story: Redis

### Details:

- Name: Implementing redis as temporary storage.
- Date: 2-5-2022.
- Researcher: Iwan van der Kolk.
- Reason: To let people live code, there must be a temporary in memory storage.
- Functionality: Using redis we can let users code without lagging out a server.


## Why not ... instead of redis

- Writing to files:
    - Too slow to save.
    - Is actively bad for storage medium, as it would constantly delete files and recreate them.
    - Can instantly be send to docker engine.
- Writing as list in a database:
    - Uses large amounts of memory.
    - On the slower side to write to a file

## Conclusion on why:

As we need to keep updating the file written in, and to keep remembering that there could be multiple files open at once.
With multiple coders typing at once, then speed of the backend is a factor deemed quite necessary.
Whilst that is a problem with writing to a file, this could be solved with time. 
Yet redis would be better then constantly file writing. As Redis is better for the storage mediums health.
And a database would be a bad choice due to it costing tons more memory.

## Implementation visible:

- [Demo repo under redis](https://github.com/webbasedcode/demo/tree/main/backend-demo/src/main/java/com/demowebsocket)

## Best place to learn:

This would best be learned at the [demo repo under redis.](https://github.com/webbasedcode/demo/tree/main/backend-demo/src/main/java/com/demowebsocket)
As there is an implementation in development there currently.

### Commands:
- lpush(key, strings):
  - Adds the strings at the left side at the key list
- rpush(key, strings):
  - Adds the strings at the right side at the key list
- lset(key, index, string)
  - Sets the value at the index to that string
  
- [RECOMMENDED LOOK INTO](https://redis.io/commands/keys/)
  - Is apperently a better way then the current list we use
  - Includes a warning for using KEYS command
