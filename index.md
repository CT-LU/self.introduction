# Welcome to Ludan's pages

## Profile

15+ years of embedded systems experience. Skilled in software development and integration on embedded Linux and Android. In the past 5 years, I've been involved in machine/deep learning accelerated by heterogeneous computing, ideally with GPU (OpenCL, CUDA), FPGA, DSP. Nowadays, my project is to research and develop unsupervised learning for defect inspection.

## Honors
------
* **Award:**
I won the 3rd place in CUDA programming contest in September 2009, NVIDIA Taiwan. <http://www.nvidia.com.tw/object/cuda_contest_main_tw.html>

<img src="https://raw.githubusercontent.com/CT-LU/self.introduction/master/Contest.jpg" width="739" height="554">

* **Publication :**
Multiview encoder parallelized fast search realization on NVIDIA CUDA, Visual Communications and Image Processing (VCIP), 2011 IEEE. <https://ieeexplore.ieee.org/abstract/document/6116010>

## Work Experience
-----
* ### HON HAI/Foxconn Technology Group (09/2019 - Present)
* ### LIPS Technology (02/2016 - 09/2019)
> #### Led a team of 6 to carry out several projects for proof of concept and mass production:<br>
> ![](https://raw.githubusercontent.com/CT-LU/self.introduction/master/3D_Hands_Pose.gif)
![](https://raw.githubusercontent.com/CT-LU/self.introduction/master/3D_Lableing_Tool.gif)<br>
> #### Project : 3D Hand Pose lower latency and higher accuracy compared to Leap Motion.
> To bring your AR/VR experience to the next level, we are developing a CNN that smooths hand and finger tracking looks and feels more organic than ever. We organized every process, including a team for label  engineering, creating 3D label tools and training a regression CNN model with fast and accurate design.
> ![](https://raw.githubusercontent.com/CT-LU/self.introduction/master/Optimization_2.5D_Body_Pose.gif)
> #### 3D Body Pose  Real-time detection using TensorRT and OpenVINO
> We created a system to estimate and track 3D poses of multiple persons by using a CNN for 2D pose estimation and extending the resulting skeletons to 3D by means of the sensor depth in calibrated RGB-Depth camera. To be a real time application,  we designed and compressed the CNN model as well as accelerated it by using NVIDIA TensorRT and Intel OpenVINO.
> #### Project : TOF Camera
> Accomplished a variety of the filters and algorithms for the depth calculation, image calibration , noise reduction and CNN-based inference through CUDA/OpenCL on the several architectures including (1). NVIDIA TK1/TX1(CUDA), (2). Mali, Adruino, Intel(OpenCL with SIMD instructions), (3). Altera Cyclone V FPGA(OpenCL in a pipelined fashion), (4). CEVA DSP(intrinsic functions) .

* ### HON HAI/Foxconn Technology Group (07/2014 - 02/2016)
> #### Led a team of 3 to create proof of concept projects<br>
> ![](https://raw.githubusercontent.com/CT-LU/self.introduction/master/Facial_Recognition.gif)
> #### Project : Facial recognition
> Accuracy rate of 95.75% on the well-known and challenging LFW benchmark. 
> To evaluate facial recognition, We not only successfully trained DeepID2 network via NVIDIA DIGITS but also developed a prototype of facial recognition system composed of face detection(HOG + SVM), alignment, recognition(DeepID2 + cosine similarity).
> ![](https://raw.githubusercontent.com/CT-LU/self.introduction/master/Gesture_Control_TV.gif)
> #### Project : Hand gesture
> Increased 200% efficiency for object detection by using CUDA to accelerate the filters. 
> Created the hand gesture system on NVIDIA TK1. We implemented fast R-CNN involving the region proposal(selective search), CNN(CaffeNet network), and recognition(fine tuning the softmax classifier). Furthermore, we invented an algorithm that can efficiently analysis the hand motions under depth images.

* ### ALPHA Networks Inc (09/2010 - 07/20147)
![](https://raw.githubusercontent.com/CT-LU/self.introduction/master/WD_TV_Play_is_a_great_streamer.gif)    
> #### Project : WD TV
> 1.  **BSP integration :**
> - Decreased 50% workload by negotiating with chip vendors to solve the parts of issues.
> - Supervised an Android BSP team of 2 in integrating BSP applications and cooperating with chip vendors.
> - Ported existing software to Android platform (implemented services with android binder).
> - Implemented a Linux device driver using GPIO to control peripheral devices.
> 2. **Hacking and Mimicking AirPlay protocol :**
> - Successfully imitate AirPlay protocol.
> - Analysed the network packet of AirPlay protocol (using Wireshark).
> - Mimicked AirPlay protocol and implemented displaying photos, slideshows and videos functions on our box.
> 3. **Framework development :**
> - Improved work efficiency over 300% by using Python to develop back-end services.
> - Designed and created a framework using the D-Bus libraries to achieve greater capability in communication between various program languages of Javascript, C/C++ and Python.
> - Led a team of 2 to design and implement applications UI of MLB and the App Store (using HTML5/JavaScript/css).
> - Designed and implemented the App Store both on the back-end service and the server (using python).
> 4. **Implemented Web applications UI :**
> - (a). Accuweather. (b). Shoutcast. (c). Wizard. (d). Yahoo weather. Fetching the data from specific URL and parsing the returned files (XML or Jason format) to display the information on the screen according to its design specification.

* ### YA HORG Electronic Corp (02/2006 - 03/2007)<br>
![](https://raw.githubusercontent.com/CT-LU/self.introduction/master/DVJ_1000_FUNCTION.gif)
> #### Project : DVJ Player<br>
> 1. **Firmware :**
> - Increased 20% efficiency by avoiding unnecessary transactions. 
> - Ported IC firmware of the network chip (CS8900,  RTL8019) to DSP chip.
> - Created IC firmware of the IDE ATA/ATAPI and I2C on DSP chip.
> 2. **Software :**
> - Successfully implemented playing DVD in reverse.
> - The development of tools of the TFTP client and SHELL command.
> - Developed the UDF file system and implemented the sliding window of the file cache for sending file data to the DVD player.
> - Designed and implemented a microkernel for the task-switching process.
> - Ported DVD application includes image blending,  navigation module,  demuxer (parsing the mpeg2 packet to the decoder),  command interpreter,  and  image format translation (RGB to UYVY).

* ### MITAC International Corp (06/2005 - 02/2006)
> #### Project : Mass Rapid Transit - Ticket System (MRT)<br>
> - Designed and implemented interprocess communication using IBM MQ.
> - Multithreaded socket programming for the communication between stations and the server.
> - Database using ORACLE OCCI (C++ embedded SQL).
> - UI design using Borland C++.

## EDUCATION
------
* **National Taipei University of Technology**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Master's Degree in Computer and Information Sciences.
* **National Yunlin University of Science and Technology**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bachelor's Degree in Management Information Systems.
