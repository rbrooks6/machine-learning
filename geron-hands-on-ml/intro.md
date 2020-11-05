## Why Use Machine Learning?
1. Useful for complicated rule algorithms that would be difficult to maintain such as a spam filter.
2. Useful for complex problems with no known algorithm such as speech recognition.
3. Useful for fluctuating environments.
4. Useful for discovering patterns that were not immediately apparent.

## Types of Machine Learning Supervision
1. Supervised: Training set includes desired solutions. Tasks to predict a target numeric value are regression tasks.
2. Unsupervised
    a. Clustering: can detect similar groups of data
    b. Anomaly/Novelty Detection: find outliers and odd-balls
    c. Visualization: create visuals of the data
    d. Dimensionality Reduction: simplify features by merging
    e. Association Rule Learning: discover interesting correlations between data attributes
3. Semisupervised: Google photos is an example of this. Uses clustering to group photos of people, and then uses your labels to label the people for searching.
4. Reinforcement learning: The learning system is called an agent and it observes an environment, performs tasks which reap negative and positive rewards, and develops policies for making future decisions. Robots often learn how to walk using reinforcement learning.

## Ways Algorithms Can Learn

### Batch Learning vs Online Learning
1. Batch learning: algorithm is trained offline with all of the data. Updates must be done by re-training with the new data added to the old data. This is time expensive and resource expensive.
2. Online learning: incremental learning by training on mini batches or individual pieces of data. This is faster and more flexible, but needs a set learning rate. high learning rate equals more likely to forget older data, low learning rate equals lower inertia.

### Instance-Based vs Model-Based
