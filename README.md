Subjects and MRI protocol
-------------------------------------

Nineteen right-handed healthy adults (6 female, mean age 22.368, range 18-28 years of age) participated in this study on
the same 3 T MRI scanner (TrioTim, software version syngo MR B17, Siemens, London,Ontario,Canada) 
by acquiring: 
-	axial 3D T1-weighted images usign an MPRAGE sequence [echo time (TE) = 2.9 ms, inversion time = 900 ms, flip angle =
9°, slice thickness=1 mm, matrix size=256 x 240 x 384;
-	three runs of bold task fMRI images using a T2*-weighted echo-planar imaging (EPI) sequence (TR=2000 ms, TE=30 ms,
flip angle=45°, slice thickness=3 mm; FOV=240 mm×240 mm, matrix size 80×80; number of slices=36; interleaved slice
acquisition).

Task protocol
------------------------------------

Participants were required to encode and maintain a set of features from an array of compound stimuli, composed of a
pseudo-randomly selected numbers and fractals placed at random spatial positions within a 4 * 4 grid. Each trials began
with a pre-encoding cue directing participants to focus on features from one of these three stimulus domains (number,
fractal or spatial). Then, three, five or seven compound stimuli were presented within the 4 * 4 grid. After 10 seconds
of encoding, stimuli were removed, and participants were required to maintain the features from the cued domain for 10
seconds. Subsequently, participants were presented with a probe array where one each of the numbers, fractals and
locations had been shuffled. They were required to indicate within a 10s timeframe the location of the shuffled item
that was within the currently maintained domain. The trial terminated at the point in time when the participant
responded and the next trial began after a 10-second inter-trial-interval (ITI), during which a fixation cross was
displayed and they were instructed to rest. In the imaging analysis, this (ITI) provided the baseline for comparing all
other events, i.e., where no overt processing of the WM task was required.


Defacing
------------------------------------

spm_deface was used on all anatomical images to ensure de-identification of subjects.


