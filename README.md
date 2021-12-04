# Product-Management-APIs (MongoDB)
<h3> Product Management APIs using Express Router and MongoDB.</h3>

<h3>SCHEMA: </h3>

  <h4><------ PRODUCT ------></h4>
  <ul>
    <li> product id : String </li>
    <li> title : String </li>
    <li> price : String </li>
    <li> category : Array of String </li>
    <li> company id : String </li>
    <li> seller id : Array of String </li>
  </ul>
  
  <h4><------ COMPANY ------></h4>
  <ul>
    <li> company id : String </li> 
    <li> name : String </li> 
    <li> product ids : Array of String </li> 
  </ul>
  
  <h4><------ SELLER ------></h4>
  <ul>
    <li> seller id : String </li> 
    <li> name : String </li> 
    <li> product ids : Array of String </li> 
  </ul>

<h3>POST REQUESTS:- </h3>
  
  <h4><------ ADD ------></h4>
  <ul>
    <li> add new company </li> 
    <li> add new seller </li> 
    <li> add new product </li> 
  </ul>

  <h4><------ RETRIEVE ------></h4>
  <ul>
    <li> fetch company details based on product name </li> 
    <li> fetch seller details based on product name </li> 
    <li> fetch all products of a company </li>  
    <li> fetch all products of a seller </li> 
  </ul>

  <h4><------ UPDATE ------></h4>
  <ul>
    <li>update company (add/remove products) </li>
    <li>update seller (add/remove products) </li>
    <li>update product (add/remove category) </li>
  </ul>

  <h4><------ DELETE ------></h4>
  <ul>
    <li> delete company </li>
    <li> delete seller </li>
    <li> delete product </li>
  </ul>

