# Gradient-Boosting-Acceleration

As Trevor Hastie correctly described it, Gradient Boosting is one of the best "Off-The-Shelf" algorithms in today’s world of Machine Learning. Indeed, XGBoost is a technique that garners great success in competitions taking place on Kaggle and other similar platforms. Ho-wever, it still remains a black box for a vast majority of its users. Gradient Boosting is a boosting technique, which consists in constructing a very accurate prediction rule by combining several relatively weak and imprecise rules. A surprisingly rich theory has developed around boosting, connecting to a broad range of topics including statistics, game theory, convex optimization, and information geometry. In this paper, we will try to explain how Gradient Boosting works, and how we can accelerate its training phase using Optimization techniques. In order to do that, we will start off by going over basic optimization definitions, followed by a presentation of different gradient descent techniques that will, hopefully, let us achieve great results. Next, we will present the theory behind the Classic Gradient Boosting algorithm, and talk about some of its variants. Finally, we will conclude our research on this matter by implementing our algorithms and testing their performances on a given dataset.
