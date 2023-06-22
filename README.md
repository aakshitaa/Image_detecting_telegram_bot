#About the product 

The application allows users to upload images and respond with objects that the service detected in the image.
Users can interact with the application through a simple web UI or an interactive Telegram bot to obtain object detection results.

The service consists of 4 microservices: 

- Telegram Bot container.
- Web UI container.
- Image prediction container based on the Yolo5 pre-train deep learning model.
- MongoDB container to store clients data.

![](../../.img/object_detection_service.png)

