# Customer Enablement

```text
aws-20200430/Item/CustomerEnablement/CustomerEnablement
```

```text
include('aws-20200430/Item/CustomerEnablement/CustomerEnablement')
```

|icon|card|element|group|
|---|---|---|---|
|![](CustomerEnablement.png)|![](CustomerEnablement.card.png)|![](CustomerEnablement.element.png)|![](CustomerEnablement.group.png)|



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
' loads the CustomerEnablement element
include('aws-20200430/Item/CustomerEnablement/CustomerEnablement')
CustomerEnablementCard('customer_enablement', 'Customer Enablement', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the CustomerEnablement element
include('aws-20200430/Item/CustomerEnablement/CustomerEnablement')
CustomerEnablementCard('customer_enablement', 'Customer Enablement', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the CustomerEnablement element
include('aws-20200430/Item/CustomerEnablement/CustomerEnablement')
CustomerEnablement('customer_enablement', 'Customer Enablement', 'an optional tech field')
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
' loads the CustomerEnablement element
include('aws-20200430/Item/CustomerEnablement/CustomerEnablement')
CustomerEnablement('customer_enablement', 'Customer Enablement', 'an optional tech field')
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
' loads the CustomerEnablement element
include('aws-20200430/Item/CustomerEnablement/CustomerEnablement')
CustomerEnablementGroup('customer_enablement', 'Customer Enablement', 'an optional tech field'){
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
' loads the CustomerEnablement element
include('aws-20200430/Item/CustomerEnablement/CustomerEnablement')
CustomerEnablementGroup('customer_enablement', 'Customer Enablement', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

