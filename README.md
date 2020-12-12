# Amazon-Review-Tags

### Problem Statement ⚡

<strong>Customers write product reviews on ecommerce websites like Amazon. Amazon processes the reviews to generate commonly
occurring tags. But, there exist multiple tags referring to the same thing. Create algorithm to combine review tags based on meaning.  </strong>

### What it does 🤖

We created an algorithm to extract from the reviews online we used the following dataset : [Dataset](https://bit.ly/SHPL1)
to train a Natural Language Processing model. 

### How We built it 💡

1. We used Google Colab to create and implement the model. 
2. We used NLTK and Spacy to preprocess the review data. 
3. For training our model we used a deep learning model called Seq2Seq model to summarize the review text summarizer where the input is a long sequence of words (in a text body), and the output is a short summary (which is a sequence as well). So, we can model this as a Many-to-Many Seq2Seq problem. Below is a typical Seq2Seq model architecture:

<p  align="center"><img  src = "https://github.com/Apurva-tech/Amazon-Review-Tags/blob/main/assets/image1.jpg"></p>

4. After summarizing the review we extract the subjects from the summary sentences
5. <strong>Voila!! The subjects extracted from the summary is tags we were looking for!</strong> 

### Challenges we ran into 🧠

- Pre-processing the review data for model. 
- Creating the model 
- Extracting subject from summary. 

### Accomplishments that we are proud of 😌

We created a fully functional algorithm to extract tags from a given review. 

<p  align="center"><img src = "https://github.com/Apurva-tech/Amazon-Review-Tags/blob/main/assets/image2.jpeg"></p>


### What we learned 🤩

We learned basic structure of natural language processing using nltk and spaCy using Python. And creating a deep learning model Seq2Seq. 

### What's next for the project 📈

#### ➡ Creating a functional API

Deploying the model as an open source API. 

#### ➡ Improve the NLP model. 

The accuracy of the NLP model can be increased in the future.

### Help File 💻

- [x] Clone the repository to your local directory
- `https://github.com/Apurva-tech/Amazon-Review-Tags`

- [x] Download all the requirements

- [x] Run the colab .ipynb file

- [x] See the tags being extracted and clustered. 


### Built With ⚙

#### The NLP Model
- [x] Python
  - NLTK
  - Numpy
  - Pandas
  - Seaborn
  - SpaCy
  - Matplotlib
  - Tensorflow

### Cheers to the team 🥂

- [Rahul Gowlapalli](https://github.com/rahulg009)
- [Apurva Sharma](https://github.com/Apurva-tech)


