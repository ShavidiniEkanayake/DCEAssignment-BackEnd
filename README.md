# DCE - BackEnd

Please follow the instructions given below and build a sample API Using .NET Core with ADO.NET.
1) Complete This Practical Using .NET Core with ADO.NET.

2) Create SQL Table Named Customer with below mentioned fields.
  A. UserId (guid) - Primary Key
  B. Username (string (30))
  C. Email (string (20))
  D. FirstName (String (20))
  E. LastName (String (20))
  F. CreatedOn (DateTime)
  G. IsActive (Boolean)
  
3) Create SQL Table Named Order with below mentioned fields
  A. OrderId (guid) -Primary Key
  B. ProductId(Guid) - Foreign Key to Product Table
  C. OrderStatus(int (1))
  D. OrderType (int (1))
  E. OrderBy (Guid) Foreign Key to User Table
  F. OrderedOn (DateTime)
  G. ShippedOn (DateTime)
  H. IsActive (Boolean)
  
4) Create SQL Table Named Product with below mentioned fields
  A. ProductId (guid) -Primary Key
  B. ProductName (string (50))
  C. UnitPrice(decimal)
  D. SupplierId (Guid) Foreign Key to Supplier Table
  E. CreatedOn (DateTime)
  F. IsActive (Boolean)
  
5) Create SQL Table Name Supplier with below mentioned fields.
  A. SupplierId (guid)
  B. SupplierName (string (50))
  C. CreatedOn (DateTime)
  D. IsActive (Boolean)
  
6) Create Web API endpoints for following scenarios.
  A. Create Customer (POST)
  B. Get All Customers (GET)
  C. Update Customer (POST)
  D. DELETE Customer (DELETE)
  E. Active Orders by Customer (GET) 
API response should contain supplier & Product details.

7) Use ADO.NET for 6.A, 6.B, 6.C & 6.D as Data access.

8) Create Stored procedure for 6.E to get required data from SQL.

Submit API Request collection (postman export) and required DB Scripts with your code.
