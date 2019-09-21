** abstract

With the increasing popularity of student response systems (SRS), such as Socrative, students can provide immediate feedback of their understanding to lecturers during in-class exercises. Typically, students are asked to answer multiple choice or true/false questions. Then, the SRS will show the proportion of students who answered each choice in a given question. With this information, the lecturer can provide immediate targeted feedback. This task becomes difficult when students are asked to answer short open-ended questions because their answers can’t be analyzed by a SRS. If the class size is significantly large, let’s say a hundred students, it is impossible for the lecturer to read through all of the answers, assess how students did and give feedback in a reasonable amount of time. This is unfortunate because open-ended questions enable teachers to capture student’s higher level of understanding than close-ended questions. [1]

Previous work on automatic short answer grading used different techniques such as unsupervised and supervised learning. In the context of in-class exercises, supervised learning is limited. It would require a set of answers to be graded by teachers to build a model able to predict the grade of a new answer.[2] Thus, the lecturer would not be able to ask a question that hasn’t been answered before. On the other end, unsupervised learning, such as clustering algorithms are used to cluster student responses and even separate excellent and weak answers. [3] However, if the clustering algorithm does not take into account synonyms, then this approach is also ineffective in categorizing answers accurately.

Filtering inappropriate short answers in peer learning applications

Vincent Gagnon
Audrey Labrie
Sameer Bathnagar
Michel Desmarais

Applications that adopt peer instruction and active learning make use of short student answers as a learning opportunity: they take some answers as topics of discussion in class, or select answer rationales from peers to foster self-reflection on the learner's own rationale to a question.  However, experience with these applications reveals that some answers are irrelevant, inappropriate, or could even be offensive, and must therefore be filtered out.  Automatic identification of these rationales is the topic of this research.  We introduce an easy-to-implement approach based on standard text classification techniques, namely bag of words and vector space models, and show its effectiveness for filtering irrelevant answers.
