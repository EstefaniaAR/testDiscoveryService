# testDiscoveryService
Part of a spring cloud sample.
Tutorial link : https://www.youtube.com/watch?v=ZyK5QrKCbwM

## Discovery Service
Discovery services allows services to find and communicate each other.

## Requirements 
- Spring boot
- Java 8
- Config server from :https://github.com/EstefaniaAR/testConfigServer.git
- Reservation service from: https://github.com/EstefaniaAR/testReservationService.git
- Eureka Service: https://github.com/EstefaniaAR/testEurekaService.git

## Dependencies
      <dependencies>
        <dependency>
          <groupId>org.springframework.boot</groupId>
          <artifactId>spring-boot-starter-actuator</artifactId>
        </dependency>
        <dependency>
          <groupId>org.springframework.boot</groupId>
          <artifactId>spring-boot-starter-web</artifactId>
        </dependency>
        <dependency>
          <groupId>org.springframework.cloud</groupId>
          <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
        </dependency>
        <dependency>
          <groupId>org.springframework.cloud</groupId>
          <artifactId>spring-cloud-starter-netflix-eureka-server</artifactId>
        </dependency>

        <dependency>
          <groupId>org.springframework.boot</groupId>
          <artifactId>spring-boot-starter-test</artifactId>
          <scope>test</scope>
        </dependency>
      </dependencies>
 ## Run 
 Run the main class as Spring boot Application
 
