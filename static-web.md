
Static Website deployed on AWS Linux EC2 Instance
![image](./Screenshots/ec2.png)

```
sudo apt update
sudo apt install nginx
sudo systemctl start nginx
sudo systemctl enable nginx
```
![image](./Screenshots/nginx.png)

static website accessible using the ec2 public IP listening on HTTP port :80 
```
http://34.229.149.15/
```

![image](./Screenshots/website%20up.png)