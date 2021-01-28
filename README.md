# springboot-with-paytm-integration demo project.

#Download paytm-checksum-2.0.0.jar form https://nexus-repo.egovernments.org/nexus/content/repositories/releases/com/paytm/paytm-checksum/2.0.0/ 
Put that jar into buildpath/classpath. For convenience I’d kept that jar in “springboot-paytm-integration-demo” folder.

#Create your paytm account, and login at https://developer.paytm.com/docs , Also ensure your paytm developer app is in activated mode. Generate your own unique API keys such as merchant id, merchant key. Collect your own Paytm registered mobile no. and Paytm registered email while doing sign up, and put it in your “application.yml” file. Now after writing code, run it as spring boot app.

#Go to browser hit : http://localhost:9191/

#Fill the form details like – <br> OrderId as “001”, <br> CustomerId as “cust001”, <br> Industry_type_id as “Retail”, <br> and Channel as “WEB”, <br> 'Amount' what ever you want to pay say 1 rupee. <br> 

Now click on pay with Paytm. It will redirect you to Paytm gateway.

#Now proceed the Paytm payment with either debit/credit/NetBanking and then do OTP verification with paytm gateway. After success you’ll get receipt. 
