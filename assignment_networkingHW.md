# Networking in GCP - IPs and Domain Management #

## Create a VPC ##

After logging on to GCP, it was easy to navigate the VPC network button to create a VPC network. The range selected was northamerica-northeast1

<img width="950" alt="image" src="https://github.com/user-attachments/assets/0a53f57e-9ca1-4aae-92f7-1707c2710e9a">

For range, I used the standard range that GCP had recommended. Everything else remained off.

<img width="288" alt="image" src="https://github.com/user-attachments/assets/f374ce09-9418-4f9c-b0ec-82fa997eecd6">

I kept the Dynamic Routing mode set to **regional** and left the best path selection mode as **legacy**

<img width="325" alt="image" src="https://github.com/user-attachments/assets/373e2745-d54e-48da-90cf-6db90f86069a">

## Assign a Dedicated IP ##

Following the drop-down menu, I easily navigated to the **IP Addresses** section and selected the option to reserve an external IP address 

<img width="641" alt="image" src="https://github.com/user-attachments/assets/04ec23f8-5c10-45c8-a495-a869cfafb5ac">

I left everything auto-filled as is and updated the region to fit my VPC

<img width="448" alt="image" src="https://github.com/user-attachments/assets/c65776fc-db9c-4cef-b9e5-e16cf067f3c5">

The creation of the reserve was successful 

<img width="593" alt="image" src="https://github.com/user-attachments/assets/14595f49-3f05-48f6-ba3e-a27e200965d6">

## Map IP to a Domain ## 

I was having trouble using the Google Cloud DNS to mpa the reserved IP address to a domain name 

<img width="638" alt="image" src="https://github.com/user-attachments/assets/db510ef0-93af-4059-84cc-89f3054d8211">

