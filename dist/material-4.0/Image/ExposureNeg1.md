# Exposure Neg1

```text
material-4.0/Image/ExposureNeg1
```

```text
include('material-4.0/Image/ExposureNeg1')
```

|icon|element|
|---|---|
|![](ExposureNeg1.png)|![](ExposureNeg1.element.png)|



## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the material-4.0 bootstrap
include('material-4.0/bootstrap')
' loads the ExposureNeg1 element
include('material-4.0/Image/ExposureNeg1')
ExposureNeg1('exposure_neg_1', 'Exposure Neg1', 'an optional tech field')
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
' loads the material-4.0 bootstrap
include('material-4.0/bootstrap')
' loads the ExposureNeg1 element
include('material-4.0/Image/ExposureNeg1')
ExposureNeg1('exposure_neg_1', 'Exposure Neg1', 'an optional tech field')
@enduml
```

