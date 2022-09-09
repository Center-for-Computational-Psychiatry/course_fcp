# Foundations of computational psychiatry - Fall 2022

**Instructors**: [Vincenzo Fiore](https://profiles.mountsinai.org/vincenzo-guido-fiore), [Angela Radulescu](https://www.angelaradulescu.com/) 

**Teaching Assistant**: [Kaustubh Kulkarni](https://kulkarnik.github.io/)

**Time**: Mondays 1-4pm

**Location**: Sinai Center for Computational Psychiatry, 55 W 125th St, Floor 13

**Format:** This course will have a hybrid lecture and lab structure. Lectures will be held in person and will be followed by a live lab portion during which we will implement some of the key concepts covered in lecture. We encourage in person attendance, though we will make available recordings of each *lecture*.

**Overview:** At the intersection of psychology, neuroscience and AI, computational models are aimed at understanding the mechanisms underlying cognitive processes that underlie behavior, and how these processes are altered in neuropsychiatric disorders. In this course, we will discuss some of the goals, foundational ideas, and technical concepts behind computational modeling. We will survey several modeling approaches, including Bayesian inference, reinforcement learning and neural modeling. And we will get hands on experience with building and fitting models to data from different modalities.  

**Pre-requisites:** The course assumes beginner-to-intermediate proficiency in programming tools for data analysis. For each class, coding materials will be provided in MATLAB or Python. In general, materials will take the form of self-contained codebases which students can modify to suit the problem at hand. If you are unsure of the expected coding level, you are encouraged to consult with the instructors.

Recommended background: 

+ [MATLAB: Getting Started with MATLAB: Basic commands](https://www.mathworks.com/help/releases/R2017a/matlab/getting-started-with-matlab.html)
+ [Matlab Programming fundamentals](https://www.mathworks.com/help/pdf_doc/matlab/matlab_prog.pdf) 
+ [Python 101 Google Colab notebook](https://colab.research.google.com/drive/1RgQqcpMyfU8FOZDgIARLqhvpKaefUMnO?usp=sharing)
+ [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
+ [Mathesaurus](http://mathesaurus.sourceforge.net/)

**Readings:** Reading for the course (~4 hours / week) will consist of selections from two textbooks, as well as recent literature in computational psychiatry. Textbooks: 

+ [Sutton, R. S., & Barto, A. G. (2018). Reinforcement learning: An introduction. MIT press.](http://incompleteideas.net/book/the-book-2nd.html)

+ [Ma, W., & Kording, K. P., & Goldreich D. (2022). Bayesian models of perception and action.](https://www.cns.nyu.edu/malab/bayesianbook.html) 

**Schedule:**

+ **Sept. 12th**: Intro. to Reinforcement learning and decision-making ([S&B Ch. 1](https://www.dropbox.com/s/c5bj6odbm0g3i0g/RLbook2020-Chapter%201.pdf?dl=0))([S&B Ch. 2](https://www.dropbox.com/s/w1v1gey5r796qwh/RLbook2020-Chapter%202.pdf?dl=0))([Addicott et al.](https://www.nature.com/articles/npp2017108))(slides)(recording)(code)
    + History and recent developments 
    + Multi-armed bandits 
    + The explore-exploit trade-off

+ **Sept. 19th**: Formalizing optimal behavior ([S&B Ch. 3](https://www.dropbox.com/s/l00l0ctmcuhj42y/RLbook2020-Chapter%203.pdf?dl=0))([S&B Ch. 4](https://www.dropbox.com/s/bdp3wp63q7myucv/RLbook2020-Chapter%204.pdf?dl=0))([Zorowitz et al.](https://cpsyjournal.org/article/10.1162/CPSY_a_00026/))(slides)(recording)(code)
    + Markov Decision Processes (MDPs) 
    + Bellman Equations 
    + Dynamic Programming

+ **Sept. 26th**: Reinforcement learning in the brain ([S&B Ch. 6](https://www.dropbox.com/s/p2njyivzwzaljis/RLbook2020-Chapter%206.pdf?dl=0))([Eldar et al.](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613%2815%2900174-6))(slides)(recording)(code)
    + TD-Learning 
    + Biological basis of TD-Learning 
    + Actor-Critic and policy-gradient methods

+ **Oct. 3rd**: Multiple learning systems ([S&B Ch. 8](https://www.dropbox.com/s/p2njyivzwzaljis/RLbook2020-Chapter%206.pdf?dl=0))([Gillan et al.](https://elifesciences.org/articles/11305.pdf))(slides)(recording)(code)
    + Model-free control
    + Model-based control
    + Hybrid approaches

+ **Oct. 17th**: Scaling to real-world problems ([S&B Ch. 9](https://www.dropbox.com/s/cdddxc4ijvf7nof/RLbook2020-Chapter%209.pdf?dl=0))([Radulescu et al.](https://www.sciencedirect.com/science/article/pii/S0959438818300928))(slides)(recording)(code)
    + Representation learning 
    + Deep RL
    + Partially Observable Markov Decision Processes (POMDPs)

+ **Oct. 24th**: Parameter estimation ([M&K&G Section C](blank))([Daw](https://www.princeton.edu/~ndaw/d10.pdf))(slides)(recording)(code)
    + Belief updating with discrete evidence
    + Probabilistic predictions
    + Precision in belief updating

+ **Oct. 31st**: Bayesian inference in the brain I ([M&K&G Ch. 1](blank))([M&K&G Ch. 2](blank))
    + Belief updating with discrete evidence
    + Probabilistic predictions
    + Precision in belief updating

+ **Nov. 7th**: Bayesian inference in the brain II ([M&K&G Ch. 5](blank))([M&K&G Ch. 11](blank))
    + Elements of active inference
    + Hierarchical Bayesian networks

+ **Dec. 5th**: Modeling social agents 
    + Basic behavioral game theory
    + Complex social interactions

+ **Dec. 12th**: Final presentations

**Grading:** 

This is a P/F course. The course is considered passed based on attendance and participation, completion coding exercises and the final project. 




