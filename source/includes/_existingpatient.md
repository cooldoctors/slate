

# Existing Patient

## Verify Existing Patient 

Verify if the patient is an existing registered user and has credentials. 


```shell
curl -i -H "Content-Type: application/json" "http://localhost:8080/DoctorOnDemand/api/auth/checkExistingEmail" -X POST -d '{"email":"mit4079@gmail.com"}'

```
> The above command returns JSON structured like this:

```json
{
  "success": "true"
}
```
### HTTP Request

`POST http://localhost:8080/DoctorOnDemand/api/auth/checkExistingEmail/
`
### Query Parameters

Parameter |  Description | Type | Optional/Required
--------- | ------------ | ---- | ----------------
Email | Patient Email address | String | Required

### Response

Parameter |  Description | Type 
--------- | ------------ | ---- 
Success | True | boolean 


<aside class="notice">
 Correct email will verify register user!
</aside>


