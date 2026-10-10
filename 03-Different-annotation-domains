1)Text

Learn:

Sentiment:--
Identify the emotion or opinion expressed in text.
Example text:
“I love this phone. It works perfectly!”
Label: Positive
Other labels: Negative, Neutral.

Intent classification:--
Identify what the user wants to do or achieve.
Example text:
“Can you help me reset my password?”
Label: Password Reset
Other labels: Complaint, Booking, Cancellation, Information Request.

Named Entity Recognition(NER):--
Identify and label names, places, organizations, dates, and other entities in text.
Example text:
“Rahul joined Google in Kolkata on Monday.”
Labels:
- Rahul → PERSON
- Google → ORGANIZATION
- Kolkata → LOCATION
- Monday → DATE

Toxicity/moderation:
Identify abusive, threatening, hateful, or otherwise policy-violating content.
Example text:
“I will hurt you if you come here.”
Label: Threatening Content
Other labels: Non-toxic, Insult, Hate Speech, Threat. Labels depend on the annotation guidelines.

Summarization evaluation:-
Evaluate whether a short summary accurately represents the original text.
Original:
“Heavy rain caused flooding in the city, and schools were closed.”
Summary:
“Flooding from heavy rain led to school closures.”
Label: Accurate Summary
Other labels: Inaccurate, Incomplete, Contains Unsupported Information.

LLM response evaluation:-
Assess the quality of an AI model's response.
User:
“What is 2 + 2?”
AI response:
“The answer is 4.”
Labels: Correct, Relevant, Clear
Other evaluation criteria: Helpfulness, Safety, Completeness, and Instruction Following

2) Image
Learn:
Classification
Bounding box
Polygon
Semantic segmentation
Instance segmentation
Keypoints
OCR
Image quality assessment

Example:
Image contains:

🚗 Car
🚶 Person
🚲 Bicycle

You may need to draw bounding boxes around each object.

3) Audio / Voice

Learn:
Transcription:-
conver voice to text 
Speaker identification
Who is speaking?
Assign an ID to each distinct voice you hear.
- One person reads all ten sentences → speaker_1 for all sentences.
- Two different people read the sentences → assign speaker_1 and speaker_2 as appropriate.
Speaker diarization:- 
When does each speaker start and stop speaking?
Speaker identification tells you who the speaker is. Diarization organizes the recording into time 
segments and associates each segment with a speaker ID.

Timestamping:- 
At what time does each sentence or word begin and end?

Emotion classification:-
What emotion is expressed through the voice?
angry, sad, happy, neutral

Noise classification:- 
What unwanted or background sounds can you hear?

Intent classification:-
What is the speaker trying to accomplish?
it is commonly used for conversational AI and virtual assistants. It is not necessarily required for speech-recognition datasets.

Spoken example	--- Possible intent
“Please open the door.”	---- request
“What time is it?”	--- ask_question
“Turn off the lights.”	-  command
“Thank you for your help.”	-  express_gratitude

Pronunciation/accent :- related labeling where the task requires it

Final annotation checklist for your audio:-
[ ] Verify the transcript against the audio
[ ] Assign consistent speaker IDs
[ ] Mark speaker turns and diarization segments
[ ] Add accurate sentence- or word-level timestamps
[ ] Label emotion only if required
[ ] Label audible background noise if required
[ ] Apply intent labels only if required
[ ] Review all labels against the task guidelines


4)  Video:Video annotation is the process of labeling objects, actions, people, and events 
in video footage so that AI models can understand what is happening over time.

Learn:
Object tracking
Action recognition:
https://chatgpt.com/c/6ac9e4dd-1650-83ee-9e48-709080c0ae26
Identifying an action performed in a video clip.
Example:
A person runs across a park.
Label: RUNNING
Other examples: Walking, Jumping, Clapping, Sitting.

Event detection
Frame-level labeling
Temporal segmentation
Object persistence
Human activity recognition

Example:
0–3 sec    Person enters room
3–7 sec    Person picks up bottle
7–10 sec   Person drinks water
