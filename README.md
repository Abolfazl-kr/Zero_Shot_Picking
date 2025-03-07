# Zero Shot Picking  

🚀 **Zero Shot Picking** is an AI-powered object retrieval system that enables a robotic arm to pick up objects from a container using only their names as input. This project demonstrates the use of advanced object detection and segmentation techniques to perform zero-shot picking in real-time.  

---


[Untitled_ Jul 10, 2023 12_52 PM.webm](https://github.com/user-attachments/assets/2437f024-9bb1-45e4-a712-f08c8fdce7cb)


https://github.com/user-attachments/assets/6c6fd186-bd49-4990-b7fa-cfa4e6a89c59



🔹 **Video 1: Object Recognition**  
- A user inputs the name of an object.  
- The system captures an image of the container.  
- The model detects and highlights the requested object in the captured image.  

🔹 **Video 2: Robotic Arm Integration**  
- The system is connected to a robotic arm.  
- When a user inputs an object’s name, the robotic arm retrieves the object from the container based on the detected coordinates.  

---

## 🛠 **Technical Overview**  

🔹 **Object Detection & Segmentation**: Uses **GroundingDino** for object detection and **Segment Anything Model (SAM)** for precise segmentation.  
🔹 **Optimized for Speed**: Utilizes **MobileSAM** to accelerate the segmentation process, reducing execution time to **~0.5 seconds** per request.  
🔹 **Robotic Arm Integration**: Extracts object coordinates and sends them to a robotic arm for automated picking.  
🔹 **Zero-Shot Picking**: The system does not require prior training on specific objects; it dynamically detects and retrieves any object based on its name.  

---

## ⚠️ **Disclaimer**  
This repository does not include the source code due to confidentiality reasons. However, the provided videos showcase the capabilities and real-world application of the system.  

For inquiries or collaboration opportunities, feel free to reach out! 🚀  
