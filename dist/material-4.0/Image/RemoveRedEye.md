# Remove Red Eye

```text
material-4.0/Image/RemoveRedEye
```

```text
include('material-4.0/Image/RemoveRedEye')
```

|icon|element|
|---|---|
|![](RemoveRedEye.png)|![](RemoveRedEye.element.png)|



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
' loads the RemoveRedEye element
include('material-4.0/Image/RemoveRedEye')
RemoveRedEye('remove_red_eye', 'Remove Red Eye', 'an optional tech field')
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
' loads the RemoveRedEye element
include('material-4.0/Image/RemoveRedEye')
RemoveRedEye('remove_red_eye', 'Remove Red Eye', 'an optional tech field')
@enduml
```

