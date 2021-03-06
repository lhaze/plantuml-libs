# Elastic Load Balancing

```text
aws-20200430/Item/NetworkingContentDelivery/ElasticLoadBalancing
```

```text
include('aws-20200430/Item/NetworkingContentDelivery/ElasticLoadBalancing')
```

|icon|card|element|group|
|---|---|---|---|
|![](ElasticLoadBalancing.png)|![](ElasticLoadBalancing.card.png)|![](ElasticLoadBalancing.element.png)|![](ElasticLoadBalancing.group.png)|



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
' loads the ElasticLoadBalancing element
include('aws-20200430/Item/NetworkingContentDelivery/ElasticLoadBalancing')
ElasticLoadBalancingCard('elastic_load_balancing', 'Elastic Load Balancing', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ElasticLoadBalancing element
include('aws-20200430/Item/NetworkingContentDelivery/ElasticLoadBalancing')
ElasticLoadBalancingCard('elastic_load_balancing', 'Elastic Load Balancing', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ElasticLoadBalancing element
include('aws-20200430/Item/NetworkingContentDelivery/ElasticLoadBalancing')
ElasticLoadBalancing('elastic_load_balancing', 'Elastic Load Balancing', 'an optional tech field')
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
' loads the ElasticLoadBalancing element
include('aws-20200430/Item/NetworkingContentDelivery/ElasticLoadBalancing')
ElasticLoadBalancing('elastic_load_balancing', 'Elastic Load Balancing', 'an optional tech field')
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
' loads the ElasticLoadBalancing element
include('aws-20200430/Item/NetworkingContentDelivery/ElasticLoadBalancing')
ElasticLoadBalancingGroup('elastic_load_balancing', 'Elastic Load Balancing', 'an optional tech field'){
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
' loads the ElasticLoadBalancing element
include('aws-20200430/Item/NetworkingContentDelivery/ElasticLoadBalancing')
ElasticLoadBalancingGroup('elastic_load_balancing', 'Elastic Load Balancing', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

