# Machine-Learning-Project
First of all, let's have a quick review of future project.


We have three datasets: 
[RAF-DB](http://www.whdeng.cn/raf/model1.html#dataset)
[FairFace](https://github.com/joojs/fairface)
[UTK](https://susanqq.github.io/UTKFace/)
For this project, I used RAF-DB and UTK.



Work-plan:
Tasks:
  0. Prepare the facial datasets 
      -Examine the images and metadata (labels and annotations).
      -Find a suitable solution to extract the region of interest (RoI) if required.
      -Save the processed dataset.
      -Determine demographic (age, gender, ethnicity) imbalances in the train data. 
  1. Find models to perform your task that can be trained from scratch with the datasets available for your disposal.
  2. Train your models on the preprocessed dataset.
  3. Evaluate the performance. 
      -How far is it from the reported results by the authors? Why?
      -Using the metadata of the evaluation sets, how does the model perform in different demographic groups?
  4. Perform data augmentation to improve training performance.
      -Identify the gaps in your train data in terms of age, gender, ethnicity (and emotion).
      -Fill in the gaps by generating images using Midjourney.
      -Prepare the generated images for training.
      -Train on the updated dataset
