# Static-website-using-AWS-Amplify-and-Route-53

**AWS Amplify and AWS Route53 to help us push our static website and host our static website**

Services::
<ul>
<li> AWS Route53 </li>
<li> AWS Amplify </li>
<li> Github(code htmls css js) </li>
</ul>

**Step1:**

a)Navigate to Amplify and create new app.

![Screenshot 2025-06-07 223852](https://github.com/user-attachments/assets/a6598437-47f4-432c-b9a0-84d9ebe76c0e)

b)Choose GitHub for code Provider.

c)Choose Repositories

![Screenshot 2025-06-07 223931](https://github.com/user-attachments/assets/cf02a255-a389-407f-8193-88d67bd7e4a4)


d)Save and Deploy

![Screenshot 2025-06-07 224015](https://github.com/user-attachments/assets/6cbbd091-dc81-481e-8107-3842ccaaf810)


**Step2:**

a)Navigate to the AWS Route53 Console and click on Hosted Zones on the left.

b)Click on the button that says Create hosted zone.

c)Complete DNS Configrution with Domain provider.

d)Navigate to the AWS Amplify Console and select the Amplify App

e)On the left, select Custom domains.

f)click the button that says Add domain.

![Screenshot 2025-06-07 224102](https://github.com/user-attachments/assets/a207e89f-025c-42bf-a4be-8189aa3bf7ac)


g)choose Domain name previously Configured using Route53

![Screenshot 2025-06-07 224120](https://github.com/user-attachments/assets/25ccc170-fad0-45ce-9567-20c9ea4e5f8c)

h)For the section Custom SSL Certificate, click on Amplify managed certificate. 

i)Click on the  button at the bottom right to Add domain.

![Screenshot 2025-06-07 224240](https://github.com/user-attachments/assets/afabe781-9174-4c70-9c3a-a8b3334456bc)

j)Give it some time for Amplify to create the connection to the Route53 domain and adding the TLS/SSL certificate

![Screenshot 2025-06-07 224343](https://github.com/user-attachments/assets/c577a9aa-fdf8-48ad-8b9d-e7df753e4186)

Then type your domain address in any browser and it's done!!

![Screenshot 2025-06-08 182658](https://github.com/user-attachments/assets/f39223af-574a-4a14-9965-73dc63b848c9)




