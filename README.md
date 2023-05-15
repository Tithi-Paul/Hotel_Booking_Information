# Hotel_Booking_Information_Rest_API_Newman
## How to run this project
- Clone this project
* Open with Postman / Command Shell
- Run Command:
>

    newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
- Run Command for Report:
>

    newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
## Technology used:
- Postman
- Newman
## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library
## Newman and Report Installation Process:
- Newman Install Command:
>

    npm install -g newman-reporter-htmlextra

- Newman Html Report Install Command:
>

    npm install -g newman-reporter-htmlextra
    
## API Documentation:
- [https://documenter.getpostman.com/view/13082503/2s93Xwz4Az](https://documenter.getpostman.com/view/27152421/2s93ecxW8e)
## Test case list:
1. Create Guest Info in a Hotel

    > Create Data Sets Using the Dynamic Random Variables.
  
2. Verify Crated Guest Details

    > In the test case you need to validate the following field values:
        
      - First Name
      - Last Name 
      - Total Cost
      - Bill Paid/not
      - Booking Date
      
          - CheckIn Date
          - CheckOut Date
          
      - Additional Needs ( Breakfast/Lunch/Dinner )
      
3. Update Guest Info in a Hotel


    > Modify Data Sets Using the Dynamic Random Variables
        
      
4. Verify Updated Guest Details

    > In the test case you need to validate the following field values:
        
      - First Name
      - Last Name 
      - Total Cost
      - Bill Paid/not
      - Booking Date
      
          - CheckIn Date
          - CheckOut Date
          
      - Additional Needs ( Breakfast/Lunch/Dinner )
    
5. Delete Guest Info in a Hotel


    > In the test case you need to validate the following field values:
        
      - Only Message
      




