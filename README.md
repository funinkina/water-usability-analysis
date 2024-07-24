In this study, we present a machine learning-based approach to
predict the usability of water for the dairy industry based on its various
physicochemical parameters. The dairy industry requires water of specific
quality to ensure product safety and operational efficiency. We utilized a
dataset comprising parameters such as Turbidity (NTU), pH, Conductivity
(uS/cm), Total Dissolved Solids (mg/l), Total Hardness (mg/l as CaCO3),
Aluminium (mg/l), Chloride (mg/l), Total Iron (mg/l), Sodium (mg/l),
Sulphate (mg/l), Biochemical Oxygen Demand/Zinc (mg/l), Magnesium
(mg/l), Calcium (mg/l), Nitrate (mg/l), and Phosphate (mg/l). These
parameters were used to train a neural network model to predict water
usability, classified into three categories: not usable, conditionally usable,
and fully usable.  

The model was developed using a synthetic dataset, with
preprocessing steps including normalization and handling missing values.
Feature importance was assessed using machine learning techniques to
understand the significance of each parameter in determining water
quality for dairy applications. The trained model demonstrated high
accuracy and reliability in predicting water usability, offering a valuable
tool for the dairy industry to assess and manage water resources
efficiently.   

With the help of compiled model by tensorflow, we can use it to
determine the usage of the water on a scale of 0, 1 or 2. 0 meaning
competely unusable. 1 meaning only non important parameters are
unusable, and 2 means the water sample is perfectly usable.

----
The dataset is included in the repository as well as thorough description in the pdf.
