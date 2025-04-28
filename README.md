# cmsc435-project-solved
**TO GET THIS SOLUTION VISIT:** [CMSC435 Project Solved](https://www.ankitcodinghub.com/product/cmsc-435-project-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119151&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC435 Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

The project asks your project group to develop, evaluate and compare models for the prediction of proteins that interact with DNA and RNA using a provided dataset. Your model must classify a given protein sequence into one of four outcomes, i.e., interacts with DNA (DNA), interacts with RNA (RNA), interacts with both DNA and RNA (DRNA), and does not interact with DNA or RNA (nonDRNA). Although each group will solve the same task, the corresponding designs must be unique, i.e., collaboration between groups is not allowed. There are 10 projects groups and they were formed at random. You can find your group assignment in Canvas. We also provide a slack channel for each project team where you can find and contact your teammates.

Datasets

Two datasets are/will be provided:

 sequences_training.txt (training dataset) that includes 391 DNA proteins, 523 RNA proteins, 22 DRNA proteins, and 7859 nonDRNA proteins, for the total of 8795 proteins. This dataset is already available in Canvas.

The training dataset is provided in the comma-separated format where each protein is represented by:

 the amino acid sequence

 the class encoded as DNA, RNA, DRNA, and nonDRNA

Test dataset will be the same format as the training dataset, except that the outcomes will not be provided.

Evaluation of Predictions

Your group is required to perform the 5-fold cross validation when using the training dataset. This cross validation divides the training dataset into 5 random, equal-size subsets, where one subset is used to test the prediction model and the remaining four to train/develop the prediction model; this is repeated 5 times, each time using a different subset as the test set. Consequently, this test results in predicting every sequence in the training dataset. This test procedure is supported by RapidMiner and other popular data science software/libraries.

For each of the four outcomes your group will convert the dataset into a binary problem, i.e., a given outcome (positive outcome) vs. all other outcomes (negative outcomes). For example, all proteins that are labeled as DNA will be considered as positive, and the remaining proteins (RNA, DRNA and nonDRNA) as negative. Next, for each of the four outcomes you will compute the following measures:

Sensitivity = SENS = 100*TP / (TP + FN)

Specificity = SPEC = 100*TN / (TN + FP)

Accuracy = 100* (TP+TN) / (TP+FP+TN+FN)

MCC = (TP*TN – FP*FN) / sqrt[(TP+FP)*(TP+FN)*(TN+FP)*(TN+FN)]

where TP is the number of true positives (correctly predicted positive outcomes), FP denotes false positives (negative outcomes that were predicted as positives), TN denotes true negatives (correctly predicted negative outcomes), FN stands for false negatives (positive outcomes that were predicted as negatives). You will also compute:

averageMCC = (MCCDNA + MCCRNA + MCCDRNA + MCCnonDRNA)/4 accuracy4labels = 100*TPall / (number of all protein in the dataset) where MCCDNA, MCCRNA, MCCDRNA, and MCCnonDRNA denote the MCC values when using the DNA, RNA, DRNA, and nonDRNA outcomes as the positives, and TPall is the number of correctly predicted outcomes (DNA proteins predicted as DNA proteins, RNA proteins predicted as RNA proteins, etc.). These measures can be computed based on the confusion matrix. You should round the values to one digit after the decimal point when reporting the accuracy, sensitivities, and specificity and to three digits after the decimal point when reporting MCC. You report must include the confusion matrix for your final/best solution.

Your group must also provide and summarize predictions on the blind test dataset. To do that you will compute your model using the entire training dataset (using the same design, i.e., features, values of parameters, etc., as in your best 5 fold cross validation result) and you will use this model to predict sequences from the blind test dataset. In your report, you must discuss the corresponding results on both the training and blind test dataset; on the blind test dataset you can summarize your results by explaining and comparing how many proteins were predicted with a given outcome.

Design

• Selection of a subset of the input features. This could potentially speed up computation of the model, remove weak/noisy features, and reduce overfitting. Feel free to combine results of multiple feature selection methods.

• Selection of the classification algorithm that you will use to compute your model from among many algorithms that are available in RapidMiner.

• Parametrization of the selected classification algorithm(s). This involves setting values of their key parameters.

• Building a system with multiple models that are used together. For instance, you could use multiple models that predict all 4 classes and combine their results together to generate one prediction. Check the methods in RapidMiner at Operators → Modeling → Predictive → Ensembles.

IMPORTANT NOTE 1: Ensure that your team perform all design activities (e.g., feature selection, selection and parametrization of the classification algorithms, etc.) using the 5-fold cross validation on the training dataset. Otherwise you could overfit this dataset and your results on the blind test dataset will suffer.

IMPORTANT NOTE 2: Your team’s design should be done incrementally. Start with a simple initial solution (complete the entire design, prediction, and prediction assessment process) and gradually make your design more sophisticated with the goal to improve the predictive performance. The progress report checkpoint should be based on a simple initial solution. In your final report, you should clearly indicate one best set of results, which must be selected based on the cross-validation results on the training dataset. Moreover, these results should be compared with your intermediate results (earlier/simpler designs, other alternatives, etc.) and with baseline results shown in Table 1, in order to justify your design choices. In your final report, provide your results by adding them into Table 1. This will make it easy to compare the different alternatives. Clearly indicate which result is the best/final. You should explain how you made decisions that led you a certain direction of redesigning/improving your model. You also should provide a convincing argument why and how your method is good/competitive in comparison to the real baseline result listed in Table 1.

Table 1. Predictive results based on the 5-fold cross validation on the training dataset (this table is available in Canvas).

Outcome Quality measure Baseline result Design 1 Design 2 Design 3 Best Design

DNA Sensitivity 6.9

Specificity 99.3

Accuracy 95.2

MCC 0.132

RNA Sensitivity 39.6

Specificity 98.9

Accuracy 95.3

MCC 0.501

DRNA Sensitivity 4.5

Specificity 100.0

Accuracy 99.7

MCC 0.122

nonDRNA Sensitivity 98.6

Specificity 29.8

Accuracy 91.3

MCC 0.428

averageMCC 0.296

accuracy4labels 90.8

Deliverables

Each group shall provide the following five deliverables:

1. Progress report that consists of:

 Description of the first attempt to make predictions. You should use short bullet points to list the features that you generated from the input sequences; list major data processing steps that you used to prepare the data; and name the classification algorithm that you used. This is supposed to be an initial attempt so we expect to see simple models and just a few bullet points.

 4×4 confusion matrix and the four MCC values (MCCDNA + MCCRNA + MCCDRNA + MCCnonDRNA) that the above model has produced.

 Training dataset file in txt/csv format. This file is the rectangular dataset with a fixed set of features for each object (protein) where the last (right-most) feature is the class. This is supposed to be an initial version of the dataset and so we expect to see small and simple feature set.

2. Final Report that consists of:

 Description of the design of the prediction system. You should briefly explain the features that you generated from the input sequences; how and which features were selected; which classification algorithms and their parameters you tried and why and which you have chosen; and which other design options you considered and applied.

 Results (see Evaluation of Predictions section). You must organize the results in a table using the format of Table 1. Using this format, compare your best cross validation results with the results from earlier/alternative designs and with the results shown in Table 1. Include confusion matrix for your best solution. Summarize predictions for the blind test dataset.

 Conclusions. This is a very important part of your report. You should comment on the quality of your results and compare them against the baseline results from Table 1. Also, describe your experience in this project, and explain advantages and disadvantages of your method and why you think your results are good or bad, in comparison with the other results from Table 1.

DNA

DNA

RNA

nonDRNA

…

4. In-class presentation

 10 minutes long plus 3 minutes for questions&amp;answer session  must describe the design, results and conclusions  must include the following parts:

 Motivation for your design. Briefly explain how you arrived at your final design.

 Description of your design. Explain (preferably with a diagram) how your method makes the predictions.

 Discussion and comparison of the quality of the achieved best results using the results on the training dataset and Table 1.

 Conclusions. This part is essential; see the conclusions part of your report.

5. Statement of contributions

 A short document with bullet-point style list of detailed contributions to the project for each team member. The contributions cover all aspects of the project including conceptualization and design of the methodology, implementation, testing, writing the report, preparing the presentation, making the presentation, coordination of the work, notes taking, organizing group meetings, submission of deliverables, etc.

 The contribution list for each team member should be accompanied with an estimated fraction of the total project effort, quantified in %. The effort estimates across the team members must sum up to 100%. Each team should strive to balance the effort to be equal across team member.

 Submission of the bullet-point detailed contributions is optional in case when the contributions of all team members are equal.

 Our objective for this statement is that the workload is divided evenly across team members. You should not be competing who will do more but encourage everyone to contribute equally. This statement will be used to distribute the project grade among the team members.

Marking

The evaluations of the progress report, project report and predictions constitute 15% of the final mark from the course and it will consist of the following four parts:

1. 5% for the quality of the progress report

2. 3% for the quality of the final report

3. 3% for the quality of the design of the prediction method from the final report

4. 4% for the quality of the predictions measured using the 5-fold cross validation on the training dataset from the final report and on the blind test dataset

IMPORTANT NOTE 3: For item 4, the averageMCC is the main predictive quality measure that will be used to evaluate submitted solutions but the conclusions must discuss the other quality indices as well. Bonuses of 3%, 2%, and 1% will be given to the project submissions that secure the highest, the second highest and the third highest value of averageMCC on the blind test dataset. In case of a tie the winner will be decided based on the higher value of the accuracy on the blind test dataset.

IMPORTANT NOTE 4: For item 4, MCCs that are high(er) relative to other submissions or to the baseline in

Table 1 are not necessary to receive a full mark. The key is to show substantial progress from the initial solution – you should show and discuss how your best design is better when compared to your own alternative solutions and explain advantages compared to the baseline results in Table 1.

Deadlines and Delivery

Final Notes

 While we recommend the use of RapidMiner, you can complete this project using any other data science software or language. Just make sure that you will be ready to make predictions on the blind test dataset using your selected software.

 Always copy the email communications to yourself so you can prove that it was sent.

Peer Evaluation Form for the In-class Project Presentations

Name of the presenting group ………………………….……………………………………………

Remarks:

• For each question enter grade between 0 and 20 or between 0 and 10 (0 being the worst, 30 or 10 being the best) • Optionally please add comments (both positive and negative); they will be passed along to the presenting group.

• Average of these grades submitted for a given group will constitute the peer evaluation component for the project presentation.

remarks grade

Quality of Presentation

Did you find the presentation interesting? Were the presenters prepared? Did you understand the topics covered in the presentation? How much did you learn? Was there anything significant missing? Were the conclusions and discussion of results covered sufficiently? How would you rate handling the discussion/questions? min 0, max 20

……

Presentation Style

Quality of presentation style – Was it finished on time? Too fast/slow? Well presented? Was the presenter just reading the slides or was (s)he presenting the material beyond the content of the slides? Was there an eye contact? min 0, max 10

……

Quality of Slides

Quality of slides – Did you find the slides too crowded? Too brief? Too many? Easy to read? Was the layout of individual slides appropriate and consistent? How was the overall quality of the organization, in terms of the order and flow of the slides? min 0, max 10

……

Additional

Comments

Name of the presenting group ………………………….………………………………………

TASK grade max grade

Quality of Motivation for the proposed design

5

Quality of the Description of the proposed design 5

Quality of the Discussion and comparison of the quality

5

Quality of Conclusions

10

Quality of the Presentation and Presentation Style

5

Name of the presenting group ………………………….………………………………………

TASK comments grade max grade

Presentation finished within 8 minutes limit (up to -10 points penalty) Y / 0

Quality of Motivation for the proposed design

5

Quality of the Description of the proposed design 5

Quality of the Discussion and comparison of the quality

5

Quality of Conclusions

10

Quality of the Presentation and Presentation Style

5
