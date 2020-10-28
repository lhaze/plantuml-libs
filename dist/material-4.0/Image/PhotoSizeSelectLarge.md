# Photo Size Select Large

```text
material-4.0/Image/PhotoSizeSelectLarge
```

```text
include('material-4.0/Image/PhotoSizeSelectLarge')
```

|icon|element|
|---|---|
|![](PhotoSizeSelectLarge.png)|![](PhotoSizeSelectLarge.element.png)|



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
' loads the PhotoSizeSelectLarge element
include('material-4.0/Image/PhotoSizeSelectLarge')
PhotoSizeSelectLarge('photo_size_select_large', 'Photo Size Select Large', 'an optional tech field')
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
' loads the PhotoSizeSelectLarge element
include('material-4.0/Image/PhotoSizeSelectLarge')
PhotoSizeSelectLarge('photo_size_select_large', 'Photo Size Select Large', 'an optional tech field')
@enduml
```
