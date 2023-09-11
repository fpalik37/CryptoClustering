# CryptoClustering


The CryptoClustering Challenge (Module 19) provides for an excellent introduction to Machine Learning, and in particular, Unsupervised Machine Learning.  The idea is to create a machine learning model that groups cryptocurrencies in way that lends insight to their prospective profitability.  

Specifically here, I applied clustering algorithms to standardized data and then to the principal components of that data-- the goal being that by comparing the results, insight that forms the bedrock of future investment advice will arise 😊.

In line with ‘Unsupervised Learning’ (which fundamentally relies on starting input), I began with a given dataset - cypto_market_data.csv.  The data is composed of 41 different cryptocurrencies, each followed over the course of the year, their % price change documented at specific timepoints throughout.

### Process Overview
I used the k-means algorithm.  Note, the k-means algorithm is the simplest and most common algorithm used to group data points into clusters. Clustering is simply (but actually not-so-simple) grouping of data in way that incorporates machine-observed similarities between that data, i.e., ‘like data’ gets grouped together.  Data clustering is optimized by selecting the best value for ‘k’ (i.e., the ideal number of clusters). The best value of k was determined by the Elbow method – which is a graphical plotting via a very ‘mathy’ concept called ‘inertia’.  The ideal value of k is illustrated where the bend in the graph’s ‘elbow’ occurs.

We can often enhance and optimize machine learning algorithms by applying Principal Component Analysis, or PCA. PCA reduces the number of factors by transforming a large set of features (i.e., columns) into a smaller one that contains ‘most’ of the information of the original larger dataset. This process is called dimensional-reduction.  Although this often leads to a decrease in accuracy, the improved clarity of the data trends is considered more than compensatory.

### Conclusion
In the end, I visually analyzed the cluster analysis results by contrasting the outcome with and without the PCA optimization technique.  This takes the form of a final ‘composite plot’ (just a fancier term for ‘side-by-side graphs’ 😉) in order to contrast the Elbow curves.
Note the composite plot at the end of the program, Crypto_Clustering.ipynb, comprised of the following: 
1)	Elbow Curve using Crypto Market Data
2)	Elbow Curve using Crypto Market PCA
   
The comparison shows that both methods yield the same optimal k-value – 4.  Yet, the PCA method manifests increased clarity from which, undoubtedly, will come wise decisions and improved strategizing in terms of future cryptocurrency investing.

Not only was the concept of Unsupervised Machine Learning gained from this challenge, but also the practical experience of using new Python libraries, such as sklearn, practice in extensive data prep, data segmenting and scaling, and the ‘bread & butter’ programming practice that comes with constructing for loops and scatter plots, etc..  In all, a marrying of the old tricks with new leads to deeper and richer understanding. 

In the context of the exercise, it’s now off to the board of directors with my impressive portfolio proposal 😊.

### Addendum: 
Programming, algorithm development, and deeper understanding was aided by the excellent guidance of professor Alexandria Kalika, her trusty sub – Will Zigler, and the experience and generous encouragement of esteemed tutor Bethany Lindberg.



