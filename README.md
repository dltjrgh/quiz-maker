# **Quiz-maker**

- Quiz-maker is an web application that classifies and digitizes workbook question images using the OCR technology.
- As the user upload the question image, the components of the question are classified and read through a deep-learning model.
- You can also check the [Demo Video](https://drive.google.com/file/d/1ds0OtsfHtQU73apmXCc4GG05eo-xNcXv/view?usp=sharing)
<br>

## :zap: Tech Stack
```
- Frontend: React, Javascript ES6+, Bootstrap
- Backend: Flask 1.1.2, Python 3.7.6, Postman, Swagger
- Database: MongoDB
- Model: Pytorch, YOLOv5
- Development: AWS, Amazon S3 Bucket, Docker
- Monitoring: Prometheus, Grafana
```

|Frontend|Backend|Database / Model|Development|Monitoring|
|:------:|:------:|:---:|:----:|:---:|
|![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)<br>![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)<br>![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=black)<br>|![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)<br>![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)<br>![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=black)|![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)![Pytorch](https://img.shields.io/badge/Pytorch-EE4C2C?style=for-the-badge&logo=Pytorch&logoColor=white)|![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)<br>![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=Amazon-S3&logoColor=black)![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)|![Swagger](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white)
<br>

## **📝 Installation**

### **💡 API** Setup

- .Backend/s3.py

  ```python
  APPKEY = 'Kakao OCR Rest API URL'
  AWS_ACCESS_KEY = 'AWS ACCESS KEY'
  AWS_SECRET_KEY = 'AWS SECRET KEY'
  BUCKET_NAME = 'WS S3 Bucket Name'
  ```

### **🐳 Docker Compose**

```bash
docker-compose up —-build
```

<br>