# UIT Exercise (Redis)

Use the chat app that you made last week, and make it hold persistent data by doing the following

  1. Ensure that you are connected to the Redis database
  2. Save your last logged user by saving a simple string in Redis using .get() and .set()
  3. Save your messages list as a redis list by using .rpush() and .lrange()
  4. Save and access your list of usernames in a redis set by using .sadd(), .srem() and .smembers()

**Notes and Tips:**

  - You only have to work in the server.js file for this assignment. Everything else can be worked with as-is, but you are free to change whatever you like. Just remember, with great power comes great responsibility! :)
  - Ensure that your local version of redis is working in terminal before trying to use in production. You don't want to be debugging your project when it was Redis all along!
  - You can find a list of the most commonly used node-redis commands along with examples at https://gist.github.com/leommoore/4704080
  - If you're not sure how to implement after checking out the examples, ask!