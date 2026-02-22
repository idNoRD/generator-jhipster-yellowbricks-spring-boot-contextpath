# generator-jhipster-yellowbricks-server-contextpath

## Change target:
- File: https://github.com/jhipster/generator-jhipster/blob/main/generators/spring-boot/templates/src/main/resources/config/application.yml.ejs
- Generator: https://github.com/jhipster/generator-jhipster/tree/main/generators/spring-boot
- Purpose: Configure context-path


## For example
Assume the context-path is "/jh"
So `src/main/resources/config/application.yml` will be
```diff
server:
  servlet:
+   context-path: /jh/
    session:
      cookie:
        http-only: true
```
