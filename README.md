# PDF-Summarizer

steps to download this project

1)create a folder for your project

2)in the project folder create a folder named uploaded_pdfs : here the pdf that you upload gets saved

3) in the project folder create a folder named LaMini-Flan-T5-248M in this folder and download the model files from
   this link

   https://huggingface.co/MBZUAI/LaMini-Flan-T5-248M/tree/main
   
OR

   if you have git in the system you can clone the repo

   then just open terminal in your project folder  and execute this command in terminal
   
   git clone https://huggingface.co/MBZUAI/LaMini-Flan-T5-248M


   
4) setup virtual enviorment in your system

   and in your virtual enviorment  install the requirments mentioned in requirements.txt file

   just execute this command for that

   pip install -r requirements.txt   (Note:to be executed inside the virtual enviorment)

5) I have used python  3.12.4 for this project

6)Finally to run the project:

  open terminal and get inside the virtual enviorment and execute the following command

  streamlit run streamlit_app.py


make sure you have downloaded the python file and the jpg  inside your project folder before doing this
  
  
