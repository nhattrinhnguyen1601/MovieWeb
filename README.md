# MovieWeb

A web-based movie streaming platform supporting HLS + Video.js, multi-language, light/dark themes, and AI-powered recommendations.

## Technologies
- **Backend**: Spring Boot, AWS Services
- **Frontend**: Video.js, HLS
- **Database**: MySQL
- **Cloud Services**: AWS S3

## Setup Instructions

### 1. Database Setup
Ensure MySQL is installed and running. Then, execute the provided SQL script:

```sh
mysql -u root -p < path/to/setup_script.sql
```

### 2. Build & Run the Project

#### Using Maven:
```sh
mvn clean install
```
If dependencies are missing, reload Maven:
```sh
mvn dependency:resolve
```

#### Running the application:
```sh
mvn spring-boot:run
```

### 3. AWS S3 Key Setup
This project requires AWS credentials to access S3. Contact the project maintainer to obtain the necessary keys.

After obtaining the keys, set them up in your `.env` file:
```
AWS_ACCESS_KEY=your-access-key
AWS_SECRET_KEY=your-secret-key
```


## Security Notice
To ensure security and prevent accidental exposure of sensitive credentials:
- The `application.properties` file has been removed from the repository.
- Firebase credentials (`firebase-service-account.json`) have been excluded from version control.
- Make sure to configure these files locally before running the project.

## Contact
For credentials and support, reach out via GitHub: [nhattrinhnguyen1601](https://github.com/nhattrinhnguyen1601)


## Demo
![Ảnh Demo 1](https://github.com/nhattrinhnguyen1601/MyImg/blob/34d62ad2d2c2a3fd9123172628d6f0374fb4c00c/imagess/%E1%BA%A2nh1.png)
![Ảnh Demo 2](https://github.com/nhattrinhnguyen1601/MyImg/blob/34d62ad2d2c2a3fd9123172628d6f0374fb4c00c/imagess/%E1%BA%A2nh2.png)
![Ảnh Demo 3](https://github.com/nhattrinhnguyen1601/MyImg/blob/34d62ad2d2c2a3fd9123172628d6f0374fb4c00c/imagess/%E1%BA%A2nh3.png)
![Ảnh Demo 4](https://github.com/nhattrinhnguyen1601/MyImg/blob/34d62ad2d2c2a3fd9123172628d6f0374fb4c00c/imagess/%E1%BA%A2nh4.png)
![Ảnh Demo 5](https://github.com/nhattrinhnguyen1601/MyImg/blob/34d62ad2d2c2a3fd9123172628d6f0374fb4c00c/imagess/%E1%BA%A2nh5.png)
![Ảnh Demo 6](https://github.com/nhattrinhnguyen1601/MyImg/blob/34d62ad2d2c2a3fd9123172628d6f0374fb4c00c/imagess/%E1%BA%A2nh6.png)
