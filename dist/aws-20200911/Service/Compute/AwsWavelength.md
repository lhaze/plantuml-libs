# Aws Wavelength

```text
aws-20200911/Service/Compute/AwsWavelength
```

```text
include('aws-20200911/Service/Compute/AwsWavelength')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsWavelength.png)|![](AwsWavelength.card.png)|![](AwsWavelength.element.png)|![](AwsWavelength.group.png)|



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
' loads the AwsWavelength element
include('aws-20200911/Service/Compute/AwsWavelength')
AwsWavelengthCard('aws_wavelength', 'Aws Wavelength', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsWavelength element
include('aws-20200911/Service/Compute/AwsWavelength')
AwsWavelengthCard('aws_wavelength', 'Aws Wavelength', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsWavelength element
include('aws-20200911/Service/Compute/AwsWavelength')
AwsWavelength('aws_wavelength', 'Aws Wavelength', 'an optional tech field')
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
' loads the AwsWavelength element
include('aws-20200911/Service/Compute/AwsWavelength')
AwsWavelength('aws_wavelength', 'Aws Wavelength', 'an optional tech field')
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
' loads the AwsWavelength element
include('aws-20200911/Service/Compute/AwsWavelength')
AwsWavelengthGroup('aws_wavelength', 'Aws Wavelength', 'an optional tech field'){
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
' loads the AwsWavelength element
include('aws-20200911/Service/Compute/AwsWavelength')
AwsWavelengthGroup('aws_wavelength', 'Aws Wavelength', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

