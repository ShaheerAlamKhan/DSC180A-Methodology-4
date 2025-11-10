# Shaheer Khan

**Email:** shk021@ucsd.edu

## Section & Mentor
**Section:** B14 - Comparing Maps from Human Brain Imaging

**Mentor:** Professor Armin Schwartzman

**TA:** Gabriel Reigner

-----------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------

## Quarter 2 Project Reflection

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic has been the exploration of how EEG signals differ between actual physical movements and imagined movements. Being able to understanding the distinct neural activation patterns in the motor cortex during these two conditions, has been incredibly engaging. The practical challenge of classifying these subtle signal differences using machine learning makes this both technically challenging and rewarding.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to investigate optimal feature extraction and classification methods specifically for distinguishing actual versus imagined movements in EEG data. This would involve comparing different preprocessing pipelines, exploring which frequency bands (alpha, beta, mu) are most distinct between the two conditions, and testing various classification algorithms to achieve the highest accuracy. Additionally, I'd examine whether certain types of movements produce more distinguishable patterns than others.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

I'd want to add more statistical testing to back up what we're seeing in the visualizations. Right now we have the preprocessing pipeline working and can compare the EDA outputs between actual and imagined movements, but I haven't really quantified whether the differences we're seeing are actually significant or just random variation. I'd also like to try different epoch lengths and baseline correction methods to see if that makes the differences between conditions more obvious. Some of our comparison plots look promising but others are kind of ambiguous, so playing around with those parameters during preprocessing might give us cleaner data to work with when we eventually build the classifier.

**4. What other techniques would you be interested in using in your project?**

I'd really like to try out EEGNet or some of the simpler CNN architectures that are built specifically for brain data. The idea that they can just learn what matters in the signals without me having to manually pick features is pretty cool. I'm also curious about combining different classifiers together to see if that improves accuracy, since I've seen papers where ensemble approaches work well for noisy EEG data. One big challenge I've noticed is that EEG patterns vary a lot between people, so I want to look into ways to adapt models for individual subjects rather than just training one model for everyone. And I need to be more careful about cross-validation, can't just randomly split the data when dealing with time-series brain signals, so I want to figure out the right way to validate without cheating.
