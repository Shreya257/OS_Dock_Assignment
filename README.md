# OS_Dock_Assignment | Sem 5
Assignment2:

Question:

Create a Docker-compose yaml for the following Multi-container app (Drupal postgres)

contianer1 (front-end)

Front-end image - drupal:8-apache

Container port - 80

volumes 

    - /var/www/html/modules
    
    - /var/www/html/profiles
    
    - /var/www/html/themes
    
    - /var/www/html/sites
    
contianer2(database)

Back-end image - postgres:10

environment variable - POSTGRES_PASSWORD: example

Note: Bring up both the containers on same user defined bridge network

SCREENSHOTS:
![2020-12-30 (12)](https://user-images.githubusercontent.com/76741091/103317515-67403680-4a51-11eb-903a-9acb26969430.png)
![2020-12-30 (13)](https://user-images.githubusercontent.com/76741091/103317517-6909fa00-4a51-11eb-81a1-56563da29602.png)
![2020-12-30 (14)](https://user-images.githubusercontent.com/76741091/103317519-6a3b2700-4a51-11eb-8ac0-e3fb917d2bf6.png)
![2020-12-30 (15)](https://user-images.githubusercontent.com/76741091/103317520-6a3b2700-4a51-11eb-9358-d657f3041da3.png)
![2020-12-30 (6)](https://user-images.githubusercontent.com/76741091/103317521-6ad3bd80-4a51-11eb-9eaf-ac368faed103.png)
![2020-12-30 (8)](https://user-images.githubusercontent.com/76741091/103317523-6b6c5400-4a51-11eb-9664-5d53b969ffda.png)
![2020-12-30 (9)](https://user-images.githubusercontent.com/76741091/103317524-6b6c5400-4a51-11eb-82f0-223379b0ce32.png)
