# ProMISDocumentation

Project documentation

## Mock APIs

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

## Stubby4j

- Download --> http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22io.github.azagniotov%22%20AND%20a%3A%22stubby4j%22
- Manual (Eng) --> https://github.com/azagniotov/stubby4j/blob/master/README.md
- Manual (Tha) --> http://www.somkiat.cc/stub-http-server-stubby4j/

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
