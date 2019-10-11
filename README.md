# Y3-IndividualProject
The aim of this project is to investigate existing natural sounding speech synthesis techniques and apply them to computer-synthesised singing. Computer generated speech is something that's made its way into commercial products already and yet applying the same principles to music has not been attempted yet. The goal of this project is to train a neural network using the millions of available audio tracks, extracting the vocals from them and generating sining using pre-defined lyrics.  

The main stages can be outlined as such - separating vocals from music tracks and synthesising voice from musical vocals.  

For the first part, there are many solutions available. Separation of vocals or instrumentals can be achieved through digital signal processing - applying filters to audio. In the music industry, this is achieved by using software programs such as Audacity and Adobe Audition. There has been some exploration in terms using AI for the task as well - websites such as Phonic Mind offer a service that lets you isolate either vocals or music from a song provided by the user. 

For the second part - an initial exploration of available APIs. The most prominent example of applying Deep Learning techniques to audio processing is Google Deepmind's WaveNet, which generates a very convincing text-to-speech audio. In this project, different approaches will be examined to determine what the best one is for the desired outcome - natural-sounding computer-synthesised singing.
