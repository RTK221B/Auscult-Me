# Welcome to [Auscult-Me](https://github.com/ishwariyjoshi/Auscult-Me)!

AI based telemedicine system to analyse cardiovascular/lung sounds using a low-cost and highly efficient stethoscope mod to diagnose diseases through an application at home.
```
![pic8opj54t5x](https://user-images.githubusercontent.com/19995215/94829595-4eab8a80-0428-11eb-8a8e-73c4321b059e.png)

```

# The problem Can **Ascult-Me** solves

1) In case of respiratory or cardiovascular diseases, physical examination is necessary but isn’t possible everywhere due to lockdown measures.

2) Even where possible, physical examination by doctor puts doctor as well as patient at risk.

3) In developing nations such as **India**, most of the rural population does not have access to a **hospital**.

4) Telemedicine is an option but only history taking and visual examination is possible through telemedicine, auscultation is not possible and so there is incomplete assesment.

5) There are digital stethoscopes available in the market but they cost from **₹8,500- ₹35,000** and they are not AI Enabled. We have hacked our way into this stethoscope and have made it AI enabled in just under ₹500. So it is affordable to a larger population of India.

5) In case of **Covid-19**, symptoms show up very late after infection has spread in lungs.

6) Being just a one-time investment, and that too of erely a few hundred rupees, can provide them with diagnosis whenever they feel feverish or feel the slightest of symptoms, thereby eliminating/accelerating their doubt over whether they are infected by the disease or not. One more major advantage is that, these lung sounds can also diagnose efficiently as to whether the person is infected by the recent **Covid-19(CoV-SARS-2)** virus.

7) Also, the patient can send the recorded lung/cardiovascular sounds to the doctor via email/WhatsApp and the doctors can **remotely** analyse these sounds using the stethoscope data and prescribe appropriate medication and can offer consultation, thereby maintaining the social distancing norms.

## Challenges we ran into

1) One problem we encountered at the initial stage was the accuracy of the AI model. Howsoever, we solved this by using a **bandpass filter**. Hence, the overall accuracy of the result increased a lot and was around **80-90%.**

2) We ran into an issue over how to train this AI model and create an efficient solution ithin the **Hackathon** duration, so we used Google Teachable Maachine for training our dataset, and linked it with the website we created.

3) The cost of a **digital stethoscope** was extremely high. So, we consulted a doctor and he advised us to use a lower cost version of a normal readily available stethoscope, which gave the same result as the higher coated versions, because of the attachment of the filter.

4) One more challenge we ran into was the **noise**. We eliminated this with the help of the bandpass filter we developed using the **basic electronic components**.

##  Technologies we used

>HTML |
>CSS |
>Java Script |
>Google Cloud Platform (GCP)
