# MRTK-Bot-Qna-Speech

This is a simple MRTK application (platform UWP) that works with a Web App Bot and QnA Maker in order to get the information to answer the user's questions. This also uses Azure Speech services to answer.

## Installation

In order to run the application you need to have the following platforms installed. 

* Unity 2019.4.23f1 
* MRTK 2.6.1 (Foundation and Standard assets) - Use Mixed reality Feature Tool to install it. [Link](https://docs.microsoft.com/en-us/windows/mixed-reality/develop/unity/welcome-to-mr-feature-tool?WT.mc_id=MR-MVP-5003639)
* Speech SDK for Unity 1.16.0 - You can download the package located in the "Importing the tutorial assets" paragraph in here [Link](https://docs.microsoft.com/en-us/windows/mixed-reality/develop/unity/tutorials/mrlearning-speechsdk-ch1?WT.mc_id=MR-MVP-5003639)

You also need to have:
* An Azure account or trial account check how to get a trial following this tutorial. [Link](https://docs.microsoft.com/en-us/learn/modules/create-an-azure-account/?WT.mc_id=AZ-MVP-5003639)
* Speech Service [Link](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/overview#try-the-speech-service-for-free)
* Qna Maker account [Link](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/how-to/set-up-qnamaker-service-azure?tabs=v1)
* Create your QnA Maker KB [Link](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/how-to/manage-knowledge-bases)

---

## What you will find in this application

1. For you to test the app, open up the Bot scene located under Assets/Scenes.

2. You need to have the following credentials 

* Speech service Key and Speech service Region
![Image](https://github.com/ivatilca/MRTK-Bot-Qna-Speech/blob/main/readme/SpeechKeys.png)
* Web App Bot Microsoft App Id 
![Image](https://github.com/ivatilca/MRTK-Bot-Qna-Speech/blob/main/readme/BotID.PNG)
