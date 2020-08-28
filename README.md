## Docker tutorial 

### Step 1

#### Command to get certificate files
openssl req -x509 -sha256 -nodes -newkey rsa:2048 -days 365 -keyout localhost.key -out localhost.crt