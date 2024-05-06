
# Student_Rest_API_Testing

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 

newman run Lopachowdhury.postman_collection.json -e lopachowdhury.postman_environment.json
```
- Run Command for Report: 
```console 
newman run Lopachowdhury.postman_collection.json -e lopachowdhury.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman


## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/29253980/2sA3JGgjCb

## Test case list:
1. ### Get Student
	> In the test case you need to validate the status code value.

2. ### Create Student
	> Create data sets using the dynamic random variables and in the test case you need to validate the status code value.

3. ### Get Specific Student Details
	> In the test case you need to validate the following field values:
    1. > Status Code
 	2. > First Name
 	3. > Middle Name
 	4. > Last Name
 	5. > Date of Birth


4. ### Create Technical skills 

	> In the test case you need to validate the following field values:
    1. > Status Code

5. ### Create Student Address
	> In the test case you need to validate the following field values:
    1. > Status Code
	1. > Only Message

6. ### Get the Student's Full Details
	> In the test case you need to validate the following field values:
    1. > Status Code
	2. > Language
	3. > Year Of Experience
	4. > House Number
	5. > City
	6. > Country
	7. > Mobile
	8. > Current Address
	
## Newman Report Summary:


![Screenshot_6-5-2024_143633_](https://github.com/Lopachowdhury/Api-Testing/assets/139904174/55895e6c-7c20-4134-9d1e-cd4846e6c7d1)



![Screenshot_6-5-2024_14374_](https://github.com/Lopachowdhury/Api-Testing/assets/139904174/743f0efe-07ed-4fe7-8cb0-4805bbfd395a)
