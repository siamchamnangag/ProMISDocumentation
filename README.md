# ProMISDocumentation

Project documentation

## Acceptance Test Cases

| # | DocID | User | oldDIR | DocID | Description | Status | User | Link | newDIR | DocID | Description | Status | User | Link | message |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 1 | NGOLAMA | | 1 | PMoC | RE | PWP | [PMoC_complexity_and_effort_assessment.xlsx](https://github.com/siamchamnangag/ProMISFileService/raw/master/src/main/resources/PMoC_complexity_and_effort_assessment.xlsx) | | 101 | PMoC | IW | NGOLAMA | [PMoC_yyyyMMddHHmmss.xlsx](https://github.com/siamchamnangag/ProMISFileService/raw/master/src/main/resources/PMoC_yyyyMMddHHmmss.xlsx) | Document is created. |
| 2 | 2 | NGOLAMA | | | | | | | | | | | | | Document not found. |
| 3 | 3 | XXX | | | | | | | | | | | | | User not found. |
| 4 | 4 | NGOLAMA | | 4 | fail | RE | PWP | [PMoC_complexity_and_effort_assessment.xlsx](https://github.com/siamchamnangag/ProMISFileService/raw/master/src/main/resources/PMoC_complexity_and_effort_assessment.xlsx) | | | | | | | Upload failed. |

## Mock APIs

Mock API Portal:
https://anypoint.mulesoft.com/apiplatform/emxom/#/portals/organizations/a2079598-5713-432b-94fb-f86fbd31a5d2/apis/25285470/versions/962379/pages/273531

BaseURL:
http://document-api.cloudhub.io/mock/v1  
NewBaseURL:
http://doc-api.cloudhub.io/mock/v1/
/documents/{docid} (GET_  
/sap/users (GET)  
/sap/users/{lanid} (GET)  
/sap/users/current (GET)  
/sap/dirs (GET) (POST)  
/sap/dirs/{docid} (GET)  
/sap/file (POST)  
/sap/file/{link}  

## Design

## Testing

### Test Results
![results](http://imgur.com/8uQj6Or.png)

### Test Screenshot

Document is created (document_id = 1)
![id=1](http://imgur.com/WIiizJ0.png)

Document is not found (document_id = 2)
![id=1](http://imgur.com/qtoyrmO.png)

Upload failed (document_id = 3)
![id=1](http://imgur.com/0QlvWf6.png)
