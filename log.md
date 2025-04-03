# 100 Days Of Code - Log

### Day 1: March 17, 2025 
### Day 1: March 17, 2025 

**Today's Progress**: practiced Js async features like readfile, writefile, callbacks, promises, async/await and learned Bash scripting 

**Thoughts:** I already knew it but I tried to get a deeper understanding of the async JS and played with it. Then I got myself familiar with bash scripting, how it is a lot more accessible version of Linux, and how helpful it is to get a lot of basic movement 

### Day 2: March 18, 2025 
**Today's Progress**: practiced Js async features like readfile, writefile, callbacks, promises, async/await and learned Bash scripting 

**Thoughts:** I already knew it but I tried to get a deeper understanding of the async JS and played with it. Then I got myself familiar with bash scripting, how it is a lot more accessible version of Linux, and how helpful it is to get a lot of basic movement 

### Day 2: March 18, 2025 

**Today's Progress**: Learned more Bash scripting, how frontends and backends communicate (client and server) and set up vite react for a project 

**Thoughts:** I practiced bash scripting made a couple of cool programs like a game using conditionals , learned about variables and how you can set a variable using .bashrc file which you can use it anytime , how you can do calculations using $(()) syntax and then learned about HTTP , client side contains protocol , URL , route , header , query params, method(GET,POST,PUT,DELETE) and server side has response headers , response , status codes.

### Day 3: March 19, 2025 
**Today's Progress**: Learned more Bash scripting, how frontends and backends communicate (client and server) and set up vite react for a project 

**Thoughts:** I practiced bash scripting made a couple of cool programs like a game using conditionals , learned about variables and how you can set a variable using .bashrc file which you can use it anytime , how you can do calculations using $(()) syntax and then learned about HTTP , client side contains protocol , URL , route , header , query params, method(GET,POST,PUT,DELETE) and server side has response headers , response , status codes.

### Day 3: March 19, 2025 

**Today's Progress**: Learned about express  

**Thoughts:** I wrote some express servers utilizing methods like get and post , also used postman for sending requests and understood the need to use app.use(express.json()) to parse json data from request body to js object which gives us access to the request body.

### Day 4: March 20, 2025 

**Today's Progress**: Learned more about express and started to dive into react 

**Thoughts:** I wrote some backend servers using express

### Day 5: March 21, 2025 

**Today's Progress**: Got the overview of Next js , learned about git and github , and worked with express

**Thoughts:** High level working of next js and what it is , Learned git and github like branching , merging , how to make pull requests and how it works everything , and wrote code in express

### Day 6: March 22, 2025 

**Today's Progress**: Just covered express

**Thoughts:**  I can build http servers using express

### Day 7: March 23, 2025 

**Today's Progress**: Learned about react ,understood middlewares and its importance and importance of input validation

**Thoughts:**  I got to know how react works , components , states, server side and client side components( next js) , how to use middlewares , 3 inputs that every middleware takes : req,res and next, input validation

### Day 8: March 24, 2025 

**Today's Progress**: Learned about zod, authentication (hashing,encryption,jwt,localstorage) and databases (noSQL MongoDB with mongoose for schema for mongo)

**Thoughts:**  : I learned about zod a library which helps us to do input validation and in their documentation many different data types usage is mentioned with syntax on how to go about using it , hashing which happens only one way usually used for passwords (once hased you cannot decode it and the way it is used is whenever a user comes to visit the platform the password that they enter gets hashed and it is compared to the password which is stored in the db already hased and if both matches the user is logged in )
Hashing
Consistency (same input = same hash)
One-way transformation (can't reverse the hash back to password)
Unique output for different inputs

So to directly answer your question: The hashed password is ALWAYS the same for the same input, not random, but designed to be secure and non-reversible.

Encryption 
2 way -> It can be decoded using a key

Json web token
decoded without password 
Decoding just reveals the token's contents
Anyone can decode the token's header and payload
BUT decoding does NOT mean you can use or validate the token
but to verify you need A SECRET KEY (not exactly a password)
The secret is used to verify the token's SIGNATURE

Token Structure:

Header (contains algorithm info)
Payload (contains claims/data)
Signature (cryptographically signed part)

and learned about how jwt is stored in localstorage when you create a new account the backend send you jwt back and stores it so that you don't need to enter password again and learned about databases and its importance (large amount of data easily manage,central location data, optimise data usage) and mongoDb utilize and used mongoose to create schema 

### Day 9: March 25, 2025 

**Today's Progress**: Practiced what i learned mongoose schema for mongodb, authentication with jwt and worked with routes 

**Thoughts:**  Used mongoose to build DB schema and created models , middlewares for user ,admin authentication with jwt and passing jwt in headers on every request

### Day 10: March 26, 2025 

**Today's Progress**: learned about the usage of backend and setted up a new react project 

**Thoughts:**  Having a backend is very important this is how the websites actually talk (using api) , you dont need to share everything on the frontend (the looks and feels of a website) this is where backend comes to play to create routes , manage data with database , and keep things organized. Started a react project called WisdomWave a yt shorts like app but with inspirational quotes so i created landing page for it (used copilot for that )

### Day 11: March 27, 2025 

**Today's Progress**: learned react and built backend for my fullstack prject (WisdomWave)

**Thoughts:**  I dont how to make a functioning backend but im using a random tut and using it as a guide and doing things my way with my app

### Day 12: March 28, 2025 

**Today's Progress**: worked on backend of the project

**Thoughts:**  built controllers , sending jwt , middleware , and a lot of bugs when using postman to check up on how things are working and had to go through the entire code from start to understand the flow of backend

### Day 13: March 29, 2025 

**Today's Progress**: worked on backend of the project got struck with a lot of errors , learned about authentication and learned about how frontend and backend communicates (what is internet , web , tcp/ip , http , server, network and how it all works)

**Thoughts:**  errors that i got from the project were about db not connection , internal server error, unable to create new user so have to refactor it all tomorrow , and learned a lot about authentication 

### Day 14: March 30, 2025 

**Today's Progress**: worked on authentication of my project and tested with postman , learned about debouncing and throttling and why is it necessary and learned about ui and ux

**Thoughts:**  the errors like reading prop. null when doing backend , whenever you recieve that you need to be aware that the issue is in your code and it may be a type error (not specifically ) but not using the proper terminology , to prevent sending automatic too many requests which put a lot of load on servers we use debouncing to make sure that when is user is finished writing the thing the user wants to search that when we'll send one request make request sending more optimised and learned about importance of ui and ux and the 4 step design process ( data collection , alternatives , prototype and evaluation)

### Day 15: March 31, 2025 

**Today's Progress**: created quotes route on backend for the project and learned why react is used instead of DOM (it is very verbose and time consuming ) and learned about ui / ux pricipals for collecting information about the users

**Thoughts:**  i need to be more focused on building and just shipping things than just consuming content , just gotta build a lot of things to gain the skill expertise and confidence 

### Day 16: April 1, 2025 

**Today's Progress**: Tested routes and all worked fine , started building frontend (created pages , components , routing) just frontend work is remaining , learned react works and difference between react and react dom

**Thoughts:**  get more focused and try to get more done each day, well gave a test of ui ux course and i messed it up , gotta retry it again

### Day 17: April 2, 2025 

**Today's Progress**:set up routes in frontend using react router , built out logic for authentication on frontend (did state management using zustand ) and learned about state , components and re-rendering in react

**Thoughts:**  

### Day 18: April 2, 2025 

**Today's Progress**:Finished building the sign up page with proper authentication and input validation

**Thoughts:**  i got sick today so didn't got much done

