# Group Elastic Container Service

```text
aws-20200430/Group/GroupElasticContainerService
```

```text
include('aws-20200430/Group/GroupElasticContainerService')
```

|group|
|---|
|![](GroupElasticContainerService.group.local.png)|



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
' loads the GroupElasticContainerService element
include('aws-20200430/Group/GroupElasticContainerService')
GroupElasticContainerService('group_elastic_container_service', 'Group Elastic Container Service', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the GroupElasticContainerService element
include('aws-20200430/Group/GroupElasticContainerService')
GroupElasticContainerService('group_elastic_container_service', 'Group Elastic Container Service', 'an optional tech field')
@enduml
```

