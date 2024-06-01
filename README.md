Naive Bayes Sınıflandırıcısıyla SMS Filtreleme Yöntemi (TÜRKÇE)
Naive Bayes sınıflandırıcısı, istatistiksel bir makine öğrenmesi yöntemidir ve özellikle metin sınıflandırma görevlerinde sıkça kullanılır. Bu yöntem, Bayes teoremini ve özelliklerin birbirinden bağımsız olduğu varsayımını temel alır. SMS filtreleme, spam (istenmeyen mesajlar) ve ham (istenen mesajlar) olarak sınıflandırma işlemidir. İşte bu sürecin adımları:

Veri Toplama: İlk adım olarak, spam ve ham mesajlardan oluşan bir veri kümesi toplanır.
Ön İşleme: Mesajlar temizlenir; özel karakterler, sayılar ve durak kelimeler (ve, ya, ile gibi) kaldırılır. Ardından, kelimeler köklerine indirgenir.
Özellik Çıkarma: Her mesajdaki kelimeler sayılır ve bir kelime sıklığı matrisi oluşturulur. Bu matris, her mesajın birer özellik vektörüne dönüştürülmesini sağlar.
Model Eğitim: Naive Bayes sınıflandırıcısı, eğitim verisi üzerinde eğitilir. Bu aşamada, her kelimenin spam veya ham olma olasılığı hesaplanır.
Sınıflandırma: Yeni bir SMS geldiğinde, özellik vektörüne dönüştürülür ve Naive Bayes modeli kullanılarak spam veya ham olarak sınıflandırılır.
Değerlendirme: Modelin performansı, doğruluk, hassasiyet, özgüllük gibi metriklerle değerlendirilir.



SMS Filtering Method with Naive Bayes Classification (ENGLİSH)
Naive Bayes classifier is a statistical machine learning method, widely used in text classification tasks. This method is based on Bayes' theorem and the assumption that features are independent of each other. SMS filtering involves classifying messages as spam (unwanted messages) or ham (wanted messages). Here are the steps of this process:

Data Collection: The first step is to collect a dataset of spam and ham messages.
Preprocessing: The messages are cleaned; special characters, numbers, and stop words (like and, or, with) are removed. Then, words are stemmed to their root forms.
Feature Extraction: Words in each message are counted, and a term frequency matrix is created. This matrix allows each message to be transformed into a feature vector.
Model Training: The Naive Bayes classifier is trained on the training data. At this stage, the probability of each word being spam or ham is calculated.
Classification: When a new SMS arrives, it is transformed into a feature vector and classified as spam or ham using the Naive Bayes model.
Evaluation: The performance of the model is evaluated using metrics like accuracy, precision, and recall.
