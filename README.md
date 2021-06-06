# LIME

Application of Lime on the titanic dataset (https://www.kaggle.com/c/titanic)

Lime stand for Local Interpretable Model-agnostic Explanations. Here each word has its own meaning .Local as instead of explaining the prediction globally by building a global surrogate model, LIME focuses on training local surrogate models to explain individual predictions. Surrogate models are models trained to approximate the predictions of the underlying black box model. Interpretable as idea behind LIME is to make easy to interpretable local model such as linear regression which can explain your black box model locally .Model Agnostic Implies LIME can be applied to any black box model irrespective of the technique as long as it can predict probability . Explanations it implies that LIME will be able to explain how the model behaves, which features it picks up and what kinds of interactions between them take place to drive the predictions

for more details on lime you can refer my article ()

Lime github - https://github.com/marcotcr/lime

