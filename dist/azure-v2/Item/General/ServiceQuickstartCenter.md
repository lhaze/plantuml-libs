# Service Quickstart Center

```text
azure-v2/Item/General/ServiceQuickstartCenter
```

```text
include('azure-v2/Item/General/ServiceQuickstartCenter')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceQuickstartCenter.png)|![](ServiceQuickstartCenter.card.png)|![](ServiceQuickstartCenter.element.png)|![](ServiceQuickstartCenter.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceQuickstartCenter element
include('azure-v2/Item/General/ServiceQuickstartCenter')
ServiceQuickstartCenterCard('service_quickstart_center', 'Service Quickstart Center', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceQuickstartCenter element
include('azure-v2/Item/General/ServiceQuickstartCenter')
ServiceQuickstartCenterCard('service_quickstart_center', 'Service Quickstart Center', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceQuickstartCenter element
include('azure-v2/Item/General/ServiceQuickstartCenter')
ServiceQuickstartCenter('service_quickstart_center', 'Service Quickstart Center', 'an optional tech field')
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceQuickstartCenter element
include('azure-v2/Item/General/ServiceQuickstartCenter')
ServiceQuickstartCenter('service_quickstart_center', 'Service Quickstart Center', 'an optional tech field')
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceQuickstartCenter element
include('azure-v2/Item/General/ServiceQuickstartCenter')
ServiceQuickstartCenterGroup('service_quickstart_center', 'Service Quickstart Center', 'an optional tech field'){
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceQuickstartCenter element
include('azure-v2/Item/General/ServiceQuickstartCenter')
ServiceQuickstartCenterGroup('service_quickstart_center', 'Service Quickstart Center', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

