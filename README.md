## Docker tutorial 

### Step 1

#### Command to get certificate files
openssl req -x509 -sha256 -nodes -newkey rsa:2048 -days 365 -keyout localhost.key -out localhost.crt
#### Command to enter test container
docker exec -it php_test bash
#### Write file on commandline
echo "<?php php_info()" > index.php
#### Temporary work around Chrome Security
chrome://flags/#allow-insecure-localhost