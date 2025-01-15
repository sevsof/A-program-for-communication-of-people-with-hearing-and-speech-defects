# A-program-for-communication-of-people-with-hearing-and-speech-defects
Training a neural network to recognise gestures used for communication between hearing and speech impaired people.

Gesture language is the language used by deaf and hard of hearing people. Each gesture is produced by the hands in combination with facial expressions, lip shape and movement, and body body posture. It has its own grammar and vocabulary. It also has its own gesture alphabet (dactyl alphabet) .

Dactyl is a gesture alphabet in which each letter corresponds to a certain gesture. The gesture itself is performed with one hand using fingers. This alphabet is mainly used at the initial stage of language acquisition. So children can express their thoughts, which can not yet say full-fledged words. Also, some words can be said only in dactyl. For example, people can say their name only with the help of sign alphabet. Therefore, dactylology is the basis in the study of sign language

Classification task - a task in which there is a set of objects (situations) divided into classes in some way. There is a finite set of objects for which it is known to which classes they belong.

It is required to build an algorithm capable of classifying an arbitrary object from the initial set.

Two sets are given: objects and the classes they belong to. Elements of the set of objects are photos of each letter gesture. The following attributes are used to describe them:

- The white colour content of each pixel.

- The number of pixels.

More complex features are extracted automatically using convolutional layers of the neural network. The set of classes is the name of the letters of the alphabet.

We need to build an algorithm that maps the pictures of a gesture to the name of the letter it shows.

Computer vision is an area of artificial intelligence related to image and video analysis. Like other types of AI, computer vision is used to try to automate intellectual tasks normally performed by humans. In this case, it is the ability to recognise objects from a photo or video.

Neural networks are a type of machine learning that has so far good results in a wide variety of human knowledge areas like speech recognition, text and image analysis

Some letters in the dactyl alphabet need to be shown in motion, so a separate code presents an example of working with these particular letters.

Training a neural network requires a large amount of data for good trainability. After analysing the sources of information a data set was found which contains 20 different photos of each gesture in Russian, but this amount was not enough, as the network was poorly trained and the accuracy was low. So an approbation group of friends and family members was created to take a few more photos of each letter. They had the goal of taking photos under good light, without decorations and on a clean background so that the network could detect gestures under all conditions. Attached below are examples of the photos that turned out.

Also, after watching an instructional video on sign language, specifically dactylology, it became necessary to add some more screenshots.

About 90 photos were taken for each gesture.

Also about 80 videos for the missing gestures.

Thus, the program reads the image of the gesture from the camera, the neural network recognises it and outputs the correct letter (in 83% of cases according to the test data). All tasks have been completed, creation of a programme for gesture recognition using artificial neural networks with acceptable accuracy is possible.

At this link you can check the work of the programme and show the gestures yourself.

https://drive.google.com/drive/folders/1_kZ5GxUM9BBSZrBXeseE7sz2ajLX5P_z?usp=sharing
