# Aws Snowmobile

```text
aws-20200430/Item/Storage/AwsSnowmobile
```

```text
include('aws-20200430/Item/Storage/AwsSnowmobile')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsSnowmobile.png)|![](AwsSnowmobile.card.png)|![](AwsSnowmobile.element.png)|![](AwsSnowmobile.group.png)|



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
' loads the AwsSnowmobile element
include('aws-20200430/Item/Storage/AwsSnowmobile')
AwsSnowmobileCard('aws_snowmobile', 'Aws Snowmobile', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsSnowmobile element
include('aws-20200430/Item/Storage/AwsSnowmobile')
AwsSnowmobileCard('aws_snowmobile', 'Aws Snowmobile', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsSnowmobile element
include('aws-20200430/Item/Storage/AwsSnowmobile')
AwsSnowmobile('aws_snowmobile', 'Aws Snowmobile', 'an optional tech field')
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
' loads the AwsSnowmobile element
include('aws-20200430/Item/Storage/AwsSnowmobile')
AwsSnowmobile('aws_snowmobile', 'Aws Snowmobile', 'an optional tech field')
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
' loads the AwsSnowmobile element
include('aws-20200430/Item/Storage/AwsSnowmobile')
AwsSnowmobileGroup('aws_snowmobile', 'Aws Snowmobile', 'an optional tech field'){
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
' loads the AwsSnowmobile element
include('aws-20200430/Item/Storage/AwsSnowmobile')
AwsSnowmobileGroup('aws_snowmobile', 'Aws Snowmobile', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

