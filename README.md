# ML_Linear_Algebra_Find_Similar_Clients

## Project description
The Sure Tomorrow insurance company wants to protect its clients' data. The
task is to develop a data transforming algorithm that would make it hard to
recover personal information from the transformed data. This is called data
masking, or data obfuscation. Additionally, the data should be protected in such a way that the
quality of machine learning models doesn't suffer. We will follow these steps to develop a new algorithm:
- construct a theoretical proof using properties of models and the given task,
- formulate an algorithm for this proof,
- check that the algorithm is working correctly when applied to real data.
We will use a simple method of data masking, based on an invertible matrix.

## Data description
- Features: insured person's gender, age, salary, and number of family
members.
- Target: number of insurance benefits received by the insured person over the
last five years.

## Project steps
1.Downloading and looking into the data.
2. Providing a theoretical proof based on the equation of linear regression. The
features are multiplied by an invertible matrix. Showing that the quality of the
model is the same for both sets of parameters: the original features and the
Linear Algebra. 
3. Features after multiplication. How are the weight vectors from MSE minimums
for these models related?
4. Stating an algorithm for data transformation to solve the task. Explaining why the
linear regression quality won't change based on the proof above.
5.Programing the algorithm using matrix operations. Making sure that the quality of
linear regression from sklearn is the same before and after transformation. Use
the R2 metric

