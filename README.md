# Sample API

<Start add a description of the API There ...>

  
## **`GET`  &nbsp; UseCase title**
  
<Start describe what this usecase aim for ...>
  
  
```
GET /vx/correct-path
```

**Input params**

Name | Type | In | Required | Description
:--- | :--- | :--- | :--- | :--- 
`accept` | string | header | `true` | allow to return data in your expected format
  
**Success response &nbsp; `200`**

```
  Status Code:  200  OK
```

```JSON
{
  "id": "43ng55inr3inbi",
  "name": "Giovani Santos"
}
```
  
**Not found &nbsp; `404`**
  
```
Status Code: 404  NOT_FOUND
```

```JSON
{
  "status": 404,
  "message": "parcel not found",
  "code": 404001,
  "dev": "detailed message for developper",
  "moreInfo": "error url"
}
```
  

### Sample Object
  
<Description of the sample object ...>
 
