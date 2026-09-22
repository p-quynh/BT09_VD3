## Cấu hình file env


    spring.datasource.url=${DB_URL}
    spring.datasource.username=${DB_USERNAME}
    spring.datasource.password=${DB_PASSWORD}

    SERVER_PORT=8080

    spring.mail.host=${MAIL_HOST}
    spring.mail.port=${MAIL_PORT}
    spring.mail.username=${MAIL_USERNAME}
    spring.mail.password=${MAIL_PASSWORD}

    cloudinary.cloud-name=${CLOUDINARY_CLOUD_NAME}
    cloudinary.api-key=${CLOUDINARY_API_KEY}
    cloudinary.api-secret=${CLOUDINARY_API_SECRET}

## CHẠY CHƯƠNG TRÌNH

    mvn clean package

    mvn spring-boot:run

## TRUY CẬP

    http://localhost:8080