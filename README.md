# Message App

1. Initialize a new module

    ```go mod init rabbitmq-go ```
    ```  go mod tidy ```

2. Start RabbitMQ from a Docker image.

```     docker-compose up     ```

3.  Open your browser and head over to http://localhost:15672. 
You should see the RabbitMQ UI. Use guest as username and password.

4. Install amqp library by running the following command in your terminal:

```     go get github.com/streadway/amqp     ```

5. Test sendMessage with the following terminal command: 

```    go run sendMessage.go    ```
