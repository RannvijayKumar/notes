- 02/05/2020
- Saturday
- Day 4


# Flow

- Create Project
- Git Repo
- Create Skeleton
    - Hardcode Return Values
- Add Just Works Functionality
- Integrate with UI
- Add Service Discovery 
- Add Load Balancing
- Add Proxy
- Add CI Pipelines
- Add Remaining Functionality in sprints
- Integrate with Backend DB
- Enable Logging
- Add Swagger API
- Add Code for Testing
- Add Authentication
- Add Authorization
- Add Circuit Breaker


# Today's Agenda

- CLI Based Application
- Microservice way
    - UI
    - DB



- Input
- Processed that input
- you took another input
- did further processing


- Microservice

- Consume Input
    - PathVariable
    - RequestBody
- Process
- Produce Output
    - JSON


He said, \"Wow this is a nice thing\"

```json
{
    "bookId": id,
    "price": 800
}
```

- Example Java Code for custom JSON output

```java
package in.cg.demo.controllers;

import org.springframework.http.MediaType;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.PathVariable;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
@RequestMapping(value="/",produces=MediaType.APPLICATION_JSON_VALUE)
public class Api {
	@GetMapping("/book/{bookId}")
	public String displayBook(@PathVariable("bookId") int bookId) {
		return "{\r\n    \"bookId\": " + bookId + ",\r\n    \"msg\": \"Not Implemented yet\"\r\n}";
	}
}
```



# Rest Template Example

- Producer Service (demo)
- Consumer Service (demo-1)



- Client
    - RestTemplate
- Server
    - @RestController





# Expectations on Monday

- Scrum Possibly on Trello
- Start some part of the UI
- Atleast create your producers


# T1 : Employee Maintenance System

- git repository ready
- projects ready
- models ready


- H2 Use Cases
    - 

- SQL 
    - persistent
    - 


4gb of data from sql puts it inside h2 database

Tracing
Message Queues




```json
{
    "key":"value",
    "Key2": {
        "key3": "value2",
        "key4": "value3"
    }
}
```

```yaml
key: value
Key2:
    key3: value2
    key4: value3
```


```properties
server.port=8080
```


```yaml
server:
    port: 8080
```


```json
{
    "server":{
        "port": 8080
    }
}
```

# T3

