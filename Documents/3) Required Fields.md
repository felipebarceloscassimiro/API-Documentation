# Employee Management API Fields

## Field Specifications

The following table provides details on the required fields utilized by the Employee Management API.


| Field | Type | Description | Mandatory |
|----------------|------|-------------|-----------|
| employee_age | Integer | It informs the employee age. | Yes |
| employee_name | String | It informs the employee name. | Yes |
| employee_salary | Number | It informs the employee salary. | Yes |
| id | Integer | It informs the ID number of a given employee. | Yes |
| profile_image | String | It presents the employee picture. | Yes |


## Next Release Scope

In order to further develop the Employee Management API, the following fields are planned for the next Employee Management API release:



| Field | Type | Description | Mandatory |
|----------------|------|-------------|-----------|
| time_employed | Integer | It informs the total number of days a given employee has been employed. | Yes |
| birthday | String | It informs the birthday of a given employee. | Yes |
| vacation_days | Integer | It informs how many vacation days a given employee has. | Yes |
| employee_of_the_month | Boolean | It indicates if a given employee has been granted the "Employee of the Month" award.  | Yes |
| languages_spoken | Array | It informs which languages the employee can speak.  | Yes |
| linkedin_profile | String | It informs the employee LinkedIn Profile. | No |
| key_ability | String | It informs key abilities that the employee posses. | No |


The following is an example of a POST request for the enhanced Employee Management API:

    {
      "status": "success",
      "data": {
        "id": 30,
        "employee_name": "Felipe Barcelos Cassimiro",
        "employee_salary": 156000,
        "employee_age": 31,
        "profile_image": "",
        "time_employed": 14,
        "birthday": "29/06/1993",
        "vacation_days": 0,
        "employee_of_the_month": true,
        "languages_spoken": ["portuguese", "english"],
        "linkedin_profile": "www.linkedin.com/in/felipe-barcelos-cassimiro-09165a223",
        "key_ability": "A quick learner and proactive, Felipe Barcelos Cassimiro was able to research and learn Markdown/Nextra Framework concepts, delivering high-quality work in a matter of days."
      }
    }


