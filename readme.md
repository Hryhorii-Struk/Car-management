# Smart Vehicle management.

- User management and authentication:
```
├───auth
│   ├───api
│   │   ├───controllers
│   │   ├───models
│   │   ├───routes
│   │   └───services
│   ├───base
│   ├───core
│   ├───db
│   ├───utils
│   └───views
│       └───templates
```

- Real-time license plate detection/recognition and face-recognition:
```
├───check-vehicle-real-time
│   ├───services
│   └───utils
```
- Face recognition using FaceNet, MTCNN and HNSWlib 
```
├───face-recognition
│   ├───api
│   │   ├───ai_model
│   │   ├───controllers
│   │   ├───models
│   │   ├───routes
│   │   ├───services
│   │   └───tasks
│   ├───base
│   ├───core
│   ├───data_file
│   ├───db
│   ├───utils
│   └───views
│       └───templates
```
- Vehicle manager
```
├───license-plate-app
│   ├───api
│   │   ├───controllers
│   │   ├───models
│   │   ├───routes
│   │   ├───schemas
│   │   ├───services
│   │   └───tasks
│   ├───base
│   ├───core
│   ├───db
│   └───utils
```
- License plate detection and recognition using YOLO:
```
└───yolo-license-plate
    ├───base
    ├───ONNXModel
    │   ├───baseONNX
    │   ├───func
    │   └───utils
    ├───onnx_folder
    │   ├───DetectV5
    │   ├───DetectV7
    │   ├───RecognizeV5
    │   └───RecognizeV7
    ├───pt_folder
    │   ├───yolov5s
    │   └───yolov7_tiny
    └───yolo_function
        ├───baseProcessing
        ├───baseYOLO
        ├───yoloV5
        └───yoloV7
```

### Requirement:
Python version >= 3.9
Node module >= v18.16.0



### Technologies:
 - Microservice: NGINX, FastAPI, Mongodb, YOLO, Docker, MTCNN, FaceNet, HNSWlib.
 - Front-end: React.js (Using TypeScript)
 - Realtime Stream: WebSocket, Multi-thread.
