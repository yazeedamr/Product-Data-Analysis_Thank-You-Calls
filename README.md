# Product-Data-Analysis_Thank-You-Calls
An analysis to evaluate the need for a "Thank You Call" Product Feature for an e-Commerce Application catered towards vacation stays.

The company sells flights and hotel stays through an automated process, where in just 2 texts, a customer can book their entire stay. The company has been experimenting with a bot calling customers after successfully completing their first stay to thank them for using its service. The goal of the analysis is to determine whether or not the calls provide any additional value based on a subset of customers whose first purchase was between 200-300 Canadian Dollars. 

The Data Dictionary for the accompanying dataset is as follows:

**User ID**

  Data Type: *int*
  
  Description: ID number for a unique user
  
**month**

  Data Type: *date*
  
  Description: Month of the user’s first booking
  
**thank_you_status**

  Data Type: *string*
  
  Description: Whether or not the company reached out to the user to say thank you for booking.
  
**LTR**

  Data Type: *float*
  
  Description: Lifetime revenue. Sum of all revenue generated from the user over their lifetime.
  
**bookings**

  Data Type: *integer*
  
  Description: Total number of lifetime bookings made by the user
  
**gmv**

  Data Type: *float*
  
  Description: Total gross merchandise volume of bookings made by the user (total cost of the rooms)

