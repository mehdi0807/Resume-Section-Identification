# Resume-Section-Identification
The presented Github repository offers a comprehensive solution to the challenge posed by ZSoft (an IT consulting firm working on an automatic hiring system named “Hiring Master”) in the Haick 2023 Datathon, which was hosted by `School of AI Algiers`.<br>
The primary objective of the task was to build a model that can efficiently and accurately classify text snippets into one of the following resume sections: Education, Experience, or Skills.<br><br><br>
Knowing that the resumes are in <b>French</b> my approach was to fine-tune the `Camembert` model. This approach for resume section classification involved several key steps. First, I carefully preprocessed the resume dataset, performing text tokenization and handling any data anomalies to ensure the model's input was clean and consistent. Then, I employed transfer learning techniques, leveraging the pre-trained Camembert model from Hugging Face as a starting point. <br><br>
In fact, I participated in the challenge with my team 'DATA SQUAD' and we secured first place with an accuracy of `82.91%` on the public leaderboard and an accuracy of `82.65%` on the private leaderboard.<br>
You can check the competition leaderboard here: https://www.kaggle.com/competitions/zsoft-challenge/leaderboard <br><br>
After the datathon ended, I endeavored to improve upon these results and organized the updated solution in the Jupyter notebook presented in this repository. The updated results show an accuracy of `83.14%` on the public leaderboard and an accuracy of `83.36%` on the private one.<br>
![Capture d'écran 2023-09-28 014841](https://github.com/mehdi0807/Resume-Section-Identification/assets/92737907/ca3bc7bd-30f1-47a8-85eb-fe9bc2de251b)

