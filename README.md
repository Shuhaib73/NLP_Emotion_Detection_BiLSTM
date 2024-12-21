# Emotion Detection Web Application: Trained Bi-LSTM & GloVe for Emotional Insights 🎭✨

Welcome to the Emotion Detection Web App! Harness the power of cutting-edge AI to detect and understand emotions from text. Designed for researchers, marketers, and data enthusiasts, this app leverages fine-tuned Bi-LSTM (Bidirectional Long Short-Term Memory) networks with GloVe word embeddings to provide accurate and nuanced emotion classification. Fine-tuned specifically on a labeled emotion dataset, this tool allows you to classify emotions in text with high precision. Whether analyzing customer feedback, social media posts, or user sentiments, this app delivers actionable emotional insights. 🌟


### *** Note: To access the Web Application Kindly visit my portfolio website or you can contact me through LinkedIn/Mail.***

---

## 📖 **Features**

✅ **Advanced Emotion Detection**: Classify text into diverse emotions such as Happiness, Anger, Sadness, Fear, and Surprise, providing a deeper understanding of human sentiment.  
✅ **Trined Bi-LSTM Model**: Built using a Bidirectional LSTM, the model is fine-tuned on an emotion-labeled dataset to recognize emotional cues in text. This allows it to better understand both past and future context in sequences.

✅ **GloVe Word Embeddings**: Leverages pre-trained GloVe embeddings, which are fine-tuned alongside the Bi-LSTM model during training. This improves the model's ability to understand the relationships between words and their contextual meaning.

✅ **Customizable & Scalable**: The modular architecture supports fine-tuning for additional emotion classes or integration with larger datasets.

✅ **User-Friendly Interface**: Built with Flask, HTML and CSS, the interface ensures a smooth and intuitive experience for all users.  

✅ **Deployable Anywhere**: Containerized with Docker for consistent performance across environments.

---

## 🛠️ **Technologies Used**

- **Python** 🐍: The core programming language that powers the app.  
- **Flask**: A Backend web framework for building web applications.  
- **NLTK (Natural Language Toolkit)**: Utilized for preprocessing tasks like text tokenization and stopword removal.
- **Bi-LSTM (Bidirectional Long Short-Term Memory)**: A deep learning model used for understanding sequential data in text. Fine-tuned for emotion detection tasks by learning context from both past and future sequences.
- **GloVe (Global Vectors for Word Representation)**: Pre-trained word embeddings that capture semantic relationships between words, used as input for the Bi-LSTM model.
- **TensorFlow**: Leveraged in this project as the primary framework for building and deploying the deep learning model for sentiment classification.
- **Keras**: A high-level neural networks API, Used in combination with TensorFlow to simplify the construction and training of deep learning models, enabling efficient sentiment prediction.
- **Torch (PyTorch)**: A powerful framework for building deep learning models. Used to train, fine-tune, and deploy the transformer models efficiently.
- **Docker**: Utilized in this project to create a containerized environment for the app, ensuring consistent development and deployment across different environments.
- **Docker Container Images**: Employed to package all necessary code, libraries, and dependencies, allowing for the easy deployment and scaling of the sentiment analysis app.
- **CI/CD (Continuous Integration/Continuous Deployment)**: Integrated into the development workflow to automatically test and deploy new changes to the app, ensuring higher quality and faster release cycles for updates.
- **GitHub Actions**: Implemented for automating the CI/CD pipeline, allowing for seamless building, testing, and deployment of the sentiment analysis model directly from GitHub.
- **Pandas**: A robust library for dataset management and processing.  
- **WordCloud**: A powerful library for generating word clouds to visualize text data.  
- **Matplotlib/Seaborn**: Used for creating impactful visualizations that simplify data insights.  

These technologies collectively make the Sentiment Analyzer app a versatile, efficient, and easy-to-use tool for professionals and researchers alike! 🚀


### Input Options  
1. **Single Text Analysis**:  
      - A user can enter any text or sentence in the provided text box.
      - Upon clicking the "Analyze Emotion" button, the app processes the input and classifies it into one of the predefined emotional categories such as Joy, Sadness, Anger, Fear, or Surprise.

---

### Output Features  

1. **Sentiment Classification**:  
   - Each input text or dataset entry is labeled with a specific emotion such as Joy, Sadness, Anger, Fear, or Surprise. This helps users quickly grasp the dominant emotional tone of each text.

These outputs enable quick, clear, and actionable insights for text-level sentiment analysis. 🎯

---
## 📈 Visualizations

<img src="https://github.com/Shuhaib73/NLP_Emotion_Detection_BiLSTM/blob/main/emo1_word_dis.png" alt="Generated Image 1" style="max-width: 35%; height: 250px; border: 2px solid #ccc; border-radius: 8px; display: inline-block; margin-right: 10px;">

<img src="https://github.com/Shuhaib73/NLP_Emotion_Detection_BiLSTM/blob/main/emo1_word_dis2.png" alt="Generated Image 1" style="max-width: 35%; height: 250px; border: 2px solid #ccc; border-radius: 8px; display: inline-block; margin-right: 10px;">


## 📝 **Model Accuracy & validation Loss Per Epoch**

<img src="https://github.com/Shuhaib73/NLP_Emotion_Detection_BiLSTM/blob/main/emo_res.png" alt="Generated Image 1" style="max-width: 55%; height: 330px; border: 2px solid #ccc; border-radius: 8px; display: inline-block; margin-right: 10px;">

## 📝 **Classification Report**

<img src="https://github.com/Shuhaib73/NLP_Emotion_Detection_BiLSTM/blob/main/emo1_repo.png" alt="Generated Image 1" style="width: 700px; height: 320px; border: 2px solid #ccc; border-radius: 8px; display: inline-block; margin-right: 10px;">


---

## 🌟 **Usage Examples**

1. **Analyze Customer Feedback**: Identify emotions like Joy, Anger, or Frustration in product reviews or feedback surveys to enhance customer experience and services.
2. **Social Media Monitoring**: Track emotions in tweets, comments, or posts to understand public sentiment and emotional trends regarding a brand, event, or trending topic.
3. **Research**: Uncover emotional patterns in textual datasets for academic or market research, enabling deeper insights into human behavior.
4. **Event Monitoring**: Analyze live reactions during events such as conferences, product launches, or disasters to understand public emotional responses in real-time.
5. **Mental Health Analysis**: Analyze text data from online forums or personal journals to identify emotions indicative of mental well-being or distress.  
6. **Employee Feedback**: Detect emotions in employee surveys to assess workplace morale, leadership effectiveness, and cultural health. 
7. **Customer Service Analysis**: Identify patterns and trends in customer service complaints or satisfaction levels.  
8. **Market Research**: Study public perceptions of competitors, industries, or trends for better decision-making.  
9. **Political Sentiment Analysis**: Gauge public emotional responses to political speeches, debates, or policy announcements.
10. **E-commerce Insights**: Analyze emotional tones in product reviews to better understand customer feelings about products and services.

These examples highlight the versatility of this tool across industries and fields! 🚀

---

## 📈 **Future Enhancements**

✨ **Multilingual Support**: Expand the tool to analyze sentiments in multiple languages, enabling global usability.  
✨ **Real-Time Social Media Integration**: Connect directly to live social media APIs (e.g., Twitter API) to analyze trends in real-time.  
✨ **Entity Recognition and Sentiment Correlation**: Combine Named Entity Recognition (NER) to analyze sentiment towards specific entities (e.g., brands, people, or locations).  
✨ **Text Summarization Integration**: Include a feature to summarize large datasets before sentiment analysis for faster insights.  
✨ **Support for Speech-to-Text Integration**: Enable voice inputs by integrating speech-to-text technology, allowing spoken text sentiment analysis.  

These enhancements aim to make the app more versatile, efficient, and impactful for users across various industries and applications. 🚀✨ 

---


## 📧 **Contact**

For questions, feedback, or contributions, please contact:  
**Shuhaib**  
**Email**: mohamed.shuhaib73@gmail.com
**LinkedIn**: https://www.linkedin.com/in/mohamedshuhaib/

---
