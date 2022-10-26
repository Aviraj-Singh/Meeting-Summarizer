# Meeting-Summarizer

## Problem Statement

Majority of leaders and executive of any organization spend more than 20 hours a week on meetings. Unless one joins, there is no atomated way to get a glimpse of Important Decisions Made. Also about 50% of the time spet on meeting in majority of the meeting is not measurable in any aspect.

## My Solution

Optimising meeting performance by providing a Meeting Summary of the recorded meeting. Thus, one can read summary whenever needed.

## Process Flow

1. Recording is converted to text using Wav2Vec2 model from Hugging Face
2. The text script is then filtered using spell corrector for better and corrected script
3. Different models like Seq2Seq, SBERT, etc. are applied on the text to generate summary
4. Performance of the models are compared and best one is chosen for production
