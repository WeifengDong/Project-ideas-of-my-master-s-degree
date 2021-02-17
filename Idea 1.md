# Idea 1

## **A software for posting job information based on a recommendation system**



### **Background and Gap** 

I am faced with a job dilemma. I have various job communication groups and pay attention to a large number of job application and company web pages, which gave me a headache. Job groups usually post temporary needs for a particular project group, company web pages post long-term needs, and job applications fall somewhere in between. What I've learned, at least in China, is that there's no software that combines all three. On the other hand, in China, the relevant software mainly uses the tag screening and search technology, and does not emphasize the recommendation system. 

 

### **Design of Software** 

So I wanted to make a comprehensive but lightweight job information platform. Crawler crawls and company releases are sources of information. The software could be an app or a WeChat app - as I don't know the job information situation in UK, I would like to target the project to the Chinese environment in the beginning. If you don't agree with this, I can learn more about job hunting in the UK or internationally afterwards. 

Students during the job-seeking season or employees interested in jumping ship would be able to swipe job postings on a daily basis like they do on Tic Toc. Of course they can also access it through search. After finding companies they are interested in, they use the contact information or links to take the next step. 

In addition, after accumulating a certain user base, I have two user-friendly growth and profit plans. This part has nothing to do with Bayes, so it's not going to expand. **I believe this is a project that is interesting in theory and feasible in reality.** 

 

### **Implementation of Recommendation System**

I think it can be realized by **Bayesian Personalized Ranking (BPR)**, which is the core technology of the software. 

Bayesian Personalized Ranking provides different ranking lists for different users and information, which is exactly what is needed for this project. As a pairwise approach, it also has better accuracy and robustness. 

First of all, the user as the first variable "a" can form the user set **A**, while factors such as occupation, industry, region and salary extracted from the text of recruitment information are taken as variable "b" to form information set "B", and "X" is set as the information matrix of users and information: *|A|**×**|B|*. "X" is approximate to the product of the two lower rank matrix "W":|A|**×**K and "H":|B|**×**K. The key goal is to find the most suitable matrices "W" and "H". They are found using maximum posterior estimation, and then the gradient descent method is used as a learning algorithm to iterate the final target matrices W" and "H". 

The project can be tested by volunteers or compared with other algorithms, such as matrix factorization(MF) and most popular(MP). 



### **about Myself** 

To be honest, I haven't implemented a whole recommender system, nor have I applied Bayesian theory, which is my weakness. 

However, I have some basic skills, such as C, MATLAB and Python. And I'm also learning Java now. Besides, I have relevant experience, like using GitHub programs to crawl some information and designing a prototype of a fabric recommendation software, so I have a certain understanding of relevant theories. What's more, I believe I am a good learner. I once participated in an entrepreneurship competition and completed a fabric image retrieval system based on traditional algorithms for an enterprise. I also had an internship in a large group and a start-up, which can prove my learning ability. 

Another disadvantage is that my oral expression and listening are poor. But I am qualified in writing and reading (got 8/9 in IELTS) and will not let anyone down! 

 

### **End** 

This is a project I really want to realize, and it will be of great help to my future development. If you think there is any need for modification(for example, not only the software design, but also the algorithm can be innovative), I am willing to make adjustments. I hope you can guide me! 
