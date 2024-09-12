# cURL Commands and JSONs

The next topics present information on the following service operations:
- Read Employee Information
- Create Employee


## Read Employee

The following example provides a request and successful response to the operation **Read Employee Information**.


### Request:

**Method:** GET

**cURL Command:** curl -X GET "https://dummy.restapiexample.com/api/v1/employee/{id}"

**Example (Using {id} as 1):** curl -X GET "https://dummy.restapiexample.com/api/v1/employee/1"



### Response Status:
200

### Successful Response:
**Type/Format:** JSON

    {
      "status": "success",
      "data": {
        "id": 1,
        "employee_name": "Tiger Nixon",
        "employee_salary": 320800,
        "employee_age": 61,
        "profile_image": ""
      },
      "message": "Successfully! Record has been fetched."
    }






## Create Employee

The following example provides a request and successful response to the operation **Create Employee**.

### Request:

**Method:** POST

**cURL Command:** curl -X POST "https://dummy.restapiexample.com/api/v1/create"

**Type/Format:** JSON

    {
      "status": "success",
      "data": {
        "id": 30,
        "employee_name": "Felipe Barcelos",
        "employee_salary": 156000,
        "employee_age": 31,
        "profile_image": ""
      }
    }

### Response Status:
201

### Successful Response:
**Type/Format:** JSON

    {
        "status": "success",
        "data": {
            "status": "success",
            "data": {
                "id": 30,
                "employee_name": "Felipe Barcelos",
                "employee_salary": 156000,
                "employee_age": 31,
                "profile_image": null
            },
            "id": 283
        },
        "message": "Successfully! Record has been added."
    }



## HTTP Status Codes

The following list provides general information on the HTTP Status Codes.


- **200 OK:** Successful retrieval of data.
- **401 Unauthorized:** Authentication credentials were missing or invalid.
- **403 Forbidden::** The server understood the request, but refused to fulfill it due to authorization reasons.
- **404 Not Found:** The resource specified by {id} was not found.
















