<img src='cdologo.jpeg'>
<!--meta property=“og:image” content=“cdologo.jpeg ” /> 
<meta property=“og:image” content=“cdologo.jpeg ” /--> 
<h1>openCDO</h1><h3>
 main site can be found at https://opencdo.onrender.com
 We are the Cyber Defense Organization, a completely open source security service that is starting off simple from here
 <hr>
You will need to put the code below into your file for verification.
 <hr>   
When we set it up you can join our hard working team of volunteers
</h3>

```html
<!DOCTYPE html>
<html>
<head>
  <title>Parent Window</title>
<script>
    function sendParentURL() {
     const iframe = document.getElementById('myIframe');
     iframe.contentWindow.postMessage(window.location.href, '*');
    }
    
   window.onload = sendParentURL;
</script>
</head>
<body>
    <iframe id="myIframe" src="https://opencdo.onrender.com/sites"></iframe>
</body>
</html>
```
we will also have ways for companies to contact about having their website being put on the list of trusted sites
