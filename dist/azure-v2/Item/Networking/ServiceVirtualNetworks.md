# Service Virtual Networks

```text
azure-v2/Item/Networking/ServiceVirtualNetworks
```

```text
include('azure-v2/Item/Networking/ServiceVirtualNetworks')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceVirtualNetworks.png)|![](ServiceVirtualNetworks.card.png)|![](ServiceVirtualNetworks.element.png)|![](ServiceVirtualNetworks.group.png)|



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
' loads the ServiceVirtualNetworks element
include('azure-v2/Item/Networking/ServiceVirtualNetworks')
ServiceVirtualNetworksCard('service_virtual_networks', 'Service Virtual Networks', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceVirtualNetworks element
include('azure-v2/Item/Networking/ServiceVirtualNetworks')
ServiceVirtualNetworksCard('service_virtual_networks', 'Service Virtual Networks', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceVirtualNetworks element
include('azure-v2/Item/Networking/ServiceVirtualNetworks')
ServiceVirtualNetworks('service_virtual_networks', 'Service Virtual Networks', 'an optional tech field')
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
' loads the ServiceVirtualNetworks element
include('azure-v2/Item/Networking/ServiceVirtualNetworks')
ServiceVirtualNetworks('service_virtual_networks', 'Service Virtual Networks', 'an optional tech field')
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
' loads the ServiceVirtualNetworks element
include('azure-v2/Item/Networking/ServiceVirtualNetworks')
ServiceVirtualNetworksGroup('service_virtual_networks', 'Service Virtual Networks', 'an optional tech field'){
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
' loads the ServiceVirtualNetworks element
include('azure-v2/Item/Networking/ServiceVirtualNetworks')
ServiceVirtualNetworksGroup('service_virtual_networks', 'Service Virtual Networks', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

