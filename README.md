# Monitoring Spring Boot Applications with Prometheus Demo

Link to original tutorial can be found in two parts:
[part1](https://www.callicoder.com/spring-boot-actuator/),
[part2](https://www.callicoder.com/spring-boot-actuator-metrics-monitoring-dashboard-prometheus-grafana/)

## Useful links

- Testing endpoint using intellij builtin [http client](https://www.vojtechruzicka.com/intellij-idea-tips-tricks-testing-restful-web-services/)
- Docs for spring actuator [prod-ready-endpoints](https://docs.spring.io/spring-boot/docs/current/reference/html/production-ready-endpoints.html)
- More info on [micrometer](http://micrometer.io/)

## Notes for Docker for Windows Users

Copy docker directory into C:\Users\username\Documents and run compose from there. You will need to change the prometheus.yml file to reflect your ip address instead of localhost as the target since you are running your spring boot code on a different ip as your prometheus container.
