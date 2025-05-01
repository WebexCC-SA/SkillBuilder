# Understanding JSON



### Navigate to [JSON Path Finder](https://jsonpathfinder.com/){:target="_blank"}
   
### Exercise 1

1. Copy this text into the left pane of the JSON PathFinder
   >  <textarea cols="50" disabled style= "background-color: #ffffff">{"name":"John", "age":30, "car":null} </textarea>
2. Click Beautify
3. Click age
   > What is the JSON path for age? 
   >
4. Delete the contents of the left pane and copy this text into the left pane of the JSON PathFinder
   >
   >   <textarea cols="50" disabled style= "background-color: #ffffff">{"name":"John","age":30,"cars":["Ford","BMW","Fiat"]}</textarea>
5. Click Beautify
   > Click on cars and observe that there is an array.
   >
   > What is the JSON path for BMW?

### Exercise 2

1. Delete the contents of the left pane and copy this text into the left pane of the JSON PathFinder
   >  <textarea cols="70" rows = "8" disabled style= "background-color: #ffffff">{"name":"John Smith","sku":"20223","price":23.95,"shipTo":{"name":"Jane Smith","address":"123 Maple Street","city":"Pretendville","state":"NY","zip":"12345"},"billTo":{"name":"John Smith","address":"123 Maple Street","city":"Pretendville","state":"NY","zip":"12345"}}</textarea>
   >

2. Click Beautify
   > !!! Note 
      "shipTo" and "billTo" have additional JSON objects in them.
   >
   > What is the JSON path for the ship to state?
   >
3. Delete the contents of the left pane and copy this text into the left pane of the JSON PathFinder
   > <textarea cols="70" rows = "10" disabled style= "background-color: #ffffff">[{"name":"John Smith","sku":"20223","price":23.95,"shipTo":{"name":"Jane Smith","address":"123 Maple Street","city":"Pretendville","state":"NY","zip":"12345"},"billTo":{"name":"John Smith","address":"123 Maple Street","city":"Pretendville","state":"NY","zip":"12345"}},{"name":"Alice Brown","sku":"54321","price":199.95,"shipTo":{"name":"Bob Brown","address":"456 Oak Lane","city":"Pretendville","state":"HI","zip":"98999"},"billTo":{"name":"Alice Brown","address":"456 Oak Lane","city":"Pretendville","state":"HI","zip":"98999"}}]</textarea>
   >

4. Click Beautify
   > !!! Note 
      We now have an array of objects (0 and 1)
   >
   > What is the JSON path for Alice Brown's ship to state?

### Exercise 3

1. Delete the contents of the left pane and copy the raw text from this [Desktop Layout](sesson1Assets/Default%20Desktop%20Layout.json){:target="_blank"} into the left pane of the JSON PathFinder
2. Click Beautify
   > Does the agent desktop layout have the chat app enabled?
   >
   > What areas are listed in the supervisor desktop layout?
    
    ---
