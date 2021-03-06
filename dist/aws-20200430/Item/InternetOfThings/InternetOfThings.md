# Internet Of Things

```text
aws-20200430/Item/InternetOfThings/InternetOfThings
```

```text
include('aws-20200430/Item/InternetOfThings/InternetOfThings')
```

|icon|card|element|group|
|---|---|---|---|
|![](InternetOfThings.png)|![](InternetOfThings.card.png)|![](InternetOfThings.element.png)|![](InternetOfThings.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the InternetOfThings element
include('aws-20200430/Item/InternetOfThings/InternetOfThings')
InternetOfThingsCard('internet_of_things', 'Internet Of Things', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the InternetOfThings element
include('aws-20200430/Item/InternetOfThings/InternetOfThings')
InternetOfThingsCard('internet_of_things', 'Internet Of Things', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```


## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the InternetOfThings element
include('aws-20200430/Item/InternetOfThings/InternetOfThings')
InternetOfThings('internet_of_things', 'Internet Of Things', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the InternetOfThings element
include('aws-20200430/Item/InternetOfThings/InternetOfThings')
InternetOfThings('internet_of_things', 'Internet Of Things', 'an optional tech field')
@enduml
```


## group
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the InternetOfThings element
include('aws-20200430/Item/InternetOfThings/InternetOfThings')
InternetOfThingsGroup('internet_of_things', 'Internet Of Things', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the InternetOfThings element
include('aws-20200430/Item/InternetOfThings/InternetOfThings')
InternetOfThingsGroup('internet_of_things', 'Internet Of Things', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

