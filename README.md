# Deep Learning & Applied AI @Sapienza

Course material, 2nd semester a.y. 2022/2023, Dept. of Computer Science

### News
- **26/04/2023:** The **midterm sheet** is now published. Students who wish to have their answers checked must deliver **by today at 15:00** via email (rodola@di.uniroma1.it).
- **19/04/2023:** The lecture of **April 25th is cancelled** due to the Liberation Day, as per the academic calendar. On **April 26th** we will do a self-evaluation test; more details will follow.
- **03/04/2023:** The lecture of **April 11th is cancelled** due to Easter holidays, as per the academic calendar.
- **27/03/2023:** The lectures of Tue 28 and Wed 29 March **will be held remotely** due to illness. _Tue 28_: The notebook will be uploaded shortly, and you can work on it from your homes; the Professor and the teaching assistants will be on the Discord server during the 3 hours, to assist you in real time. _Wed 29_: The slides are already up, together with a video recording of the Professor explaining the new topic; the recording is from DLAI 2021, which overlaps well with the new slides up to some simplifications.
- **11/02/2023:** The course website is online. Welcome to DLAI 2022/23! **The course will start on Tue 28th February**.

### Logistics

**Lecturer:** Prof. Emanuele Rodolà

**Assistants:** Dr. Antonio Norelli, Dr. Luca Moschella, Dr. Marco Fumero

**When:** Tuesdays 13:00--16:00 and Wednesdays 13:00--15:00

**Where:**

Physical classrooms: Aula Magna Edificio C RM111 (Tuesdays) and Aula Alfa RM062 (Wednesdays)

There is no virtual classroom, and the lectures will not be recorded.

**Q & A:** We will use a [Discord](https://discord.com/) server. More details during the first lessons.

### Pre-requisites

Python fundamentals; calculus; linear algebra.

### Textbook and reading material

Due to the continuously evolving nature of the topic, there is no fixed textbook as a reference. Specific material in the form of scientific articles and book chapters will be given throughout the lectures.

In addition, [here](https://github.com/erodola/DLAI-s2-2022/raw/main/resources/Course_notes_Crisostomi.pdf) you can find some supplementary course notes.

### Grading

Evaluation proceeds according to the following steps:

- A midterm self-evaluation test (optional, does not concur to the final grade)
- A final written exam (**mandatory**, accounts for 60% of the final grade)
- A project (**mandatory**, accounts for 40% of the final grade)
- An oral exam (optional, attributes at most 3 points, added to or subtracted from the final grade)

We may require an oral exam in doubtful cases or whenever necessary.

Here you can find some example sheets of past written exams:

- [June 2021](https://github.com/erodola/DLAI-s2-2021/raw/main/exams/June-2021.pdf)
- [July 2021](https://github.com/erodola/DLAI-s2-2021/raw/main/exams/July-2021.pdf)
- [September 2021](https://github.com/erodola/DLAI-s2-2021/raw/main/exams/September-2021.pdf)
- [October 2021](https://github.com/erodola/DLAI-s2-2021/raw/main/exams/October-2021.pdf)
- [January 2022](https://github.com/erodola/DLAI-s2-2022/raw/main/exams/Jan22.pdf)
- [February 2022](https://github.com/erodola/DLAI-s2-2022/raw/main/exams/Feb22.pdf)

### Lectures

**Date** | **Topic** | **Reading** | **Code & Data**
------------ | ------------- | ------------ | ------------
Tue 28 Feb | Introduction | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/01_intro/01-intro.pdf) |
Wed 01 Mar | Data, features, and embeddings | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/02_data/02-data.pdf) ; [linear algebra recap](https://github.com/erodola/DLAI-s2-2023/raw/main/02_data/03-linalg.pdf) ; [matrix notes](https://github.com/erodola/DLAI-s2-2023/raw/main/02_data/03b-matrix.pdf) |
Tue 07 Mar | Tensor manipulation and Tensor operations | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2023/blob/main/labs/01/01_Tensor_basics_2023.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2023/blob/main/labs/01/02_Tensor_operations_2023.ipynb)
Wed 08 Mar | Linear regression, convexity, and gradients | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/04_linear/04-linear.pdf) |
Tue 14 Mar | Linear models and Pytorch Datasets | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2023/blob/main/labs/03_Linear_models_and_Pytorch_Datasets_2023.ipynb)
Wed 15 Mar | Overfitting and going nonlinear | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/05_nonlinear/05-nonlinear.pdf) |
Tue 21 Mar | Logistic Regression and Optimization | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2023/blob/main/labs/04/4_Logistic_Regression_and_Optimization.ipynb)
Wed 22 Mar | Stochastic gradient descent | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/06_sgd/06-sgd.pdf) |
Tue 28 Mar |  Autograd and Modules | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2023/blob/main/labs/05/5_Autograd_and_Modules_2023.ipynb)
Wed 29 Mar | Multi-layer perceptron and back-propagation | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/07_mlp/07-mlp.pdf) ; [video](https://drive.google.com/file/d/1Eb25ov9i-Zx5DxHYYpckltSNpT6U8FDH/view?usp=sharing) |
Tue 04 Apr | Convolutional Neural Networks   |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2023/blob/main/labs/06/6_Convolutional_Neural_Networks_2023.ipynb) |
Wed 05 Apr | Convolutional Neural Networks | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/08_cnn/08-cnn.pdf) |
Tue 11 Apr | **Easter holidays** |  |
Wed 12 Apr | Regularization, batchnorm and dropout | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/09_regular/09-regular.pdf) |
Tue 18 Apr | Uncertainty, regularization and the deep learning toolset | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/labs/07/ML%20Tooling%202022.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2023/blob/main/labs/07/7_Uncertainty,_regularization_and_the_deep_learning_toolset.ipynb) |
Wed 19 Apr | Deep generative models | [slides](https://github.com/erodola/DLAI-s2-2023/raw/main/10_generative/10-generative.pdf) ; [video](https://drive.google.com/file/d/1GCsGIEumWR0GMJ9OijYjwMhq61OFKTGh/view?usp=sharing) |
Tue 25 Apr | **Liberation Day** |  |
Wed 26 Apr | **Midterm self-evaluation** | [sheet](https://github.com/erodola/DLAI-s2-2023/raw/main/DLAI_Apr26_Midterm.pdf)  |
