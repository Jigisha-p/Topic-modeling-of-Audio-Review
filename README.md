## Problem statement:

After the success of Tap Portable Bluetooth Speaker, Amazon is about to launch a new version in the market. To understand what features customers liked, Amazon did a focus group discussion with some selected customers - the audio in the discussions has been recorded.
The reviews that the panelists gave to Tap is what interests Amazon.

The task is to convert the given audio file to text, assess which features of the bluetooth speaker are being talked about in the audio reviews.  


Steps -

1. From speech_recognition module, import the sr utility. Instantiate the Recognizer class from the utility.
2. Load the given audio file "Recording2.wav" - this contains a sample audio for you to get comfortable with the module, use the 'AudioFile' method
3. With this as source, 'record' the audio from the file
4. Using 'recognize_google' method, convert the audio to text
5. Create a function to return the text for any given audio file (.wav format) as input.
6. Apply this function to the file 'Tap Review.wav' to extract the text from the audio review from the Amazon Tap focus group discsussions
7. Pre-process the text - tokenize into individual terms using NLTKs word_tokenize
8. Define feature_list as list of features of the product, containing the following terms -
 - "echo", "alexa", "music", "sound", "button","bluetooth", "voice", "battery", "dot", "phone"
9. Identify which of the features are being talked of in the audio review
