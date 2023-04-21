The first steps in the scientific study of music were made by Hermann von Helmholtz in the 19th century, detailed in his main work, *On the Sensations of Tone*.
# 1.1 Pitch and Frequency 

The waveform the vibration of a tuning fork tine creates can be called a **pure tone waveform**. A pure tone waveform is periodic in nature, the frequency of the wave is representative of the pitch of that particular waveform. The larger the amplitude of the waveform the louder the sound is perceived.

## 1.1.1 Instrumental Tones

There are many different types of musical instruments such as voices, violins, pianos, flutes, and so on. The sounds that these instruments create are much more complex than the ones produced by something like a tuning fork. For instruments, they can be combinations of several pure tone waveforms of different frequency and amplitudes. For both the flute and piano these combinations are made up of pure tone waveforms that have varying amplitude but frequencies that are positive integer multiples of 329Hz. These multiples are called the harmonics for the instrumental tones. The 329Hz in this case is called the fundamental frequency. The fundamental frequency is the basis but does not necessarily need to be the loudest/most dominant pure tone waveform.

Generalizing the concept of fundamental frequencies to make up a particular instrumental tone we get the form of:

$\nu_0, 2\nu_0, 3\nu_0, 4\nu_0, ...$

The smallest frequency being the **fundamental frequency**, $v_0$. the other frequencies are called **overtones**. All of the frequencies are called **harmonics**.

<sub>The physical explanation for why instrumental tones contain multiple harmonics is beyond the scope of this book. For more information see Chapter 3 of *Fourier Analysis*, by James S. Walker for stringed instruments. For other instruments see Music, Physics and Engineering, by Harry F. Olson.</sub>

## 1.1.2 Pure Tones Combining to Create an Instrumental Tone

[![Trumpet Instrumental Tone Decomposition](https://www.jameswalkermathmusic.net/mathematicsandmusic/Nav/EmbeddedYouTubeVideos/Chap1/TrumpetHarmonics.jpg)](https://www.youtube.com/watch?v=MTrxqihjH98)
<sub> Image hyperlinked to spectogram video with audio. </sub>

Now we can see how pure tone can be used to assemble an instrumental tone for a particular instrument given that you know the properties of the instrumental tones.

# 1.2 Overtones, Pitch Equivalence, and Musical Scales

Now we have seen that instrumental tones contain harmonics that are all multiples of a fundamental frequency. This fact is the basis for  an equivalence of two tones, when the frequency for one tone is twice the frequency of another tone.

For example if one tone has a fundamental frequency of 100Hz, and another has a frequency of 200Hz, their harmonics are as follows:

$$\nu_0 = 110Hz: 110, 220, 330, 440, 550, 660, 770, 880, 990, 1100, 1210, ...$$

$$\nu_0 = 220Hz: 220, 440, 660, 880, 1100, ...$$

All of the harmonics for the tone with fundamental 220Hz are contained in the harmonics for the tone with fundamental 110Hz. So while they are essentially equivalent, we will say the tone with $2\nu_0$ is **an octave higher in pitch** than the tone with $\nu_0$. 

The term octave comes from the use of 8 notes on the scales commonly used in western music. On such scales the eighth tone has double the fundamental frequency of the first tone.

## 1.2.1 Pitch Equivalence

When one tone is an octave higher in pitch, then the two tones will be nearly indistinguishable **when they are played concurrently**. They are **harmonically equivalent**. This harmonic equivalence is referred to in music theory as **octave equivalence**. 

Octave equivalence can be shown by playing two notes that are an octave apart, first separately, then together. When played together, because the first tone contains all the same harmonics as the second tone, the tones played together sound essentially identical to the first tone. 

[![Octave Eqivalence](https://cdn.discordapp.com/attachments/463193265416699915/1099093987547164712/image.png)](https://youtu.be/MnP1AUfhkKo)
<sub> Image hyperlinked to spectogram video with audio. </sub>

Like can be seen visually in the spectrogram above, the notes will only be easily distinguishable when played alone.

## 1.2.2 Musical Scales

There are many different kinds of musical scales used throughout the world. The harmonics of instrumental tones can be used to explain some of the features of the most commonly employed musical scales. 

We will go over two types of scales, the pentatonic scale which has 5 distinct notes, and the octave scale which has 8 notes.

Suppose we begin with a specific note, whose tone has a fundamental frequency of $\nu_0$. We shall refer to this note as C. The frequencies of the harmonics of C are 
$$\nu_0, 2\nu_0, 3\nu_0, 4\nu_0, ...$$
The 2nd harmonic, $2\nu_0$, is the fundamental for a tone that we have shown is octave-equivalent to the tone for C. Therefore, we shall also call this note C, and it will be the ending note of our scale. All subsequent notes on our scale will lie between these two C notes. and therefore will have fundamentals which lie between $\nu_0$ and $2\nu_0$.

The third harmonic, $3\nu_0$ is the fundamental for a higher pitched tone than the ending tone of our scale. If we divide $3\nu_0$ by 2, we obtain an octave equivalent pitch with fundamental $\frac{3}{2}\nu_0$. That frequency lies halfway between $\nu_0$ and $2\nu_0$ and we shall designate that note to be G.

When we play the note C and the note G, their harmonics will be either perfectly matched or well-separated, this is called **acoustic consonance**. When two distinct harmonies are not well-separated, then the sound waves from these harmonics will clash (interfere). This interference created a roughness in the sound, known as **acoustic dissonance**.

Continue on page 9 (26 on PDF)