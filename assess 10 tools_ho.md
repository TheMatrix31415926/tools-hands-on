##### CLOUD HOSTING WORKFLOW WITH DIGITALOCEAN



###### Hosting Scenario:

Deploying a Personal Portfolio Website (HTML/CSS/JS or simple Node.js app)



###### WORKFLOW STAGES



* Server Creation (Droplet Setup)

Action: Create a Droplet in DigitalOcean by selecting OS (Ubuntu), plan (basic), and server size

Result: A live virtual server with public IP is created

Purpose: Provides the cloud environment to host the application

* Region Selection

Action: Choose the nearest data center region (e.g., Bangalore or nearby)

Result: Server is hosted in an optimal location with better speed and lower latency

Purpose: Ensures faster access and better performance for users

* Access \& Initial Setup

Action: Connect to server using SSH and install required software (NGINX/Node.js)

Result: Server is accessible and ready to run applications

Purpose: Prepares the server environment for deployment

* Application Deployment

Action: Upload website files or clone project from GitHub and start the server

Result: Application runs on the server and is accessible via IP/domain

Purpose: Makes the website live on the internet



###### SECURITY STEP



* Disable password login and use SSH key authentication
* Configure firewall (allow only ports 22, 80, 443)
* Purpose: Protects the server from unauthorized access



###### VERIFICATION STEP



* Open browser and visit server IP or domain
* Check if website loads correctly and all features work
* Purpose: Confirms successful deployment and availability



###### OUTCOME



* Website successfully hosted on cloud
* Secure and accessible server setup
* Reliable online presence for users

