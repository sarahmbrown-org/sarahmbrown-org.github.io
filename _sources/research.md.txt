# Research 

I am making AI more fair by enabling it to use subjective human expertise. I do this by modeling bias in the world, understanding the behavior of fair machine learning interventions, and building tools that directly allow domain experts to interact with data and learning systems. Through collaborations with social scientists who study societal bias, I am able to develop better models that can aid in detection of biases in datasets and prevent machines from replicating those biases. To understand where different types of interventions succeed and fail, I analyzed the behavior of fair machine learning algorithms. Finally, I collaboratively build tools that enable incorporating expertise and subjective assessments of data in the modeling process.  Underlying all of these is a core technical approach of probabilistic model-based machine learning. I trained in developing probabilistic models for complex systems with multiple sources of uncertainty by collaborating with affective neuroscientists improving understanding of the spatio-temporal patterns of brain activity that create emotional experiences.


More active projects are on the [lab website](https://ml4sts.com/projects/)

## Past Projects

::::{grid} 3
:::{grid-item-card}  Detecting Simpson's Paradox

Simpson’s paradox is the phenomenon that a trend of an association
in the whole population reverses within the subpopulations
defined by a categorical variable. Detecting Simpson’s
paradox indicates surprising and interesting patterns of
the data set for the user. It is generally discussed in terms of
binary variables, but studies for the exploration of it for continuous
variables are relatively rare. This paper describes a
method to discover Simpson’s paradox for the trend of the
pair of continuous variables
:::



:::{grid-item-card}  Racial Profiling and Marijuana Reform"


In collaboration with economist Terry-Ann Craigie, I am studied the impact of marijuana reform on racial profiling as measured through traffic stops.


:::



:::{grid-item-card} A Sparse Combined Regression-Classification Formulation for Learning a Physiological



Current diagnostic methods for mental pathologies, including Post-Traumatic Stress Disorder (PTSD), involve a clinician-coded interview, which can be subjective. Heart rate and skin conductance, as well as other peripheral physiology measures, have previously shown utility in predicting binary diagnostic decisions. The binary decision problem is easier, but misses important information on the severity of the patient’s condition. This work utilizes a novel experimental set-up that exploits virtual reality videos and peripheral physiology for PTSD diagnosis. In pursuit of an automated physiology-based objective diagnostic method, we propose a learning formulation that integrates the description of the experimental data and expert knowledge on desirable properties of a physiological diagnostic score. From a list of desired criteria, we derive a new cost function that combines regression and classification while learning the salient features for predicting physiological score. The physiological score produced by Sparse Combined Regression-Classification (SCRC) is assessed with respect to three sets of criteria chosen to reflect design goals for an objective, physiological PTSD score: parsimony and context of selected features, diagnostic score validity, and learning generalizability. For these criteria, we demonstrate that Sparse Combined Regression-Classification performs better than more generic learning approaches.


:::



:::{grid-item-card} Machine Learning Analysis of Peripheral Physiology for Emotion Detection

Peripheral physiological signals have shown promise as a measure of a person's emotional state. There are many applications where a more quantitative evaluation of an individual's mental state would be beneficial. For example, in PTSD or depression diagnosis, a quantitative measure to assist and compliment the qualitative assessments conducted by clinicians could reduce the time involved in treatment planning. A better understanding of the underlying mechanism is necessary for building systems that use these signals to assist in critical decision making.

Previous work in emotion research has relied upon averaging in time and then applying standard significance tests and simple classifiers to analyze psychophysiological data. In this work, we extend analysis beyond traditional hypothesis testing and simple classifiers to better understand previous results and design an appropriate computational model. Under the hypothesis that modeling dynamics is important, we design and apply an Input-Output Hidden Markov Model (IOHMM). Through exploration of the learned IOHMM model parameters, we demonstrate the promise that more descriptive, generative machine learning models provide over the more task-specific discriminative models and traditional statistical hypothesis testing. Incorporating time provides an improvement over simple static classifiers in single trial (without averaging in time) prediction accuracy, but does not provide significant improvement over the time averaged results found in literature. To address this, we employ exploratory data analysis methods and examine properties of the algorithms applied to better understand the results and consider improvements. Mutual information computation and clustering provide insight as to the challenges in modeling this data. By applying concepts from learning theory, we show that these seemingly weaker results are actually consistent with previous results. We conclude with insights as to how an alternative approach could elicit more positive results out of this dataset and key theoretical contributions to machine learning that are of value for applying these techniques in scientific research.
:::

::::