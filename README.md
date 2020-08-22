# Motivation

The year 2020 came with changes all around the globe, imposing new standards when it comes to protecting everybody around you, not only your beloved ones. In this time of need, one of the most harmed and overloaded institutions is the hospital, which is the first line of fighting the pandemic, but also a mandatory place for some of us. People that have chronic, autoimmune or degenerative diseases or just a simple headache have to stay in touch with their doctors to check themselves and to keep their mental health in a good shape.

Q&AId tries to solve this problem by helping the hospitals and the patients as well by:
providing the user answers to questions on clinic data.
providing the hospital with a transcript of what the patient needs, reducing the waiting time and unloading the hospital triage.

<insert here cute cool example from the app>

Q&AId is conversation agent that relies on a few machine learning models to filter, label and answer medical questions, all based on a provided image as described below. The transcript is then forwarded to the closest hospitals and the user will be contacted by a nearby hospital to make an appointment.

<insert app diagram here>

Each hospital nearby has their models trained on their data that finetunes a visual question answering model (VQA) and other models, based on what data they have (an example being the brain anomaly segmentation). We are aggregating all the tasks that these hospitals can do into a single app chat, the user getting aggregated results and features from all the nearby hospitals. When the chat ends, the transcript is forwarded to each hospital, a doctor being in charge of the final decision.
