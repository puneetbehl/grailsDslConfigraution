# Sample Grails 4.0.2 application
Ref: https://github.com/grails/grails-core/issues/11491

This is a sample Grails 4.0.2 application verifying that there are no issues with GORM DSL in the application.groovy configuration as:

_grails-app/config/application.groovy_
```
grails.gorm.default.mapping = {
    cache true
    id generator : 'uuid2'
}

```
