# Service Disk Encryption Sets

```text
azure-v2/Item/Compute/ServiceDiskEncryptionSets
```

```text
include('azure-v2/Item/Compute/ServiceDiskEncryptionSets')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceDiskEncryptionSets.png)|![](ServiceDiskEncryptionSets.card.png)|![](ServiceDiskEncryptionSets.element.png)|![](ServiceDiskEncryptionSets.group.png)|



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
' loads the ServiceDiskEncryptionSets element
include('azure-v2/Item/Compute/ServiceDiskEncryptionSets')
ServiceDiskEncryptionSetsCard('service_disk_encryption_sets', 'Service Disk Encryption Sets', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceDiskEncryptionSets element
include('azure-v2/Item/Compute/ServiceDiskEncryptionSets')
ServiceDiskEncryptionSetsCard('service_disk_encryption_sets', 'Service Disk Encryption Sets', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceDiskEncryptionSets element
include('azure-v2/Item/Compute/ServiceDiskEncryptionSets')
ServiceDiskEncryptionSets('service_disk_encryption_sets', 'Service Disk Encryption Sets', 'an optional tech field')
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
' loads the ServiceDiskEncryptionSets element
include('azure-v2/Item/Compute/ServiceDiskEncryptionSets')
ServiceDiskEncryptionSets('service_disk_encryption_sets', 'Service Disk Encryption Sets', 'an optional tech field')
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
' loads the ServiceDiskEncryptionSets element
include('azure-v2/Item/Compute/ServiceDiskEncryptionSets')
ServiceDiskEncryptionSetsGroup('service_disk_encryption_sets', 'Service Disk Encryption Sets', 'an optional tech field'){
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
' loads the ServiceDiskEncryptionSets element
include('azure-v2/Item/Compute/ServiceDiskEncryptionSets')
ServiceDiskEncryptionSetsGroup('service_disk_encryption_sets', 'Service Disk Encryption Sets', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

