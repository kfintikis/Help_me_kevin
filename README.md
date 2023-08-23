Task 3: Format the output of the application
Convert the response text into a dictionary using the json library functions.

Note the content formatting in this dictionary.

Extract the required set of emotions, including anger, disgust, fear, joy and sadness, along with their scores.

Write the code logic to find the dominant emotion, which is the emotion with the highest score.

Then, modify the emotion_predictor function to return the following output format.

1
2
3
4
5
6
7
8
{
'anger': anger_score,
'disgust': disgust_score,
'fear': fear_score,
'joy': joy_score,
'sadness': sadness_score,
'dominant_emotion': '<name of the dominant emotion>'
}
Copied!
Take a screenshot of the modified function code and save it as 3a_output_formatting.png.

Test the application in the python3.11 shell again, with the statement I am so happy I am doing this.

Verify that the response received has the dominant emotion is joy.

