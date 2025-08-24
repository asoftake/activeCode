# ASOFTAKE Activation Code Starter

## Usage

### 1. Add Dependency 

#### Maven Dependency
```xml
<dependency>
    <groupId>uk.asoftake</groupId>
    <artifactId>asoftake-activation-starter</artifactId>
    <version>1.0.3</version>
</dependency>
```

### 2. Enable the Feature
```java
@SpringBootApplication
@EnableActivation
public class MyApp {
    public static void main(String[] args) {SpringApplication.run(MyApp.class, args);}
}
```

### 3. Configure the Activation Code
```yaml
activation:
  code: your-activation-code
  server-url: https://active.asoftake.uk/api/activation
```

Done！🚀
