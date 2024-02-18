# Connecting to EC2 Instance and Setting up Apache Web Server

1. Connect to EC2 instance:
    ```bash
    sudo su -
    ```

2. Update system packages:
    ```bash
    yum update -y
    ```

3. Install Apache HTTP server:
    ```bash
    yum install -y httpd
    ```

4. Check status of Apache:
    ```bash
    systemctl status httpd
    ```

5. Create a temporary directory and navigate into it:
    ```bash
    mkdir temp
    cd temp
    ```

6. Download the zip file containing website files:
    ```bash
    wget https://www.free-css.com/assets/files...
    ```

7. Unzip the downloaded file:
    ```bash
    unzip complex.zip
    ```

8. Navigate into the unzipped directory:
    ```bash
    cd complex
    ```

9. List contents of the directory:
    ```bash
    ls -lrt
    ```

10. Move all files to Apache's document root directory:
    ```bash
    mv * /var/www/html
    ```

11. Enable Apache to start on system boot:
    ```bash
    systemctl enable httpd
    ```

12. Start Apache service:
    ```bash
    systemctl start httpd
    ```
