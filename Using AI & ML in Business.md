**Overview**

***An approach that realizes business value starts with the problem:***
1. Business problem:
    Definitions, value, stakeholders, priority, investment
2. Data:
    Availability, provenance, security, coverage, cleaning, augmentation, annotation, refreshing, pipeline development
3. Model building:
    Feature extraction, hyperparameters, tuning, selection, benchmarking
4. Deploy & measure:
    Business value measurement, AB testing, versioning, business process integration
5. Active learning & tuning:
    Bias mitigation, ground truth & success monitoring, version control

Tip: Start small and narrow and expand thereafter once you find the business value

***Business needs:***
 - Production systems actively learn from humans: active learning in this case, means a model can learn from data that is labeled by human annotators and experts
 - When a model does not know the answer to a specific query or how it might respond to a certain input, more data should be gathered from human annotators and the model should be re-trained to increase its knowledge base and increase the confidence of the model

 ***Business case:***
 How to determine if a problem is a good problem for machine learning?
 - Identify the AI value:
    What is the specific activity that needs to be accomplished?
    How would a human execute that activity?
    How would AI execute that activity?
    What incremental value would AI create?
- Create a project statement:
    What problem are we solving?
    How does AI add value?
    What data are needed?
    What is the scope? When will the AI product be used?
    How do we measure success?

Summary:
- Deploy for targeted use cases: to realize business value, AI technologies must be deployed to deliver specific, measurable business outcomes for targeted use cases (source: Gartner)
- Start with the business problem before data: it's rarely a good idea to start with a decision to clean up data. It's almost always better to start with a business case and then evaluate options for how to achieve success in that special case (source: PwC)
- Success depends on the data: our AI systems are only as good as the data we put into them (source: IBM THINK)

***Metrics:***
- What makes a metric effective?
    Easily measurable
    Directly correlated to business performance
    Predictive of future business outcomes
    Isolated to factors controlled by the group its measuring
    Comparable to competitors' metrics

***Do you need AI?***
- Key considerations:
    Do you have an impactful business problem that warrants solving?
    Can you quantify the business value clearly and simply?
    Does the problem have a large volume of associated data?

- The data:
    How much data do you have?
    Does the dataset match the problem?
    Is the dataset complete?
    Is the data annotated correctly for the ML team?

- Need for deep learning vs. traditional ML?
    Deep learning outperforms with large datasets; ML works better with smaller datasets
    Deep learning techniques will require more powerful infrastructure
    Deep learning is about learning features rather than manually engineering them
    Deep learning shines when applied to complex / multidimensional problems (e.g., image classification, natural language processing, speech recognition)

***Things to remember:***
- Start with the business value: break it down into a small and specific component of the process that you want to improve  
- Get real with the data: use production data to ensure that the training data match the reality of the real-world deployment
- Learning is key to value: learning from new data ensures constant improvement

***Typical team structure:***
- Product: Product, Design
- Engineering: Engineer, DevOps, QA
- Machine Learning: Data engineering, Data science

***Key roles:***
- Product owner:
    Business case owner
    Bridge from stakeholders to team
    Owns maximization of product value
    Ensures that the team builds the right product
- Designer:
    Owns human-computer interaction design
    Visual design, information architecture, interaction design
    Usability / accessibility
- Software engineer:
    Builds product infrastructure
    Problem solving in software development
    Frontend / backend
- Data engineer:
    Builds the data infrastructure
    Gets model into production
    Ensures entire pipeline can support rapid development and iteration after launch
    Model management / AB testing / validation
- Data scientist:
    Builds & selects the Model
    Guides the team on the state-of-the-art technology
    Structures the problem to achieve the business metrics
    Uses data to answer business questions
- Quality Assurance:
    Owns the quality assurance of the product
    Ensures product release is ready
    Scalability testing
    Functional testing
- Development & Operations (DevOps):
    Ensures infrastructure reliability
    Manages scalability and performance
    Mitigates security risks
    Ensures development and ML team can work efficiently

***Project management:***
- Scrum: framework for prototyping and improving on product ideas

***Summary:***
- Start with the business problem
- Make sure you have the right data
- Build an interdisciplinary team
- Learn and iterate.... fast
