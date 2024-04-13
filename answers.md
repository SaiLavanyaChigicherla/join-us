## About You.

1. Introduce yourself.
Hello, I'm Sai Lavanya, and I am thrilled to have the opportunity to introduce myself to you. While my academic background is in Civil Engineering, I discovered my passion for data science during my final year of college. I have recently completed a rigorous training on Data Science to strengthen my skills in data analysis, machine learning, and statistical modeling. I am proficient in languages like Python and SQL. I have worked on Book Recommendation System project in which I have used collaborative filtering techniques to personalize recommendations. My transition into data science has been driven by my curiosity, analytical mindset, and a strong desire to make an impact through data-driven insights. I am excited about the opportunity to contribute my unique perspective and skills to Lightrains Technolabs' data science initiatives. Thank you for considering my application.

2. Do you own a personal computer?
Yes I do

3. Describe your development environment. (Your OS, IDE, Editor and Config manager if any)
My development environment varies depending on the task at hand, but typically I use Windows operating system for its stability and customization options. For coding, I prefer using Visual Studio Code or Jupyter Notebook as my IDE due to its versatility. I also rely on Git for version control.
Additionally, I use programming languages such as Python, and occasionally SQL depending on the project requirements. Overall, my development environment is designed to be efficient and adaptable to different coding tasks.


## Social Profile

1. Your StackOverflow Profile url.
I don't have a Stack Overflow profile at the moment. But I will definitely create it soon to contribute and learn from the community.

2. Personal website, blog or something you want us to see.
I don’t have anything specific to share in that regard.


## The real stuff.

1. Which all programming languages are installed on your system.
I just bought my system 2 months back and as of now I have MS Office, Anaconda, MySQL server and PowerBI desktop.

2. Write a function that takes a number and returns a list of its digits in an array.
def get_digits(number):
    digits_list = [int(digit) for digit in str(number)]
    return digits_list
get_digits(180202) #Example
 
3. Remove duplicates of an array and returning an array of only unique elements
def remove_duplicates(arr):
    unique_elements = set(arr)
    unique_list = list(unique_elements)
    return unique_list
remove_duplicates([1,2,2,3,4,4,5,6,6]) #Example

4. Write function that translates a text to Pig Latin and back. English is translated to Pig Latin by taking the first letter of every word, moving it to the end of the word and adding ‘ay’. “The quick brown fox” becomes “Hetay uickqay rownbay oxfay”.
def to_piglatin(text):
    words = text.split()
    piglatin_words = []
    for i in words:
        piglatin_word = i[1:] + i[0] + 'ay' 
        piglatin_words.append(piglatin_word)
    return ' '.join(piglatin_words)
def from_piglatin(piglatin_text):
    words = piglatin_text.split()
    english_words = []
    for i in words:
        english_word = i[-3] + i[:-3] 
        english_words.append(english_word)
    return ' '.join(english_words)
text = "The quick brown fox"
piglatin_text = to_piglatin(text)
print(piglatin_text) 
original_text = from_piglatin(piglatin_text)
print(original_text)

5. Write a function that rotates a list by `k` elements. For example [1,2,3,4,5,6] rotated by `2` becomes [3,4,5,6,1,2]. Try solving this without creating a copy of the list. How many swap or move operations do you need?

Note: It is not mandatory that you answer all the questions. You may leave some behind and create a PR. However maximum questions will earn you maximum points. It is advised that you answer all the puzzles in a language that you are applying for.

### Notes

- [Pig Latin](https://en.wikipedia.org/wiki/Pig_Latin)
- [Fun](http://www.snowcrest.net/donnelly/piglatin.html)
- [Nice Read](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
