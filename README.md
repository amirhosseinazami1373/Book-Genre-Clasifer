<h1 style="display: flex; justify-content: space-between; align-items: right;">
    <span>Book-Genre Classifier</span>
    <img src="https://spark.apache.org/images/spark-logo-trademark.png" style="width: 100px;"/>
</h1>


Have you ever tried to guess the genre of a book by reading its title? Well, in this project, I was trying to do it using a massive database of Books (their titles and genres), MLLib Spark, and the use of three different ML models, including:

**1- Support Vector Machine (SVM)**

**2- Logistic Regression**

**3- Neural Networks**

You will need to download the data using this link:

  https://github.com/uchidalab/book-dataset.git

The genres and labels of the books are as follows:

|Label|Category Name|Size|
|---|---|---|
|0|Arts & Photography|6,460|
|1|Biographies & Memoirs|4,261|
|2|Business & Money|9,965|
|3|Calendars|2,636|
|4|Children's Books|13,605|
|5|Comics & Graphic Novels|3,026|
|6|Computers & Technology|7,979|
|7|Cookbooks, Food & Wine|8,802|
|8|Crafts, Hobbies & Home|9,934|
|9|Christian Books & Bibles|9,139|
|10|Engineering & Transportation|2,672|
|11|Health, Fitness & Dieting|11,886|
|12|History|6,807|
|13|Humor & Entertainment|6,896|
|14|Law|7,314|
|15|Literature & Fiction|7,580|
|16|Medical Books|12,089|
|17|Mystery, Thriller & Suspense|1,998|
|18|Parenting & Relationships|2,523|
|19|Politics & Social Sciences|3,402|
|20|Reference|3,268|
|21|Religion & Spirituality|7,559|
|22|Romance|4,291|
|23|Science & Math|9,276|
|24|Science Fiction & Fantasy|3,800|
|25|Self-Help|2,703|
|26|Sports & Outdoors|5,968|
|27|Teen & Young Adult|7,489|
|28|Test Preparation|2,906|
|29|Travel|18,338|
|30|Gay & Lesbian|1,339|
|31|Education & Teaching|1,664|

## Challenges:
**Variability in Text Data:**

Besides some simple book titles, text data from book titles can vary significantly in style, length, and complexity, posing substantial challenges in standardization and processing within a big data framework.
Subjectivity in Genre Definition: The subjective nature of genre classification requires the models to discern subtle nuances that differentiate genres, a significant challenge given the complexity of textual data.

**Efficiency and Scalability on Spark MLlib:** 

Implementing ML algorithms efficiently on Spark MLlib to handle large datasets without compromising classification speed or accuracy. Specifically, deploying algorithms like SVM, which involves iterative parameter tuning and optimization, can be computationally intensive on distributed systems. Similarly, configuring multilayer neural networks on Spark requires careful distributed data management and extensive tuning to achieve optimal performance and convergence.

**Interpretability of Results:**

It is essential to provide results that are interpretable for stakeholders, such as publishers and authors, ensuring that the classification models are accurate and transparent in their genre categorization processes.

**Technical Complexity of Spark MLlib:**

Spark MLlib, while powerful, presents its own set of challenges, including the difficulty of deploying complex models such as SVMs and deep neural networks. These models require extensive custom configuration and optimization to perform effectively in a distributed computing environment, complicating their implementation and scalability.

