Fossil Fuel Share Prediction


What combination of state characteristics (political leaning, grid capacity, median income, existing energy mix, etc.) and renewable energy policy designs (Renewable Portfolio Standard targets, subsidy types, etc.) best predicts a successful change in fossil fuel shares per state in the U.S.?

Motivation:
As climate concerns grow, U.S. states are progressively adopting policies to lower their reliance on fossil fuels. However, the effectiveness of these policies vary considerably. Some states see quick adoption of renewables, while others grapple to make meaningful transitions. This inconsistency suggests that success is affected by more than policy alone — foundational state characteristics may play a key role.

Why This Question Matters:
The findings can guide policymakers and other interested parties in creating realistic, context-sensitive energy policies. By comprehending the conditions under which fossil fuel displacement is most successful, states can avoid one-size-fits-all strategies and take on tailored approaches.

Hypothesis:
States with supportive political climates (e.g., liberal leaning), high grid capacity, higher median incomes, and ambitious, well-designed renewable energy policies (e.g., binding Renewable Portfolio Standard with financial incentives) will be more successful in displacing fossil fuel energy sources.

Prediction:
A machine learning classifier or regression model will show that the above features are significantly and positively associated with a greater percentage-point reduction in fossil fuel energy share over the past decade, compared to other states.

Custom Function:
One custom function that was created was the build_preprocessor function in the Eval_Interpretation_Pipeline. It creates a preprocessing pipeline for machine learning models. It applies standard scaling to numeric features and one-hot encoding to categorical features (ignoring unknown categories). The function returns a ColumnTransformer that can be directly integrated into scikit-learn pipelines
