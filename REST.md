
## What Is REST ?

REST stands for **REpresentational State Transfer**. Fancy name, simple idea: it's a way for computers to talk to each other over the web. 

### 1. Client-Server
Separate the front-end (what users see) from back-end (where data lives). They talk through requests.

### 2. Stateless
Every request has ALL the info needed to understand it. The server doesn't remember you between requests.

**What I actually do:** I send my login token with EVERY request.

### 3. Cacheable
Responses should say if they can be cached. Makes things faster.

### 4. Uniform Interface
This is the big one - everything works the same way:
- Resources (like /users or /products)
- Manipulation through representations (JSON/XML)
- Self-descriptive messages
- HATEOAS (more on this later)

### 5. Layered System
You don't need to know if you're talking to the actual server or a middleman.

### 6. Code on Demand (Optional)
Server can send code to run on client. Like JavaScript.

## How REST Actually Works - The Real Stuff

### The Golden Pattern: URL + HTTP Method

See the pattern? **The URL says WHAT, the HTTP method says HOW.**


