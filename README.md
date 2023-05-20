# Random Jokes 

## Framworks & Language Used 

* Java 17(Language)
* Springboot 3.0.5(Framwork)
* Apache Maven 4.0.0
* IntelliJ IDEA

## Data Flow
1.Controller:
* It consists of JokeController classesin which used the annotations like @RestController to annotate the class as Controller.
Used annotation @GetMapping , @PostMapping  to map the HTTP web requests to the specific handler methods.
### API Reference:
<br>

>Joke API References
<br>

* Add Jokes:
```*.sh-session
  http://localhost:8080/jokes
```

* Get Joke:
```*.sh-session
 http://localhost:8080/joke
```


2. Service:
* It consists of JokeService classe in which provide some business functionalities of every handler methods.
* Used @Service annotation to indicate that a class belongs to the service layer.

3. Repository:
* It consist StockRepo class that contains a ArrayList. ArrayList used to store the jokes. 
* Used @Repository annotation is used to indicate that the class provides the mechanism for storage, retrieval, search, update and delete operation on objects.

## Data Structure
* Used ArrayList to store the Jokes.

## Summary
 In this project we create a ArrayList to store the the jokes. we adding joke through calling postMapping api and getting random joke whenever we call the GetMapping api.
