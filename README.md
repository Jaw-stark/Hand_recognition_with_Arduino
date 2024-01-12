# Hand_recognition_with_Arduino
Hand recogntion with arduino project uses various tools -> Mediapipe from google
                                                        -> OpenCv
                                                        -> Pyfirmata
                                                        -> Arduino Board
                                                        -> 5 Leds
                                                        -> Breadboard
                                                        -> 10ohms resistors
The code provided used mediapipe, pyfirmata, and OpenCv. The code uses the hand library from mediapipe which analyses the hand based on fingertips keys [4, 8, 12, 16, 20] which are a representation of the index finger to the thumb fingertips. OpenCv allows in image analysis from the camera input which in this case a webcam was used. The pyfimata helps in connection from python to Arduino the keys [8, 9, 10, 11, 12] were used as outputs for the leds. The code lights up an led once a fingertip is noted.  
