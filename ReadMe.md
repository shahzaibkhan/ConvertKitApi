Example Usage:
```PHP
include "ConvertKitApi.php"; //Change this as per the path you are placing
$convertKit = new ConvertKitApi('YOUR API HERE');
$convertKit->subscribeToAForm('FORMID/FORMCODE', 'EMAILADDRESS');
