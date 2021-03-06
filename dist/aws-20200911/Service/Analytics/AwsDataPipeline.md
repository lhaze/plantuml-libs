# Aws Data Pipeline

```text
aws-20200911/Service/Analytics/AwsDataPipeline
```

```text
include('aws-20200911/Service/Analytics/AwsDataPipeline')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsDataPipeline.png)|![](AwsDataPipeline.card.png)|![](AwsDataPipeline.element.png)|![](AwsDataPipeline.group.png)|



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
' loads the AwsDataPipeline element
include('aws-20200911/Service/Analytics/AwsDataPipeline')
AwsDataPipelineCard('aws_data_pipeline', 'Aws Data Pipeline', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsDataPipeline element
include('aws-20200911/Service/Analytics/AwsDataPipeline')
AwsDataPipelineCard('aws_data_pipeline', 'Aws Data Pipeline', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsDataPipeline element
include('aws-20200911/Service/Analytics/AwsDataPipeline')
AwsDataPipeline('aws_data_pipeline', 'Aws Data Pipeline', 'an optional tech field')
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
' loads the AwsDataPipeline element
include('aws-20200911/Service/Analytics/AwsDataPipeline')
AwsDataPipeline('aws_data_pipeline', 'Aws Data Pipeline', 'an optional tech field')
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
' loads the AwsDataPipeline element
include('aws-20200911/Service/Analytics/AwsDataPipeline')
AwsDataPipelineGroup('aws_data_pipeline', 'Aws Data Pipeline', 'an optional tech field'){
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
' loads the AwsDataPipeline element
include('aws-20200911/Service/Analytics/AwsDataPipeline')
AwsDataPipelineGroup('aws_data_pipeline', 'Aws Data Pipeline', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

