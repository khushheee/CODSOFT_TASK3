# CODSOFT Task 3: Nginx Web Server Deployment using Docker

##  Objective
Deploy an Nginx web server using Docker, host a static website, configure virtual hosts, and implement custom error pages.

##  Technologies Used
- **Docker** - Containerization
- **Nginx** - Web Server
- **HTML/CSS** - Static Website
- **Git & GitHub** - Version Control


##  Steps to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/khushheee/CODSOFT_TASK3.git
cd CODSOFT_TASK3
```

### 2. Build Docker Image

```bash docker build -t codsoft-nginx-task3 .```

### 3. Run Docker Container

```bash docker run -d -p 8080:80 --name nginx-task3 codsoft-nginx-task3 ```

### 4. Access the Website

```bash http://localhost:8080 ```

### 5. check container logs

```bash docker logs nginx-task3 ```

### 6. Stop and Remove Container

```bash docker stop nginx-task3 ```
```bash docker rm nginx-task3 ```

