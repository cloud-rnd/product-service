You can choose profile environment on runtime such as local, dev, staging, prod 
  -Dspring.profiles.active=dev 

You can start up defining port number on runtime 
  -Dport=8201

Usage: 
java -Dspring.profiles.active=dev -Dport=8201 -jar product-service-xxx.jar 
