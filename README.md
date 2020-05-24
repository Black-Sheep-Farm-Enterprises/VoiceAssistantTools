# VoiceTech
This repository is a documentation area for matters relating to Voice recognition in assisting or improving productivity of users of computer software.

THIS DOCUMENT IS VERY MUCH WORK IN PROGRESS expect a high frequency of updates in the next weeks

Particular emphasis is placed on voice assistants in software development process.
This repository is broken into two areas,

1) General voice recognition
And 
2) Software Coding with voice.

This repository does not have specific software as an output although it may contain examples of code. It is more about the documentation of successful applications and technologies for the use o voice.

Where possible Technologies that are platform-agnostic are looked at But this authors predominant Desktop environment is Microsoft Windows 10 and  hence the bias. 

Voice control, especially in a coding environment, is very dependent on context as opposed to General dictation . In  the common applications of voice recognition one may provide simple responses to audio prompts  or one is dictating.  Both these two common applications have very  little control of the broader contexts a user is operating in. in voice dictation one is usually working in a single context such as a document where you are predominantly working in paragraphs. voice coding and voice control however we as users require constant switching between a multitude of  applications or even contacts within an application.  encoding we are debugging writing code writing documentation doing source control comma searching for help and the list goes on. 

Each operating system platform generally has its own speech recognition tools.  in windows Cortona and WSR (Windows Speech Recognition) Google Chrome  Voice Recognition in MacOS (tbd).  The functionality of WSR goes further than dictation and has various elements of control however they are not broad enough to cover a deep set of applications such as in software development. One will find oneself switching between a voice recognition application and another,
I particularly find this in terms of dictating speech into a document. a product called Dragon by Nuance has been and probably is still regarded as the de facto speech dictation application. It is also predominantly the most common front end to more General voice command systems. Importantly, Dragon is not supporting MACOS anymore !

I have decided not to invest in dragon as I have found that WSR and Google Chrome voice recognition are generally very powerful in some contexts. I  particular find Chrome voice recognition and speech tools in Google docs to have the highest quality of speech recognition.  A product called Lipsurf is an extension to Chrome  that facilitates a high quality browser navigation experience but unfortunately the use of Google speech recognition does not extend the function into an OS such as windows. 

My current broad dictation tool of choice is Voice typing in Google docs.  I then copy and paste this into other documentation.

For overall voice control and especially voice based coding I have looked at two products.  Caster and TalonVoice. both have been around for some period of time but it is the latest iteration ofTalonVoice (still in Beta)  that I find the most useful and cross-platform functionality. 
TalonVoice  has-been freely available for Linux and Mac OS and in this current beta program is being ported to Windows.  The author and community are extremely active in the Beta ,help and other Talon slack channels.  

While Caster and Talon both support Dragon they both also have alternate open source voice-recognition engines. The TalonVoice use of wav2letter  coming from Facebook in my experience and supported by tests performs as a a very fast highly accurate speech recognition engine 

.


