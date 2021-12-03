# Phishing
For ethical hacking techniques on how to create phishing emails and websites.

## Phishing websites
Phishing websites can be created using blackeye. 
1. Download blackeye ``` git clone https://github.com/An0nUD4Y/blackeye```
2. Download ngrok with steps 1 and 2 of this page: https://dashboard.ngrok.com/get-started/setup
3. Run black eye ``` cd blackeye``` ```sudo ./blackeye.sh```
4. Run ngrok ```./ngrok http 8080
5. Run site: ```cd blackeye/sites/instgram``` ```php -S localhost:8080```
A site is ran: 
![image](https://user-images.githubusercontent.com/39514108/144540427-1665c79c-c533-4f5b-80b2-917954cdc7d6.png)
The credentials are also captured when a user enters it:
![image](https://user-images.githubusercontent.com/39514108/144540467-6a704d41-2406-45bc-9729-e6b257710d3c.png)

## Phishing Emails

To send the link in a legitimate form, an email can be crafted using social engineering toolkit provided in kali. Use mass mailing and spear phishing as the conduct. Then craft the email in a legitimate form. The following shows a crafted email:
![image](https://user-images.githubusercontent.com/39514108/144540413-cf08ebe5-e991-4070-bf73-d20fdf7dafa0.png)
