# Service Journey Hub

```text
azure-v2/Item/General/ServiceJourneyHub
```

```text
include('azure-v2/Item/General/ServiceJourneyHub')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceJourneyHub.png)|![](ServiceJourneyHub.card.png)|![](ServiceJourneyHub.element.png)|![](ServiceJourneyHub.group.png)|



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
' loads the ServiceJourneyHub element
include('azure-v2/Item/General/ServiceJourneyHub')
ServiceJourneyHubCard('service_journey_hub', 'Service Journey Hub', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceJourneyHub element
include('azure-v2/Item/General/ServiceJourneyHub')
ServiceJourneyHubCard('service_journey_hub', 'Service Journey Hub', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceJourneyHub element
include('azure-v2/Item/General/ServiceJourneyHub')
ServiceJourneyHub('service_journey_hub', 'Service Journey Hub', 'an optional tech field')
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
' loads the ServiceJourneyHub element
include('azure-v2/Item/General/ServiceJourneyHub')
ServiceJourneyHub('service_journey_hub', 'Service Journey Hub', 'an optional tech field')
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
' loads the ServiceJourneyHub element
include('azure-v2/Item/General/ServiceJourneyHub')
ServiceJourneyHubGroup('service_journey_hub', 'Service Journey Hub', 'an optional tech field'){
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
' loads the ServiceJourneyHub element
include('azure-v2/Item/General/ServiceJourneyHub')
ServiceJourneyHubGroup('service_journey_hub', 'Service Journey Hub', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

