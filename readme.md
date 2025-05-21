# Java-React Example

This project demonstrate running a java application on Digital droplet server

## **Project Overview**
- Setup server on DigitalOcean
- Deploy App on Droplet
- Create a Linux User

## **Install dependencies**
- Created a DigitalOcean account (Free Tier)
- Created a Droplet
- Configured Firewall rule to open port 22 for your IP address
- Connected to Droplet
- Installed Java on Droplet

## **Diagrammatic Presentation**

- Install Java

 ![image](https://github.com/user-attachments/assets/aa05e266-25e8-4465-a842-4c2a18505278)


## **Deploy Application on Droplet**
- Built Jar File with gradle
 ![image](https://github.com/user-attachments/assets/b49b06b4-17ba-4a14-8848-1be5ae490488)

- Copied to remote Server (Droplet)
 ![image](https://github.com/user-attachments/assets/16b02d42-6d8e-47ce-9497-a277df6f5e9c)

- Run App on Droplet
- Configured Firewall Rule to open port 7071 to access App via browser
  
  ![image](https://github.com/user-attachments/assets/c9192650-dc4d-4ec7-bbf6-c4b3cda4149c)

- Access the application on the url
  ![image](https://github.com/user-attachments/assets/a40ba18e-abde-4d85-bcd8-7ef33039a7e3)


  ![image](https://github.com/user-attachments/assets/291c4d69-33aa-47dc-99cf-3d1d2238f022)

- To check if process is running on the terminal

  ![image](https://github.com/user-attachments/assets/24c6ed71-d0b4-436f-856a-96b580805459)

- To see the port the application is runing using netstat -lpnt (List only the servers that have active internet connection)
  
  ![image](https://github.com/user-attachments/assets/fd2e76af-0c32-491b-a753-79a5717acd26)

  

## **Create a Linux User on the droplet**
- Added User and new User to sudo group
  ![image](https://github.com/user-attachments/assets/da37360f-68eb-4f60-8315-551cdc5221f9)


  ![image](https://github.com/user-attachments/assets/0db6c2c0-a830-4697-bbed-3600ecefd9d0)


  ![image](https://github.com/user-attachments/assets/52e898cf-1a0c-4af2-a1f9-23e4be2439ee)


- Created .ssh folder with ssh key for new User

  ![image](https://github.com/user-attachments/assets/b6422dd5-acb1-4e23-9c09-4ccd1f550dc9)



 
