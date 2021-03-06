# Service Scheduler

```text
azure-v2/Item/General/ServiceScheduler
```

```text
include('azure-v2/Item/General/ServiceScheduler')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceScheduler.png)|![](ServiceScheduler.card.png)|![](ServiceScheduler.element.png)|![](ServiceScheduler.group.png)|



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
' loads the ServiceScheduler element
include('azure-v2/Item/General/ServiceScheduler')
ServiceSchedulerCard('service_scheduler', 'Service Scheduler', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceScheduler element
include('azure-v2/Item/General/ServiceScheduler')
ServiceSchedulerCard('service_scheduler', 'Service Scheduler', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceScheduler element
include('azure-v2/Item/General/ServiceScheduler')
ServiceScheduler('service_scheduler', 'Service Scheduler', 'an optional tech field')
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
' loads the ServiceScheduler element
include('azure-v2/Item/General/ServiceScheduler')
ServiceScheduler('service_scheduler', 'Service Scheduler', 'an optional tech field')
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
' loads the ServiceScheduler element
include('azure-v2/Item/General/ServiceScheduler')
ServiceSchedulerGroup('service_scheduler', 'Service Scheduler', 'an optional tech field'){
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
' loads the ServiceScheduler element
include('azure-v2/Item/General/ServiceScheduler')
ServiceSchedulerGroup('service_scheduler', 'Service Scheduler', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

