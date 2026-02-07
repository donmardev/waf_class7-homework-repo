**ReadMe**
EC2 Configuration Steps

1. Launch Instance: Go to the EC2 Dashboard and click "Launch instance".
2. Name & Image: Provide a name and select an Amazon Machine Image (AMI).
3. Instance Type: Choose t2.micro or t3.micro (free tier eligible) to avoid charges.
4. Key Pair: For this excersize, continue without a Key Pair.
5. Network & Security: To host a web server, allow HTTP (port 80) traffic.
6. Storage: The default 8 GB is sufficient for testing.
7. Advanced Settings: Copy and paste prewritten Script from Theo's github.
8. Launch: Click "Launch instance". 
9. Verification: From the Instance list, select the newly created instance and copy the Public DNS. Next, paste the public dns in a new tab prefaced with http://.

Teardown Instructions (To Avoid Costs) 

1. Terminate Instance: In the EC2 Dashboard, select the running instance.
2. Instance State: Click "Instance state" > "Terminate instance".
3. Confirm: Confirm termination to delete the instance and its associated root volume.
4. Cleanup Security Groups/Key Pairs: (Optional) Navigate to Network & Security in the sidebar to delete created Security Groups and Key Pairs.