# AIRI_Kaggle_competition_Vision_Subtitles

OmniSub 2026
Visual Subtitles Challenge

**OmniSub 2026 – Visual Subtitles Challenge**


**Overview**
* The OmniSub 2026 Visual Subtitling Competition addresses the challenge of generating accurate subtitles for video content that lacks a usable audio track. This task is critical for improving accessibility for hearing-impaired audiences and for enabling subtitling in scenarios where audio is unavailable, corrupted, or unreliable.

* Participants are tasked with building a system that performs visual speech recognition (lip reading) from video data. The solution must detect a speaker's face, extract and stabilize the mouth region, and recognize spoken content under challenging conditions including head rotation, variable lighting, and partial occlusions.

**The Problem**
**Input:**
* A video clip (.mp4) of a person speaking. The evaluation uses visual information only — audio is not provided or considered during scoring.

**Output:**
A text transcription of the speech (English).

* You will train on the provided training split, which includes both video clips and their ground-truth transcripts. Your final submission must contain transcriptions for every clip in the test set.

**Evaluation metric**
* Submissions are evaluated with Word Error Rate (WER):

**WER** = (total word-level edit distance between your predictions and the reference) / (total number of reference words).
**Lower is better**. A score of 0.0 means a perfect match with the ground truth.
* Predictions are normalized (lowercasing, collapsing whitespace) before comparison. Rows are matched by the path column.

