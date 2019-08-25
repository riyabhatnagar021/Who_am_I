# Who_am_I

<b> Objective </b>

The model is able to recognize the face of a registered person from webcam.

<b> Description </b>

This works on the <b>One Shot Learning Algorithm</b> that is training on only one example.
Here we have used VGG-Face model which has 22 layers and 37 deep units.

The model consist of two categories:

<b>Face Verification -</b> "is this the claimed person?". For example, at some airports, you can pass through customs by letting a system scan your passport and then verifying that you (the person carrying the passport) are the correct person. A mobile phone that unlocks using your face is also using face verification. This is a 1:1 matching problem.


<b>Face Recognition - </b>"who is this person?".A face recognition system that takes as input an image, and figures out if it is one of the authorized persons (and if so, who). Unlike the previous face verification system, we will no longer get a person's name as another input.



<b>Result</b>

This model recognizes and verifies faces by using Face Verification and Face Recognition approaches sucessfully.
