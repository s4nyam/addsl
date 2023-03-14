# addsl
Hand Gesture Detection and Sign Language Recognition on Danish Sign Language


Abstract— Detection of hand gestures and then recognizing them to an elementary alphabet or a number has been a challenging task for all time. It becomes difficult for the specially abled class of people to communicate with other people in many ways. In this paper, we propose a novel Annotated Dataset for Danish Sign Language (ADDSL). The annotations are made using LabelImg open-source tool in YOLO format. Further, a one-stage object detector (YOLOv5) model is trained with the backbone of new CSP-DarkNet53 and YOLOv3 head to recognize alphabets (A-Z) and numbers (0-9) with only seven unique (without augmentation) images per class. Five models are trained in the same environment with 350 epochs which resulted in an average inference time of 9.02ms per image, with an average accuracy of 88.68%. The results show that our model is much faster and more accurate than existing work in the same task. Repository will be made available here after acceptance of th paper.
Keywords—Object Detection, Convolutional Neural Network, YOLOv5, Hand Gesture, Sign Language

Some results;

<img width="458" alt="Screenshot 2023-03-14 at 1 39 32 AM" src="https://user-images.githubusercontent.com/13884479/224862917-81569b44-5206-437f-a2d1-91a8e1e75534.png">


<img width="453" alt="Screenshot 2023-03-14 at 1 39 42 AM" src="https://user-images.githubusercontent.com/13884479/224862939-69f1a114-89a2-403c-aa7d-546dbd60e711.png">


<img width="438" alt="Screenshot 2023-03-14 at 1 39 58 AM" src="https://user-images.githubusercontent.com/13884479/224862970-5825459a-e9fe-4c7a-96c4-1e11c892cbda.png">


<img width="441" alt="Screenshot 2023-03-14 at 1 40 08 AM" src="https://user-images.githubusercontent.com/13884479/224862995-d31221a7-6b5e-4830-a51b-aed541d196c0.png">
