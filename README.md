DOCUMENTATION

I started by launching an EC2 instance on AWS using the Ubuntu image, selecting the t2.micro instance type for testing purposes. 

After which, i created a new Key Pair (project1.pem) for SSH access and configured a security group to allow SSH on port 22 and HTTP on port 80.

Once the instance was up, I connected to it on my terminal via SSH. 

Then, I installed the Apache web server by first updating the package lists and then installing Apache. I started the Apache service and set it to automatically start on boot.

Next, I deployed a simple HTML page i created with my full bio and other neccessary information by SSH-ing into the instance and placing the index.html file in the Apache server's root directory. 

After that, I tested the page by accessing the EC2 public IP address(http://54.170.22.238/) and verified the page loaded correctly.

After which i created a repository and pushed the index.html file to Github.

<img width="937" alt="Screenshot 2024-12-22 at 03 18 09" src="https://github.com/user-attachments/assets/a8d76555-1d25-4c45-a15a-98c6569bd406" />
