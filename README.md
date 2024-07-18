# msrv-chat-front

### INIT

`npx create-react-app <project-name>`       

`npm install react-router-dom`      
router library      

`npx generate-react-cli component <component-name>`     
auto generate component files       

`npm start`     
start developement server       

## jquery usage in react
```
npm install jquery --save  
npm i --save-dev @types/jquery  
```
Then at components file
```javascript
import $ from 'jquery'
$("button").click(function(){
    $.get("demo_test.asp", function(data, status){
        alert("Data: " + data + "\nStatus: " + status);
    });
});
```

### TIPS        
href="/somepage" - is absolute reference        
href="somepage" - is relative reference will be actualpage/somepage     

### KNOW ISSUE      

when trying update imediatly after a insert variable "found" not have time to update   
