## **PAY-0001:** Efficient Order Processing Testing - Payment  

> **Summary:** Verify that payment made is succesful and displayed succesfully.  <br>

**Preconditions:** Must be logged in  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |Go to payment screen      | Verify that user is in payment screen   | 
 |  2 |Choose payment method      | Verify that payment is selected   | 
 |  3 |Click pay button    | Verify that pay button is clicked succesfully   |  

**Post-conditions:**  

 - Payment notification should be sent to email or phone number.  
 - Tenant payment tracker must be reset or have a checked mark  
 - Landlord side payment tracker must also be modified that the tenant has paid bills for that month  
