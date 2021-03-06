# Aws Cloud Alt

```text
aws-20200430/Item/Groups/AwsCloudAlt
```

```text
include('aws-20200430/Item/Groups/AwsCloudAlt')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsCloudAlt.png)|![](AwsCloudAlt.card.png)|![](AwsCloudAlt.element.png)|![](AwsCloudAlt.group.png)|



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
' loads the AwsCloudAlt element
include('aws-20200430/Item/Groups/AwsCloudAlt')
AwsCloudAltCard('aws_cloud_alt', 'Aws Cloud Alt', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsCloudAlt element
include('aws-20200430/Item/Groups/AwsCloudAlt')
AwsCloudAltCard('aws_cloud_alt', 'Aws Cloud Alt', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsCloudAlt element
include('aws-20200430/Item/Groups/AwsCloudAlt')
AwsCloudAlt('aws_cloud_alt', 'Aws Cloud Alt', 'an optional tech field')
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
' loads the AwsCloudAlt element
include('aws-20200430/Item/Groups/AwsCloudAlt')
AwsCloudAlt('aws_cloud_alt', 'Aws Cloud Alt', 'an optional tech field')
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
' loads the AwsCloudAlt element
include('aws-20200430/Item/Groups/AwsCloudAlt')
AwsCloudAltGroup('aws_cloud_alt', 'Aws Cloud Alt', 'an optional tech field'){
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
' loads the AwsCloudAlt element
include('aws-20200430/Item/Groups/AwsCloudAlt')
AwsCloudAltGroup('aws_cloud_alt', 'Aws Cloud Alt', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

