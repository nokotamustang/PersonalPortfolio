`Celebrating 14 years of Software Engineering and Computer Vision`

I have worked on various projects, both personal and professional, and have gained a lot of experience in the field.

These projects showcase my skills and expertise in software engineering and computer science.

## 3D graphics rendering engines - 2024 ongoing

I am working on **Python** 3D graphics rendering engines for real-time applications. The engines are built from scratching with the **ModernGL** wrapper of **OpenGL** and **GLSL** shaders.

![Nokota Mustang 3](./img/mgl_grass2.PNG)

The series is open source and I am documenting the process of building the engine up piece by piece in one of my [GitHub repositories](https://github.com/nokotamustang/Python3DEngines).

This series covers the basics of 3D graphics rendering, including the mathematics behind it, the rendering pipeline, and the implementation of various rendering techniques such as lighting, shadows, and post-processing effects.

![Nokota Mustang 3](./img/mgl_ground3.PNG)

I will be extending the engine to include more advanced features such as physics simulation, animation, and particle systems.

I will also explore the **Vulkan** API and compare it to **OpenGL**, specifically in Visual Studio 2022, to see which one is better suited for real-time applications. This is a longer-term project that will be open source and available on one of my [Github repositories](https://github.com/nokotamustang/Vulkan3DEngines).

## Machine Learning for financial data - 2024 ongoing

I have built a Python **Fast API** server running a **MySQL** database of public tradable USA securities, general market data.

The front-end app is built in a **React** / **Node.js** custom built and can display complex charts.

![Nokota Mustang 3](./img/nm_2.PNG)

I track various data sources around the stock tickers, such as the Failures-To-Deliver, and can produce many technical indicators of the trading prices. 
 
![Nokota Mustang 3](./img/nm_4.PNG)

I have been tracking bankruptcy restructuring in North American companies. This includes reading and understanding legal document in the Federal Court dockets, and using this information to find patterns in financial fraud.

![Nokota Mustang 3](./img/nm_5.PNG)

I am designing a Machine Learning model to detect potential fraud in financial data, and to detect forced bankruptcy restructuring in companies.

I also track the weather and the Buffett Indicator to see if there are any correlations with the stock market.

![Nokota Mustang 1](./img/nm_1.PNG)
![Nokota Mustang 2](./img/nm_3.PNG)

## Machine Learning for tracking vehicles - 2023

This application uses AI to produce turning counts, in other words a detailed tally of the categories of vehicles during various blocks of time in the day.

The platform that I worked on uses a range of Amazon Web Services, including **S3**, **Lambda**, **API Gateway**, **DynamoDB**, **Batch** and **ECS**, and **SageMaker**.

The First part I worked on uses a variety of Amazon Web Services (AWS) technologies that span across **GPU compute** enabled **EC2** instances; with **Docker** images running via **ECS**; and wrapped inside **AWS Batch** for automated queuing. Everything is designed for scalability.

![Animation](./img/rk_animation.gif)

The 'digital twin' output of the tool recreates the vehicle movement in a 3D space.

I worked on building the scalable solution for this product, using **AWS Cloud Formation** with **Cloud Development Kit** (CDK) to build a scripted architecture for the pipeline.

## Account and billing system - 2022

This application uses deep learning algorithms to alter audio files. The platform is built using Python, PyTorch, and runs on AWS.

![Morphing](./img/al_morph.gif)

On the main app itself I have worked on adding components to the tools, and controls for third party effects wrappers and other tasks such as import/export of raw data from various file formats, and general maintenance and bug fixing. This application is an **Electron** app with a codebase written mostly in **Typescript**.

![Billing 1](./img/al_1.PNG)

I designed and built a customer management portal and payment system to help the company scale-up their product service (SaaS). The stack was **React** with **Redux**, within a **Typescript** environment running on **Node.js**. The payment system is connected to Chargebee, a third-party system that works with **Stripe**, which is in turn connected to third party payment gateways.

I built endpoints and **AWS Lambda** code hosted with **Amazon Web Services** while working with the back end engineers.

![Billing 3](./img/al_3.PNG)

## 2D graphics game engine - 2020

A 'monster tamer adventure' PC game. The technologies used are **C++19**, **OpenGL**, and **GLSL** pixel shaders.

![Daemon Team Six 3](./img/dts_5.PNG)

The final prototype which included a fully working User Interface, map system for the player to travel around, and a battle system with a variety of monsters to fight against.

![Daemon Team Six 1](./img/dts_3.PNG)

## Augmented reality for beauty - 2018

I built an **Electron** desktop application to integrate simulation toolkit with web technologies for the front-end. This used **TypeScript** web logic with the **C++19** backend of the Augmented reality software.

The Charlotte Tilbury Magic Mirror uses the toolkit to allow customers to try on different makeup looks in real-time. The application uses face tracking and augmented reality to overlay virtual makeup onto the customer's face.

![Magic Mirror](./img/hol_7.jpg)

I led a research project to determine how realistic their foundation makeup simulation algorithm was; and then to design an improved one. For this I predominantly worked in Python for prototyping ideas seen from research papers; and **C++19** for the back-end application in which I created new tools for measuring the accuracy compared to real makeup.

![Foundation 2](./img/hol_3.PNG)

From foundation makeup testing on real skin, to one simulation of foundation from the renderers, and the simulation accuracy metrics:

![Foundation 3](./img/hol_1.png)
![Foundation 4](./img/hol_2.png)

I led a research project to create a concept of AR makeup tutorials. This used face tracking in real-time video combined with animations made in **After Effects**. The technologies are the **C++19** backend for the tracker, **Emscripten** to compile the application into **ASM-JS** for web, and **Typescript** for the front end and tools to render the real-time animations. This tool for example is used by Burberry for their Virtual Studio.

![AR Tutorials 1](./img/hol_5.jpg)

From first prototype of my work with another Senior Engineer, to the production version as used in Burberry's Virtual Studio:

![AR Tutorials 2](./img/hol_animation.gif)
![AR Tutorials 3](./img/hol_animation_2.gif)

I created a comparison tool to show the difference between the real makeup (in controlled lighting) to the simulation makeup. This tool was used to help improve the accuracy of the simulation algorithm by providing a quantitative measure of the difference between the two.

![AR Tutorials 4](./img/hol_8.PNG)
![AR Tutorials 5](./img/hol_animation_3.gif)

## 2D graphics game engine - 2016

This PC game was primarily written in **C++** using the **OpenGL** for graphics rendering.

![DW 1](./img/dw_1.jpg)

This project used procedural generation for random levels, and a variety of monsters and bosses to fight against.

![DW 2](./img/dw_2.jpg)

## Augmented reality for sports broadcast - 2013

I worked on the **Piero** project which is software used to generate real time augmented reality video with **Java** and **C++**, using **OpenGL** for 3D graphics creation.

![Piero 1](./img/piero_1.PNG)

I had built many effects into the software, which can be seen on most Sport broadcasts for Tennis, Football, Rugby, etc.

![Piero 2](./img/piero_2.PNG)

Part of the challenge was working with 3D graphics and video in real-time, which required a deep understanding of computer graphics and video processing; the real-time rendering has to be ready for the broadcast in less than 4 frames to be broadcast ready.

![Piero 3](./img/piero_3.PNG)

We expanded the Piero software to work with **Opta** data, allowing even more use cases with large datasets of sports data. This was a big project that required a lot of work to integrate the data into the software and make it usable for the clients.

![Piero 4](./img/piero_4.PNG)

Another project was integrating the **EA Sports** rendering engine into **Piero**, which allowed for more realistic graphics presentation for the 3D stadium and players models. This was a complex project that required a lot of work to integrate the two systems and make them work together seamlessly.

## PhD thesis in computer vision - 2009

I led a Computer Vision project for the measurement of granular organic matter in an on-line environment. The major hurdle was to measure the percentage of broken rice in a stream of rice grains. The system had to be able to measure the size of the grains, the color of the grains, and the shape of the grains. The system had to be able to do this in real-time, as the grains were moving down a conveyor belt at a high speed.

![PhD Thesis 1](./img/bs_1.PNG)

So first was the task to measure the length of rice in a static image.

![PhD Thesis 2](./img/bs_0.PNG)

Following with the task to measure the length of rice as it freely moves in a stream.

![PhD Thesis 3](./img/bs_2.PNG)

The system was able to measure the percentage of broken rice from 25,000 grains in a moving stream within 5 minutes. Evaluation of a series of 12 measurements of 25,000 rice grains each experiment, repeated with two varieties of rice. Observations were made of a mean error of broken rice estimation without correction factor applied is 0.12%, and with correction factor applied is -0.57%.

## Computer vision for object separation of grains - 2008

I completed a one-year research project on ‘Separation of Touching Objects’ in an image, and then produced a solution to the problem for organic matter such as touching rice grains.

![Object Separation](./img/bs_os2.PNG)

## Computer vision for food optical sorting - 2007

I worked as an image processing engineer to advance the technology of optical sorting machines for food.

![Placement 1](./img/bs_os.PNG)

The Defect Browser was a prototype tool that could simulate the defect detection that the company used in their high performance machines, with a twist. This tool to simulate a variety of parameters and allow the user to manipulate and view the results in real-time.

![Placement 2](./img/bs_defect_browser.png)
The horizontal line would represent the defect threshold and the operator could adjust this to see how the machine would react to different levels of defects using real data from the machines.

The Feed Quality Measurement tool was a prototype tool that could measure the quality of the feed of the machine. Better quality of the feed would be the grains spread out across the chute, worse quality would be the grains clumped together which meant the air-ejectors would fire and hit 'innocent bystander' grains when a defect was detected.

A variety of measurements were taken to determine the quality of the feed, and the tool would output a score based on these measurements as the 'clumpyness' metric. The following images are example outputs that show the coverage measurement of the frames of rice, an example threshold set of frames, the distribution of grains across the width of the chute, and the final score of the feed quality measurement.

![Placement 5](./img/bs_fqm_3.png)
![Placement 6](./img/bs_fqm_4.png)

This tool allowed the company's mechanical engineers to build a variety of prototype chute designs to improve the feed quality of the machines. They selected a 'chamfered' design that contains numerous steps down the chute which allows the grains to spread out more evenly across the chute every time they bounce down a step. This increased the productivity of one machine by about 200% in final testing.
