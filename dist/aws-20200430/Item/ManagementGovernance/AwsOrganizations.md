# Aws Organizations

```text
aws-20200430/Item/ManagementGovernance/AwsOrganizations
```

```text
include('aws-20200430/Item/ManagementGovernance/AwsOrganizations')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsOrganizations.png)|![](AwsOrganizations.card.png)|![](AwsOrganizations.element.png)|![](AwsOrganizations.group.png)|



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
' loads the AwsOrganizations element
include('aws-20200430/Item/ManagementGovernance/AwsOrganizations')
AwsOrganizationsCard('aws_organizations', 'Aws Organizations', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsOrganizations element
include('aws-20200430/Item/ManagementGovernance/AwsOrganizations')
AwsOrganizationsCard('aws_organizations', 'Aws Organizations', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsOrganizations element
include('aws-20200430/Item/ManagementGovernance/AwsOrganizations')
AwsOrganizations('aws_organizations', 'Aws Organizations', 'an optional tech field')
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
' loads the AwsOrganizations element
include('aws-20200430/Item/ManagementGovernance/AwsOrganizations')
AwsOrganizations('aws_organizations', 'Aws Organizations', 'an optional tech field')
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
' loads the AwsOrganizations element
include('aws-20200430/Item/ManagementGovernance/AwsOrganizations')
AwsOrganizationsGroup('aws_organizations', 'Aws Organizations', 'an optional tech field'){
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
' loads the AwsOrganizations element
include('aws-20200430/Item/ManagementGovernance/AwsOrganizations')
AwsOrganizationsGroup('aws_organizations', 'Aws Organizations', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

