# ProMISDocumentation
For keeping document in project

Mock API Portal:
https://anypoint.mulesoft.com/apiplatform/emxom/#/portals/organizations/a2079598-5713-432b-94fb-f86fbd31a5d2/apis/25285470/versions/962379/pages/273531

BaseURL:
http://document-api.cloudhub.io/mock/v1  
/documents/{docid} (GET_  
/sap/users (GET)  
/sap/users/{lanid} (GET)  
/sap/users/current (GET)  
/sap/dirs (GET) (POST)  
/sap/dirs/{docid} (GET)  
/sap/file (POST)  
/sap/file/{link}  

## Old DIR URL
`https://github.com/siamchamnangag/ProMISFileService/raw/master/src/main/resources/PMoC_complexity_and_effort_assessment.xlsx`

## /sap/file (POST) Request Body

```
{
  "filename":"docname.xml",
  "content":"content stream"
}
```
