Project: Classifying spam and non-spam messages

Project Description:
This project is a machine learning model that classifies text messages as “spam” or “non-spam”. A dataset containing labeled messages is used for training, and the model is based on Natural Language Processing (NLP) techniques and the Random Forest Classifier algorithm.

Technologies and libraries used:
Pandas - working with tabular data
NumPy - processing of data arrays
NLTK (Natural Language Toolkit) - text cleaning and preprocessing
Scikit-learn - machine learning (data separation, model training)
CountVectorizer - converting text to numeric format (Bag-of-Words)
Random Forest Classifier - classification algorithm
Stages of model operation:
1) Data loading and preprocessing
2) Text cleaning: removal of unnecessary characters, lower case.
Removal of stop words and stemming (bringing words to root form)
Converting text to numeric form with CountVectorizer
3) Data Splitting:
Data is divided into training (80%) and test (20%) samples
4) Model Training
Random Forest Classifier, an ensemble algorithm that builds multiple decision trees and averages their predictions, is used
5) Model evaluation
Testing the accuracy of the predictions on a test sample
6) Classification of user message

User enters text
The model predicts whether the message is spam or not
Results and accuracy:
The model is trained on a dataset and shows high classification accuracy (97%). It can effectively filter spam messages, which makes it useful for automatic content moderation, email or messenger filtering.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Проект: Классификация сообщений на спам и не-спам

Описание проекта:
Этот проект представляет собой модель машинного обучения, которая классифицирует текстовые сообщения как "спам" или "не спам". Для обучения используется датасет, содержащий помеченные сообщения, а модель основана на методах обработки естественного языка (NLP) и алгоритме Random Forest Classifier.

Используемые технологии и библиотеки:
Pandas – работа с табличными данными
NumPy – обработка массивов данных
NLTK (Natural Language Toolkit) – очистка и предобработка текстов
Scikit-learn – машинное обучение (разделение данных, обучение модели)
CountVectorizer – преобразование текста в числовой формат (Bag-of-Words)
Random Forest Classifier – алгоритм классификации
Этапы работы модели:
1) Загрузка и предобработка данных
2) Очистка текста: удаление лишних символов, приведение к нижнему регистру
Удаление стоп-слов и стемминг (приведение слов к корневой форме)
Преобразование текста в числовой вид с помощью CountVectorizer
3) Разделение данных:
Данные делятся на тренировочную (80%) и тестовую (20%) выборки
4) Обучение модели:
Используется Random Forest Classifier – ансамблевый алгоритм, который строит несколько деревьев решений и усредняет их предсказания
5) Оценка модели:
Проверка точности предсказаний на тестовой выборке
6) Классификация пользовательского сообщения

Пользователь вводит текст
Модель предсказывает, является ли сообщение спамом или нет
Результаты и точность:
Модель обучена на датасете и показывает высокую точность классификации (97%). Она может эффективно фильтровать спамовые сообщения, что делает её полезной для автоматической модерации контента, фильтрации почты или мессенджеров.
