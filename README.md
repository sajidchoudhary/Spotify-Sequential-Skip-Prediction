# Spotify Track Skip Prediction
The public part of the dataset consists of roughly 130 million listening sessions with associated user interactions on the Spotify service. In addition to the public part of the dataset, approximately 30 million listening sessions are used for the challenge leaderboard. For these leaderboard sessions the participant is provided all the user interaction features for the first half of the session, but only the track id’s for the second half. In total, users interacted with almost 4 million tracks during these sessions, and the dataset includes acoustic features and metadata for all of these tracks.


## Problem Statement:
The task is to predict whether individual tracks encountered in a listening session will be skipped by a particular user. In order to do this, complete information about the first half of a user’s listening session is provided, while the prediction is to be carried out on the second half. Participants have access to metadata, as well as acoustic descriptors, for all the tracks encountered in listening sessions.

The output of a prediction is a binary variable for each track in the second half of the session indicating if it was skipped or not, with a 1 indicating that the track skipped, and a 0 indicating that the track was not skipped.
