# 100DaysOfML

## Day 1 : Aug 21, 2018

**Today's Progress** : I have learnt about google datalab api and Tensorflow
estimators

**Thoughts** : Tensorflow is a fucking powerfull framework, it's awesome to see
how to solve an ML problem with such simplicity of code. Datalab doesn't
impressed me that much. I'm not quite into Notebooks yet. I miss having VIM
superpowers, and web editting feels terrible bad. Also the connection with
github repositories sucks.


## Day 2 : Aug 22, 2018

**Today's Progress** : Learnt Pandas DataFrames basics and solved my first
problem from scratch, implementing a DNN.

**Thoughts** : Datalab and Notebooks are cool. The problem with the repository
connection is somehow addressed with ungit, which is a really nice interface to
git. Using tensorflow is a bomb!

**Link of Work:**
[Commit](https://github.com/mxlian/100DaysOfML/commit/af4e7157a741e5633b52a4d044afec8b646b5739)


## Day 3 : Aug 23, 2018

**Today's Progress** : Following Coursera TF course. Learning about batching
inputs. Struggling a bit to get all things in place and reading a lot of docs.
There are a lot of things to tweak in the function calls and is nice to read
what arguments can be passed, so you get an idea how to do the stuff with TF and
pandas. Couldn't finish the assignment today, need to debug how to use the map
function, bug happy with the overall architecture of the solution

**Thoughts** : Even if you can create code with a few lines, you need to know
the parameters that you're using and that you can use to be a powerful coder.

**Link of Work:**
[Commit](https://github.com/mxlian/100DaysOfML/commit/fa34ccc58be93e59525eb733d64a565d69a3b67e)


## Day 4 : Aug 24, 2018

**Today's Progress** :  Using TF Estimators for distributed work and TensorBoard
for analysis. Learnt a bit of Keras and Torch.

**Thoughts** : Using the Graphs in TF is not that intuitive as i originally
thought and is hard to debug, at least for now.

**Link of Work:** Im' stuck trying to apply some transformation in the input
function to transfor a list of float32 scalars to a rounded version with 0.1
precission.


## Day 5 : Aug 25, 2018

**Today's Progress** : Learned about Tensors in detail and debugging. I'm trying to debug the input function from day 3 to map the round function to transformate the input data.

**Thoughts** : I'm making slow progress on this because i need to grasp more the details. Debugging the execution graph is not that easy if you don't understand how it works.

**Link of Work:**: Experiments in an empty notebook [Commit](https://github.com/mxlian/100DaysOfML/commit/9d9c4e9c1745475f361082b1329a5daae0325b7f)


## Day 6 : Sept 2, 2018

**Today's Progress** : I completed week Nr2 of TF course from Google on coursera. I got an Estimator, with data loading and monitoring with TensorBoard. The model isn't performing well. Will improve it in the next week

**Thoughts** : I was confronted with probably what is the real deal in ML. Having a model, wich is not performing well and having no idea why. Data is good and clean (it seems)

**Link of Work:**: [Coursera](https://www.coursera.org/learn/intro-tensorflow/home/week/2)


## Day 7 : Sept 3, 2018

**Today's Progress** : Compleeted week 3 of TF course. Learned how to use CMLE to pre test a model, updload data to buckets, submit the training job, monitor progress and publish the trained model.

**Thoughts** : CMLE is incredible powerful. It puts the power of ML and expensive hardware in the hands of everyone.

**Link of Work:** [notebook](https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/machine_learning/deepdive/03_tensorflow/e_cloudmle.ipynb)


## Day 8 : Sept 4, 2018

**Today's Progress** : 4th part of the TF course. Today I was learning about
feature engeniering. This is a serious and hard part of ML. It takes sometime
about 70-80% of the project time.

**Thoughts** : Doing some exercises this is one of those things that look easy
but they really aren't. The insight knowledge of the domain is very strong
correlated with the quality of this task.

**Link of Work:** [coursera](https://www.coursera.org/learn/feature-engineering/lecture/paE4Y/introduction-to-feature-engineering)


## Day 9 : Sept 8, 2018

**Today's Progress** : Feature enginieering and exercise. One shot encoding.
Important is that if data is somtimes not available, the availability or not
should be encoded as a feature too. As a difference with statistics in ML
outliers aren't ignored but learned

**Thoughts** : Interesting how many things got taken care already, there is also
almost no need to make variables normalization any more.

**Link of Work:**: [Commit](https://github.com/mxlian/100DaysOfML/commit/8f82ad0c508dbbd83e666f1345cd1b8cd31ec18b)


## Day 10: Sept 14, 2018

**Today's Progress**: Using apache beam locally and pushing the job to dataflow in Google Computing Plattform GCP

**Thoughts**: Awesome abstraction and impresive syntax in python (overloading of the pipe symbol). I don't think this is the most important now to learn, as I would like to have models working where i cant solve and needed to use this feature first. That way it it would allow me to get into the details faster, however it seems that there arent many tricky details

**Link of Work:**: [Sources](https://github.com/GoogleCloudPlatform/training-data-analyst/courses/data_analysis/lab2/python)


## Day 11: Sept 17, 2018

**Today's Progress**: Apache Beam and MapReduce

**Thoughts**: 

**Link of Work:**: [coursera](https://www.coursera.org/learn/feature-engineering/gradedLti/K7cCS/mapreduce-in-dataflow)


## Day 12: Sept 21, 2018

**Today's Progress**: Took the test regarding Apache Beam and MapReduce

**Thoughts**: 

**Link of Work:**: [coursera](https://www.coursera.org/learn/feature-engineering/gradedLti/K7cCS/mapreduce-in-dataflow)


## Day 13: Sept 23, 2018

**Today's Progress**: Learning about dataprep, Trifecta product integrated in GCP

**Thoughts**: Extremely boring subject, have trouble concentrating

**Link of Work:**: [coursera](https://www.coursera.org/learn/feature-engineering/lecture/DKOZG/preprocessing-with-cloud-dataprep)


## Day 14: Sept 25, 2018

**Today's Progress**: Did a Lab + Builtin tutorial of dataprep

**Thoughts**: Fucking awesome tool, i'm blown. Sooo easy to use and intuitive I think old Datasciencist are thinking that nowdays everything is so easy for newcommers. I also find great that all computing gets automatically outsourced to GCP. The only downside is the slow spin ups time, which makes the workflow of a DS quite intermitent.

**Link of Work:**: [coursera](https://www.coursera.org/learn/feature-engineering/gradedLti/bx2Ie/computing-time-windowed-features-in-cloud-dataprep)


## Day 15: Sept 27, 2018

**Today's Progress**: Learning feature crossing

**Thoughts**: This allows to use non-linear features with linear models. Adventages from linear models are simplicity and convexity (one local minima easy to find). Using binning with feature crossing is a common practice but generates sparse data input (only one bin activates the rest are just zeros). Handling of sparsing data is then important. Tensor flow helps with that

**Link of Work:**: [coursera](https://www.coursera.org/learn/feature-engineering/lecture/V9OqG/implementing-feature-crosses)



