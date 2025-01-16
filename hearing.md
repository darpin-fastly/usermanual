# My Hearing

*tl;dr I have trouble hearing. I might ask you to repeat things...a lot.
I will get it. Bear with me. Help me out.*

Note: There is a lot to parse/understand here. Thank you for your interest.

I have moderate to severe hearing loss in both ears in the upper half of
human speech frequencies. Some people's voices I can hear perfectly at virtually
any volume; other's, I struggle with at any volume.

In more social situations I will wear my hearing aids, however, amplification
does not always help. Even with the AI component of modern hearing aids, the
amount of
amplification I need (~60dB for some frequency ranges) means that a lot of
the sounds of life can and do get in the way (HVAC, I'm looking in your
direction).

To compound the struggle, there is a thing called Auditory Processing Disorder
(APD). See
[Auditory processing disorder (APD)](https://www.mayoclinic.org/diseases-conditions/auditory-processing-disorder/symptoms-causes/syc-20555261).

It is difficult getting an audiologist to even talk about APD because they are
selling amplification as the treatment and always want to 'try that first'.
ENTs seem to just want an MRI to maybe diagnose something. There isn't
really a treatment plan that medicine can prescribe per se for APD.

In short, APD is the brain's attempt to figure out (i.e., guess) what something
it hears is when that stream of sounds don't fully and immediately matched
as a particular word or phrase.

In general, like with dyslexia, the 'sufferer' must train themself to
deal with the missed parts by putting forth extra effort (which ends up
many times being intently staring at the person speaking) or often asking
the speaker to repeat themself in hopes that the brain gets it the second...or
third time.

Keep in mind that with APD, and to some extent with simple amplification,
it is a single word or cluster of words or snippet of sounds that are missed
or misinterpreted.

Mapping this to a machine learning example, consider a neural
network (or set of neural networks) for matching words. In a stream of
sound snippets, two of the neural networks return the exact same weighting (I
mean an
unambiguous matching of the exact same value)
for a particular snippet. The orchestrator of those neural networks must
decide which to choose of the two exact matches. Sometimes the orchestrator
makes the proper selection. Sometimes it doesn't.

Asking for the stream of snippets again, causes the speaker to either
change the wording to something without the exact matches, or to better
differentiate the snippet in some way which causes the neural networks
to calculate different weightings. You'll see this in lots of captioning
software, which shows the first guess, then with further processing changes to,
hopefully, a more accurate guess.

Unfortunately, human brains don't have the wiring to do a first pass followed by
a second pass.

So, why does all this matter!? Being able to work remotely has been
a godsend for people suffering from APD and hearing loss in general.
When I am in my office at home, I control the ambient noise, I control
the level of amplification I need, I control the level and application
of closed captioning / live transcription that I need.

As such, I will always opt for attending big meetings using over-the-ear
headphones either from my home office, from a conference room, or my assigned
desk, and will
almost always have any additional amplification capabilities I need.

The short of it is: if you wonder why I'm missing from onsite meetings
(e.g., kickoffs, all-hands, and such) in the common area, it is because I'm

I'm not being anti-social. This is what I need to be able to be fully
engaged in such conversations.

## Other notes/thoughts

In my experiences, over the last 10-or-so years, dealing with hearing loss
is that there are three types of communicators who will communicate:

1. by slowing down, enunciating better, and helping repeat things
2. having no idea that someone could need help
3. expecting the listener to listen harder, or otherwise do something
   themself, if they have trouble hearing

## Available Technology

* Both Windows and mac have Live Captions built in.
* Google Chrome has captioning capabilities for web pages.
* Linux has a captioning tool called
  [LiveCaption](https://github.com/abb128/LiveCaptions)
  available through Flathub.
* Android phones have the LiveTranscribe app in the app store which is good for
  on-the-go captioning.
* [HearView](https://www.hearview.ai/) glasses are also a really expensive 
  option which I may consider more seriously now that I'm sometimes back 
  in the office.
