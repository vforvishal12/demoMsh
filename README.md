# demoMsh
Demo msh interview project using Spring Boot and H2


>> Employee Service 
EndPoint -  localhost:9092/msh/employees

Example -
GetEmployeeById - localhost:9092/msh/employees/1

   {
    "employeeId": 1,
    "employeeName": "TEST_EMPLOYEE",
    "departmentName": "TEST_DEPARTMENT",
    "organizationName": "TEST_ORGANIZATION",
    "organizationAddress": "TEST_ORGANIZATION_ADDRESS"
  }
  
  
  ----------------------------------------------------------------------------
  
  >> Department Service 
EndPoint -  localhost:9091/msh/departments

Example -
GetDepartmentById - localhost:9091/msh/departments/1

{
    "id": 1,
    "name": "TEST_DEPARTMENT",
    "organizationId": 1,
    "organization": {
        "name": "TEST_ORGANIZATION",
        "address": "TEST_ORGANIZATION_ADDRESS"
    }
}

  ----------------------------------------------------------------------------
  
  >> Organization Service 
EndPoint -  localhost:9090/msh/organizations

Example -
GetOrganizationById - localhost:9090/msh/organizations/1


{
    "id": 1,
    "name": "TEST_ORGANIZATION",
    "address": "TEST_ORGANIZATION_ADDRESS"
}


  ----------------------------------------------------------------------------
    >> Eureka Server 
   
 EndPoint -    localhost:9003










