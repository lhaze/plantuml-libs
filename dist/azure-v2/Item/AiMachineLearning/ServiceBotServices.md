# Service Bot Services

```text
azure-v2/Item/AiMachineLearning/ServiceBotServices
```

```text
include('azure-v2/Item/AiMachineLearning/ServiceBotServices')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceBotServices.png)|![](ServiceBotServices.card.png)|![](ServiceBotServices.element.png)|![](ServiceBotServices.group.png)|



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
' loads the ServiceBotServices element
include('azure-v2/Item/AiMachineLearning/ServiceBotServices')
ServiceBotServicesCard('service_bot_services', 'Service Bot Services', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceBotServices element
include('azure-v2/Item/AiMachineLearning/ServiceBotServices')
ServiceBotServicesCard('service_bot_services', 'Service Bot Services', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceBotServices element
include('azure-v2/Item/AiMachineLearning/ServiceBotServices')
ServiceBotServices('service_bot_services', 'Service Bot Services', 'an optional tech field')
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
' loads the ServiceBotServices element
include('azure-v2/Item/AiMachineLearning/ServiceBotServices')
ServiceBotServices('service_bot_services', 'Service Bot Services', 'an optional tech field')
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
' loads the ServiceBotServices element
include('azure-v2/Item/AiMachineLearning/ServiceBotServices')
ServiceBotServicesGroup('service_bot_services', 'Service Bot Services', 'an optional tech field'){
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
' loads the ServiceBotServices element
include('azure-v2/Item/AiMachineLearning/ServiceBotServices')
ServiceBotServicesGroup('service_bot_services', 'Service Bot Services', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

