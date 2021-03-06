# Aws Think Box Frost

```text
aws-20200911/Service/Compute/AwsThinkBoxFrost
```

```text
include('aws-20200911/Service/Compute/AwsThinkBoxFrost')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsThinkBoxFrost.png)|![](AwsThinkBoxFrost.card.png)|![](AwsThinkBoxFrost.element.png)|![](AwsThinkBoxFrost.group.png)|



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
' loads the AwsThinkBoxFrost element
include('aws-20200911/Service/Compute/AwsThinkBoxFrost')
AwsThinkBoxFrostCard('aws_think_box_frost', 'Aws Think Box Frost', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsThinkBoxFrost element
include('aws-20200911/Service/Compute/AwsThinkBoxFrost')
AwsThinkBoxFrostCard('aws_think_box_frost', 'Aws Think Box Frost', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsThinkBoxFrost element
include('aws-20200911/Service/Compute/AwsThinkBoxFrost')
AwsThinkBoxFrost('aws_think_box_frost', 'Aws Think Box Frost', 'an optional tech field')
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
' loads the AwsThinkBoxFrost element
include('aws-20200911/Service/Compute/AwsThinkBoxFrost')
AwsThinkBoxFrost('aws_think_box_frost', 'Aws Think Box Frost', 'an optional tech field')
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
' loads the AwsThinkBoxFrost element
include('aws-20200911/Service/Compute/AwsThinkBoxFrost')
AwsThinkBoxFrostGroup('aws_think_box_frost', 'Aws Think Box Frost', 'an optional tech field'){
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
' loads the AwsThinkBoxFrost element
include('aws-20200911/Service/Compute/AwsThinkBoxFrost')
AwsThinkBoxFrostGroup('aws_think_box_frost', 'Aws Think Box Frost', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

