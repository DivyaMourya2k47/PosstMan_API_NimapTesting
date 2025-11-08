# PosstMan_API_NimapTesting
PostMan API Testing Machine for Nimap Infotech


# Postman API Testing - Nimap Infotech Machine Test

 Base URL
https://testffc.nimapinfotech.com

Setup
1. Import the collection `Nimap_API_Test_Collection.json`
2. Import the environment `Nimap_Environment.json`
3. Select the environment in Postman
4. Run the following tests:
   - Login (Valid)
   - Login (Invalid)
   - Add Customer

 Tests Included
- Valid Login → stores token
- Invalid Login → verifies error message
- Add Customer → uses token for authentication

 Notes
The Invalid Login API returns 200 OK instead of 401, indicating a backend validation issue.  
Handled this case with a flexible test script.


**Created by:** Divya Mourya
