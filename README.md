**##LeukoVision**

## Inspiration
We were inspired to create an Acute Lymphoblastic Leukemia (ALL) classifier using deep learning with ensemble learning because of the urgent need for early and precise cancer detection. Leukemia, particularly ALL, is a serious threat to children and teenagers as it involves the rapid growth of immature white blood cells, leading to severe health issues and higher mortality. Traditional methods of diagnosing ALL are slow, complex, and often prone to human error, making them expensive and less reliable. The success of deep learning in medical research presented a unique chance to improve the diagnostic process.

## What it does
The classifier takes images of White Blood Cells (WBCs) from the user and determines whether they are Acute Lymphoblastic Leukemia cells or healthy cells.

## How we built it
We used a multi-faceted approach with advanced machine learning techniques and user-friendly deployment platforms. First, we employed transfer learning to train various Convolutional Neural Network (CNN) models, including Xception, InceptionResNetV2, and InceptionV3, on a comprehensive dataset. This allowed us to use pre-trained models to classify ALL efficiently with high accuracy. To enhance our results, we implemented ensemble learning, combining the strengths of individual models for more reliable predictions. For deployment, we used Streamlit, a web application framework, to create an interactive user interface, making our model easy for medical professionals to use. Due to budget constraints, we hosted our project on Kaggle and used ngrok to facilitate seamless deployment. This approach ensured our solution was highly accurate, practical, and user-friendly, aiding early and reliable detection of ALL.

## Challenges we ran into
Developing the "LeukoVision" app presented several challenges. Obtaining a high-quality dataset and integrating different models required careful calibration. Standardizing medical images and ensuring efficient performance on limited computational resources added complexity. We faced constraints with using paid servers, so we hosted the app on Kaggle with ngrok and Streamlit, which limited our deployment options. These issues taught us valuable lessons in data handling, model integration, performance optimization, and navigating constraints in healthcare AI deployment.

## Accomplishments that we're proud of
All three trained models achieved between 92-94% accuracy, but after ensembling, our accuracy increased to 96-97%, which is a significant improvement.

## What's next for LeukoVision
The future scope of the LeukoVision app is extensive. Enhancements can include improving model accuracy with larger datasets and advanced architectures, integrating explainable AI for better transparency, and developing user-friendly interfaces and mobile applications for broader accessibility. Integration with electronic health records (EHR) and telemedicine platforms can streamline diagnostics. Collaborations with research institutions and global health organizations can validate and extend the model's capabilities, potentially expanding to detect other diseases.


## Demo Video Link --
https://youtu.be/7Y-m7DSSyOE?si=7sItR_DOMlxELY3q

## Dataset Link -- 
https://www.kaggle.com/datasets/andrewmvd/leukemia-classification/data

## Trained Models --



