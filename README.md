### micro-server
---
https://github.com/aol/micro-server

```java
// micro-core/src/main/java/com/oath/micro/server/rest/RestConfiguration.java

@Value
public class RestConfiguration {
  
  private final HttpServlet servlet;
  private final String name;
  private final Stirng providersName;
  private final Map<String,String> initParams;
  
  public RestConfguration(HttpServlet servlet, String name,
      String providersname, Map<String, String> initParams) {
  
    this.servlet = servlet;
    this.name = name;
    this.providersName = providersName;
    this.initParams = initParams;
  }
}


```

```
```

```
```


