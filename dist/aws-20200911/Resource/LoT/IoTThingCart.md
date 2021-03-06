# Io T Thing Cart

```text
aws-20200911/Resource/LoT/IoTThingCart
```

```text
include('aws-20200911/Resource/LoT/IoTThingCart')
```

|icon|card|element|group|
|---|---|---|---|
|![](IoTThingCart.png)|![](IoTThingCart.card.png)|![](IoTThingCart.element.png)|![](IoTThingCart.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the IoTThingCart element
include('aws-20200911/Resource/LoT/IoTThingCart')
IoTThingCartCard('io_t_thing_cart', 'Io T Thing Cart', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the IoTThingCart element
include('aws-20200911/Resource/LoT/IoTThingCart')
IoTThingCartCard('io_t_thing_cart', 'Io T Thing Cart', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the IoTThingCart element
include('aws-20200911/Resource/LoT/IoTThingCart')
IoTThingCart('io_t_thing_cart', 'Io T Thing Cart', 'an optional tech field')
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the IoTThingCart element
include('aws-20200911/Resource/LoT/IoTThingCart')
IoTThingCart('io_t_thing_cart', 'Io T Thing Cart', 'an optional tech field')
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the IoTThingCart element
include('aws-20200911/Resource/LoT/IoTThingCart')
IoTThingCartGroup('io_t_thing_cart', 'Io T Thing Cart', 'an optional tech field'){
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the IoTThingCart element
include('aws-20200911/Resource/LoT/IoTThingCart')
IoTThingCartGroup('io_t_thing_cart', 'Io T Thing Cart', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

