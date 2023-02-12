# Task 2

##  Deploy django app
- Download the code https://github.com/mahmoud254/Booster_CI_CD_Project
- create instance then adjust security group to allow traffic on port 8000 

![ec2](https://user-images.githubusercontent.com/63955669/218327393-12dd5c0c-e500-43ad-963f-5afbafc4397d.png)

``` bash 
   ansible-playbook playbook.yaml -i inventory.txt
```
![Screenshot from 2023-02-12 19-15-14](https://user-images.githubusercontent.com/63955669/218327395-1ff86403-919a-4213-9f5d-3d291b882ea2.png)

- edit settings.py to allow host from public ip 

![host](https://user-images.githubusercontent.com/63955669/218327462-125d307f-f642-47bb-8477-19fb12fad352.png)

![django](https://user-images.githubusercontent.com/63955669/218327468-44625536-3af2-43b1-809c-2bf61cba1e0a.png)
