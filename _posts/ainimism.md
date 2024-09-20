---
date: '2024-05-16T19:37:18.000Z'
title: A(I)-nimism
tagline: Made in collaboration with Diana Mykhaylychenko and Dunya Baradari
preview: >-
  A(I)nimism hopes to re-connect us to the world around us. We created an object
  - a portal - that opens a connection to the inanimate world.
image: /images/AI_obj.JPG
---

# Concept

Modern technology has brought many advancements to society, however, it has isolated us in many ways from nature. Our object hopes to re-connect us to the world around us. AI has the capacity to give objects life again - and reconnect us to the world we had forgotten. We have created an object - a portal - that opens a connection to the inanimate world. A user makes a request to speak to an object. If the request is accepted, the portal infers the character of the object and allows the user to speak to it.
![500, 150 object](/images/AInimism-3.png)
We see the use of A(I)-nimism as a ritual between the user and the object, divided into 3 parts: request, conversation, and transformation.
![600, 470 object](/images/User_Ritual.JPG)

# Fabrication

The interaction begins with the user saying “awaken” and using ML keyword detection, A(I)-nimism will pick it up and take a photo of the object the user has placed in front of the camera. The photo is then sent to the GPT-4 Vision model. Now A(I)-nimism is waiting for the user to describe the importance of the object to them (or just give more description) and the voice is transcribed as they are talking. This step is ended through the use of an end phrase and once the ML keyword detection picks up the ending phrase, the transcription is then added to the character generation. The character of the object is created using the GPT’s description based on the photo and the user’s description. If the photo and/or description are not adequate, the connection is rejected and the user must begin the whole process again (this is signified through red glowing). If the connection is accepted, the object begins a conversation through A(I)-nimism. The conversation is ended using the word “goodbye” and A(I)-nismism goes back to its idle state, waiting for the next user to say “awaken”.
![600, 600 object](/images/State_Diagram.png)
A(I)-nimism went through many iterations, but ultimately we decided on a portal in which the user could meaningfully interact with the object. The materials include 2 cherry wood shells made using a CNC milling machine on the outside, 2 nylon powder printed shells on the inside, and connections made with resin printing.
![350, 500 object](/images/CNC_mill.jfif)
![300, 300 object](/images/AI_SideRender.png)
