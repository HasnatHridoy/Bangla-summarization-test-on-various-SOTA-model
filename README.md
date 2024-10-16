## Evaluation of various SOTA model performance on Bangla text summarization.
In this experiment I have fine tuned 5 SOTA model on [XLsum](https://huggingface.co/datasets/csebuetnlp/xlsum) dataset specificlly for Bangla text summarization task.
All the trained model are avilable in [Huggingface](https://huggingface.co/hasnatz). The trained models are:
- [Gemma 2 9b](https://huggingface.co/hasnatz/gemma2b11)
- [Llama 3.1 8b](https://huggingface.co/hasnatz/llama3_1_8b)
- [Gemma 2b](https://huggingface.co/hasnatz/gemma2b10M120)
- [Microsoft FILM](https://huggingface.co/hasnatz/film120)
- [Llama 3 8b](https://huggingface.co/hasnatz/exp2)

After the fine tuning I compaired the Rouge 1 & L result of these 5 model. From this comparison, we can see that the Gemma 2 9B model performs well among the other models. The LLaMA 3.1 and FILM are also close competitors to the Gemma 2. The LLaMA 3 8B model performs worse than the Gemma 2B model.
<br> Results from 100 different [samples](https://kaggle.com/datasets/522b8a01db8c65fdc0e5ad2c381fab2f6e3eac5c299d7ae5b99678f9f1987ae6) on various character token sizes are available [here](https://kaggle.com/datasets/5d06d02e6778b7d73c2dd67b30db407e4247ba80e69f9d96f974ea94b05064eb).
<br>
#### Rouge 1 compairson

![Screenshot 2024-10-04 011121](https://github.com/user-attachments/assets/ffe2c7d8-83a2-4a73-bde0-ae237826780d)
![Screenshot 2024-10-04 011157](https://github.com/user-attachments/assets/489978eb-20da-4006-961d-2ca47a226f21)
![Screenshot 2024-10-04 011259](https://github.com/user-attachments/assets/7248f8c7-2ced-4d67-81cd-b2a536007b30)
![Screenshot 2024-10-04 011326](https://github.com/user-attachments/assets/d92c21c4-ddf7-48f6-a306-09f3d0b510b4)
<br>
#### Rouge L compairson
![Screenshot 2024-10-04 014104](https://github.com/user-attachments/assets/1d0c1ee1-c28a-485f-97b0-a2349b482f83)
![Screenshot 2024-10-04 014140](https://github.com/user-attachments/assets/44ae73c0-1cfa-447e-9715-059fe128ad3e)
![Screenshot 2024-10-04 014154](https://github.com/user-attachments/assets/7225e27d-1a4b-41bf-a459-18917d44afae)
![Screenshot 2024-10-04 080847](https://github.com/user-attachments/assets/6058e011-8ac8-445b-8323-5fbdf01797e2)
<br>
 
