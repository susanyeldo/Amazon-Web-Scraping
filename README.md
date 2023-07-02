# Amazon Web Scraping

Product:
Apple iPhone 13 (128GB) - Midnight

Product link:
https://www.amazon.in/Apple-iPhone-13-128GB-Midnight/dp/B09G9HD6PD/ref=cm_cr_arp_d_product_top?ie=UTF8


Aim:
1. To scrap data(product data and reviews) regarding a product on Amazon - using BeautifulSoup
2. Activate automated data collection and email dispatch when price falls below threshold (Google Authentication)
3. Perform sentiment analysis using BiLSTM, using sentiment scorer VADER

Results:
1. After printing the WordCloud, we can pick out the common concerns/best features of the product
2. After evalutation of the model, the accuracy of BiLSTM came out to be 89.99%
3. The loss was calculated to be 0.29


Limitations:
1. Amazon allowed maximum of 97 review to be extracted. Therefore our training dataset is small which may have led to overfitted results.
2. The model is only as good as its sentiment scorer. While VADER is one of the best sentiment scorers, it does not take into account advanced forms of communication like sarcasm.
