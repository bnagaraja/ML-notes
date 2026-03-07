# ML - Acronyms

### Resources

#### Training 
The process of determining the ideal parameters (weights and biases) comprising a model. During training, a system reads in examples and gradually adjusts parameters. Training uses each example anywhere from a few times to billions of times. 

##### Model
In general, any mathematical construct that processes input data and returns output. Phrased differently, a model is the set of parameters and structure needed for a system to make predictions. In supervised machine learning, a model takes an example as input and infers a prediction as output.

#### supervised machine learning
Training a model from features and their corresponding labels. Supervised machine learning is analogous to learning a subject by studying a set of questions and their corresponding answers. After mastering the mapping between questions and answers, a student can then provide answers to new (never-before-seen) questions on the same topic.

#### feature
An input variable to a machine learning model. An example consists of one or more features. For instance, suppose you are training a model to determine the influence of weather conditions on student test scores. The following table shows three examples, each of which contains three features and one label:

Features	                                        Label
----
Temperature	    Humidity	Pressure	            Test score
----
15	                47	        998	                92
19	                34	        1020	            84
18	                92	        1012	            87
----

#### label
In supervised machine learning, the "answer" or "result" portion of an example.

Each labeled example consists of one or more features and a label. For example, in a spam detection dataset, the label would probably be either "spam" or "not spam." In a rainfall dataset, the label might be the amount of rain that fell during a certain period.