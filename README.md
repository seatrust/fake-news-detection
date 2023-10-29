# fake-news-detection
data = pd.read_csv("C:/Arnab/news.csv") 

data.head()


<img width="571" alt="fake news" src="https://github.com/seatrust/fake-news-detection/assets/114236647/890b364f-0b28-4700-bc48-9eb2cbb77eb0">

df = data.replace({ "REAL" : 1, "FAKE": 0})

df.head()

<img width="568" alt="fake newas 2" src="https://github.com/seatrust/fake-news-detection/assets/114236647/de8bfd95-9eac-4262-8dfc-e1227fadf1f3">

df1.isnull().sum()

<img width="98" alt="fake 3" src="https://github.com/seatrust/fake-news-detection/assets/114236647/a839692e-f40c-4703-b328-8b36bc05bd67">


Data Preprocessing
In data processing, we will focus on the text column on this data which actually contains the news part. We will modify this text column to extract more information to make the model more predictable. To extract information from the text column, we will use a library, which we know by the name of ‘nltk’.

Here we will use functionalities of the ‘nltk‘ library named Removing Stopwords, Tokenization, and Lemmatization. So we will see these functionalities one by one with these three examples. Hope you will have a better understanding of extracting information from the text column after this.
