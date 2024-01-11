# Generative Modeling

A generative model includes the distribution of the data itself and tells you how likely a given example is. For example, models that predict the next word in a sequence are typically generative models (usually much simpler than GANs) because they can assign a probability to a sequence of words.

A discriminative model ignores whether a given instance is likely and just tells you how likely a label is to apply to the instance.

Informally:
Generative models can generate new data instances.
Discriminative models discriminate between different kinds of data instances.

A generative model could generate new photos of animals that look like real animals, while a discriminative model could tell a dog from a cat. GANs are just one kind of generative model.

More formally, given a set of data instances X and a set of labels Y:

Generative models capture the joint probability p(X, Y), or just p(X) if no labels exist.
Discriminative models capture the conditional probability p(Y | X).

# Application of Generative modeling for False Data Injection Attacks
![8](https://github.com/harshdhiman7/GenerativeModeling/assets/48979398/42a496be-aa2d-4d4b-bc86-fe6c8fc1b543)
