# fake-news-detection
data = pd.read_csv("C:/Arnab/news.csv") 

data.head()

df = pd.DataFrame(data)

df.head()

<img width="571" alt="fake news" src="https://github.com/seatrust/fake-news-detection/assets/114236647/890b364f-0b28-4700-bc48-9eb2cbb77eb0">

df = df.replace({ "REAL" : 1, "FAKE": 0})

df.head()

<img width="568" alt="fake newas 2" src="https://github.com/seatrust/fake-news-detection/assets/114236647/de8bfd95-9eac-4262-8dfc-e1227fadf1f3">
