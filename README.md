### Continous-Implicit-Authentication-for-Smartphone-Applications

"Abstract — Due to the dramatic increase in popularity of smart-phones in the past decade, the need for sophisticated patterns that provide user authentication and security of sensitive information is growing. Towards this goal, a variety of biometrics has been applied in the past few years, such as user password, face recognition or fingerprint in order to access the device. In this work we propose a different approach. A continuous implicit authentication model that recognizes the authenticated user in real time, while using their device, through their swiping behavior. To meet this target, a one-class kNN-SVM confidence-based model was created and tested in a quite representative dataset which consists of 975 different users."

In the goal of creating this representative dataset, Papamichail et al. [8] developed “BrainRun” which, as we said before, is a commercially available application and consists of a number of games aiming at boosting cognitive skills of the users. More precisely, BrainRun consists of 5 different games (“Focus”, “Mathisis”, “Memoria”, “Reacton”, “Speedy”). Each game has a different set of rules and it is designed in a way that can provide us with a different set of user gestures such as horizontal swipes, vertical swipes, taps etc. In Table 1 we can see the statistics of the dataset created from the application “BrainRun”. Despite the fact that the dataset contains both taps and swipes of different users, in this work we only use the swipes of each user, both for simplicity reasons of the training procedure of the model and because the swiping behavior of a user gives us more information about the way they interface with their smartphone.

![photo](Screenshot_2.png)
