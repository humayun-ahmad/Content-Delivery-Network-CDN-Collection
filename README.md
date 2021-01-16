# Content-Delivery-Network-CDN-Collection


#For Adding Sweat Alert:

**Adding into header part:**
```
<head>
<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/sweetalert/1.1.3/sweetalert.min.css">
</head>
```
**onclick="sweet()" must be the there:**
```
<button onclick="sweet()">Sweet Alert</button>
```

**Adding this part before closing body tag:**
```
<script src="https://cdnjs.cloudflare.com/ajax/libs/sweetalert/1.1.3/sweetalert.min.js"></script>
<script type="text/javascript">
    function sweet() {
        swal({
            title: "Are you sure?",
            text: "Your will not be able to recover this imaginary file!",
            type: "warning",
            showCancelButton: true,
            confirmButtonClass: "btn-danger",
            confirmButtonText: "Yes, delete it!",
            closeOnConfirm: false
        },
        function(){
        swal("Deleted!", "Your imaginary file has been deleted.", "success");
        });
    }
</script>
```
You can flow this [Github page](https://gist.github.com/alfenfebral/4dc1f04ce1a779d62bbaa8292f751930)
