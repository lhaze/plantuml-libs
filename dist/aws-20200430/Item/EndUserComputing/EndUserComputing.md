# End User Computing

```text
aws-20200430/Item/EndUserComputing/EndUserComputing
```

```text
include('aws-20200430/Item/EndUserComputing/EndUserComputing')
```

|icon|card|element|group|
|---|---|---|---|
|![](EndUserComputing.png)|![](EndUserComputing.card.png)|![](EndUserComputing.element.png)|![](EndUserComputing.group.png)|



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
' loads the EndUserComputing element
include('aws-20200430/Item/EndUserComputing/EndUserComputing')
EndUserComputingCard('end_user_computing', 'End User Computing', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the EndUserComputing element
include('aws-20200430/Item/EndUserComputing/EndUserComputing')
EndUserComputingCard('end_user_computing', 'End User Computing', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the EndUserComputing element
include('aws-20200430/Item/EndUserComputing/EndUserComputing')
EndUserComputing('end_user_computing', 'End User Computing', 'an optional tech field')
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
' loads the EndUserComputing element
include('aws-20200430/Item/EndUserComputing/EndUserComputing')
EndUserComputing('end_user_computing', 'End User Computing', 'an optional tech field')
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
' loads the EndUserComputing element
include('aws-20200430/Item/EndUserComputing/EndUserComputing')
EndUserComputingGroup('end_user_computing', 'End User Computing', 'an optional tech field'){
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
' loads the EndUserComputing element
include('aws-20200430/Item/EndUserComputing/EndUserComputing')
EndUserComputingGroup('end_user_computing', 'End User Computing', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

