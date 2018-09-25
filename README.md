# SpringBoot + PostgreSQL + Adminer + Docker
A starter REST setup using Spring Boot

<img src="preview.jpg">

## How to Run:
1. Execute `Application.java` inside `src/main/java/hello`
2. Make a `GET` request to `localhost:8080/greeting?name=John`

## Docker
1. Run:
```sh
cd docker && docker-compose up
```
2. You will find the **adminer** dashboard available on `localhost:8091`:
<img src="preview_adminer.jpg" width="600">

3. Open this URL in your browser to open **postico**: `postgresql://localhost:5432/my-demo-db`
<img src="preview_postico.jpg" width="600">
