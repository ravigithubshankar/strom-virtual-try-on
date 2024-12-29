# storm-virtual-try-on

This repository contains the code for a virtual try-on application built using Flask, Twilio's WhatsApp API, and Gradio's app with IDM-VTON try-on model. 

Users can send images via WhatsApp to Twilio to try on garments virtually, and the results are sent back to them.

# Features

  - Receive images of a person and a garment via WhatsApp.
  - Use Gradio’s API to generate virtual try-on results.
  - Return the resulting image to the user via WhatsApp.
  - Uses Twilio Sandbox for WhatsApp for easy prototyping and testing.


# Technologies Used

  -  Flask: Backend server to handle requests and interact with Twilio and Gradio.
  -  Twilio API: To send and receive WhatsApp messages and media.
  -  Gradio API: For interacting with the virtual try-on Gradio app, which uses IDM-VTON (Improving Diffusion Models for Authentic Virtual Try-on) model under the hood to generate accurate garment try-on results.
  -  Ngrok: For exposing the local server to the internet for WhatsApp interaction.



