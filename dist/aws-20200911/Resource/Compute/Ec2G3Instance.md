# Ec2 G3 Instance

```text
aws-20200911/Resource/Compute/Ec2G3Instance
```

```text
include('aws-20200911/Resource/Compute/Ec2G3Instance')
```

|icon|card|element|group|
|---|---|---|---|
|![](Ec2G3Instance.png)|![](Ec2G3Instance.card.png)|![](Ec2G3Instance.element.png)|![](Ec2G3Instance.group.png)|



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
' loads the Ec2G3Instance element
include('aws-20200911/Resource/Compute/Ec2G3Instance')
Ec2G3InstanceCard('ec_2_g_3_instance', 'Ec2 G3 Instance', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the Ec2G3Instance element
include('aws-20200911/Resource/Compute/Ec2G3Instance')
Ec2G3InstanceCard('ec_2_g_3_instance', 'Ec2 G3 Instance', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the Ec2G3Instance element
include('aws-20200911/Resource/Compute/Ec2G3Instance')
Ec2G3Instance('ec_2_g_3_instance', 'Ec2 G3 Instance', 'an optional tech field')
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
' loads the Ec2G3Instance element
include('aws-20200911/Resource/Compute/Ec2G3Instance')
Ec2G3Instance('ec_2_g_3_instance', 'Ec2 G3 Instance', 'an optional tech field')
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
' loads the Ec2G3Instance element
include('aws-20200911/Resource/Compute/Ec2G3Instance')
Ec2G3InstanceGroup('ec_2_g_3_instance', 'Ec2 G3 Instance', 'an optional tech field'){
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
' loads the Ec2G3Instance element
include('aws-20200911/Resource/Compute/Ec2G3Instance')
Ec2G3InstanceGroup('ec_2_g_3_instance', 'Ec2 G3 Instance', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

