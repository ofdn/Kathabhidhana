### Kathabhidhana consists of a few Free/Libre and Open Source Software, documentation to learn and use it, and open datasets that you can customize and shape your metadata.
------------
<a href="http://www.youtube.com/watch?feature=player_embedded&v=UGMxwPtqDJY
" target="_blank"><img src="http://img.youtube.com/vi/UGMxwPtqDJY/0.jpg" 
alt="Click to watch a quick video about this toolkit" width="240" height="180" border="10" /></a>
> _Almost half of the 6909 living languages of the world are dying in a century’s time. In India alone, over 220 Indian languages out of the total of 780 languages have died only in last 50 years. With these languages, there dies a wealth of knowledge forever_.

Kathabhidhana is an open toolkit to record a large number of words. It consists of a few free/libre and open source software, open datasets, methodologies and documentations. It can be used to record pronunciations of words to make a talking dictionary to record phonemes to create a text-to-speech software.

![alt tag](https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Workflow_of_Kathabhidhana.svg/900px-Workflow_of_Kathabhidhana.svg.png)

We truly believe in openness and the FLOSS philosophy. So every single component of this toolkit is open. It also contains other dependency FLOSS tools that are built by many kind people in the open source movement.

**A tool with many faces**
![alt tag](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7c/Home-studio_recording_setup_for_Kathabhidhana_%28wide%29.jpg/495px-Home-studio_recording_setup_for_Kathabhidhana_%28wide%29.jpg)
Wikipedia has a sister project called [Wiktionary](https://wiktionary.org), a multilingual dictionary where you can not just find meaning of words from your own language but also equivalent meanings of foreign language words. Unlike many available dictionaries that help learn proununciations, Wiktionary does not have pronunciations of all words in all the languages. Kathabhidhana was originally started by [Subhashish Panigrahi](http://meta.wikimedia.org/wiki/User:Psubhashish/) to add pronunciations to the Odia-language Wiktionary. It is adopted from a free [software](https://github.com/tshrinivasan/voice-recorder-for-tawictionary) created by by [Shrinivasan T](https://github.com/tshrinivasan). It works both on Linux and Mac. The [iOS version](https://github.com/OdiaWikimedia/Kathabhidhana/tree/master/Kathabhidhana%20for%20iOS) of Kathabhidhana was created by Prateek Pattanaik. You can certainly create pronunciations and add them to Wiktionary. But you can use Kathabhidhana beyond that by making a large library of pronunciations that can be used to build any machine learning or [Natural Language Processing](http://en.wikipedia.org/wiki/Natural_Language_Processing) (NLP) tool.

Currently several Odia-language words are being [recorded](https://commons.wikimedia.org/wiki/Category:Odia_pronunciation), uploaded on [Wikimedia Commons](https://commons.wikimedia.org), and are being used in [Odia Wiktionary](https://or.wiktionary.org). Feel free to use this toolkit [with attribution](https://github.com/OdiaWikimedia/Kathabhidhana/blob/master/README.md#attribution), and even forkand build something on the top of it. 

* [Tutorial to learn and use it](http://www.youtube.com/watch?v=zd4KNbNX4_Y) (in English)
* [Audio recording of words that were made using this tool](https://commons.wikimedia.org/wiki/Category:Audio_files_created_using_Kathabhidhana)
* An [ideal format needed for uploading multiple file](https://docs.google.com/spreadsheets/d/1Vh08Dd6V743Q58ceCnNLc9BASaZQMAsGu1BOaa_dMQQ/edit?usp=sharing)

<i>An Odia version of the resources and tutorial is available [here](https://or.wiktionary.org/s/ppq). We are currently working on building more tutorials so that you can learn more about bettering your home studio setup, tips and tricks about batch renaming files, cleaning up using open source tools like Audacity, setting up files for batch upload on Wikimedia Commons, etc. So stay tuned.</i>

## What Does this toolkit contain?
* A recording tool ([download for Linux/Mac and iOS](https://github.com/OdiaWikimedia/Kathabhidhana/archive/master.zip), [watch](https://www.youtube.com/watch?v=UGMxwPtqDJY) a video introduction to Kathabhidhana, [watch](https://www.youtube.com/watch?v=F-rmyZqKzrE&feature=youtu.be) a video tutorial for the iOS version)
* Instruction manual to set up the hardware and software
* Dependency tools
 * Audacity for a post-recording batch clean up ([Download](http://www.audacityteam.org/download/), you can also check this tutorial in [English](https://www.youtube.com/watch?v=BPiYzFcRFMY), and [Odia](https://www.youtube.com/watch?v=-xnTmHvGC2Y) to clean up vocals for individual recordings)
  * [Pattypan](https://github.com/yarl/pattypan) for batch uploading recorded and edited audio files on Wikimedia Commons
* Open dataset: [CSV](https://docs.google.com/spreadsheets/d/1Vh08Dd6V743Q58ceCnNLc9BASaZQMAsGu1BOaa_dMQQ/pub?output=csv), [.ods](https://docs.google.com/spreadsheets/d/1Vh08Dd6V743Q58ceCnNLc9BASaZQMAsGu1BOaa_dMQQ/pub?output=ods) for reference while creating meta data for your recordings
* [Odia→International Phonetic Alphabet (IPA)/Roman converter](https://or.wikipedia.org/s/14jk) for adding phonetic signs in the metadata while uploading. Thiis converter works only the Odia alphabet. But you can [fork](https://github.com/OdiaWikimedia/Converter#international-phonetic-alphabet-ipa-and-romanlatin-converter) and create one for your writing system too.

Prerequisites
--------------
<b>Using a computer?</b>
* Linux or macOS
* Linux running in a virtual machine

<b>Using an iOS device? ([check more here](https://github.com/pattaprateek/Kathabhidhana/tree/master/Kathabhidhana%20for%20iOS))</b>
* iOS (iPad or iPhone)
* An app called Workflow

How to use it?
--------------
1. Download and set up Kathabhidhana (see the [next section](#setting-up-kathabhidhana))
2. Set up your recording hardware (see mine in the [picture](https://commons.wikimedia.org/wiki/File:Home-studio_recording_setup_for_Kathabhidhana_(wide).jpg) above) e.g. microphone (if using an external one), computer settings like level
3. Record using Kathabhidhana
4. Batch processing using (tutorial coming soon, download Audacity from [here](http://www.audacityteam.org/download/))
5. Manual clean up of each file (tutorial coming up soon)
6. Setting up [Pattypan](https://github.com/yarl/pattypan/releases) and upload files on Commons (download from [here](https://github.com/yarl/pattypan/releases))

Setting up Kathabhidhana
--------------
(<i>you need to run the command in Linux or Mac, or Linux in a [virtual machine](https://en.wikipedia.org/wiki/Virtual_machine) if you're on Windows</i>)
[<i>Read in Odia</i>](https://goo.gl/hqXeG3)

1. Fill the words you want to record in a textfile named "file"
2. run the below command

First dive into the folder, for instance it is the "Kathabhidhana" folder under "Documents for me:
![alt tag](https://upload.wikimedia.org/wikipedia/commons/thumb/b/ba/Kathabhidhana_-_starting_the_tool.png/800px-Kathabhidhana_-_starting_the_tool.png)

Then run:
```
python voice-record.py
```

The next steps are quite self-explanatory. You need to choose "<code>Y</code>" for yes and "<code>N</code>" for no in the following options inside your terminal.

3. To upload all the ogg files to Wikimedia Commons
This will record the sounds in .ogg and .wav formats. You can then use a tool like [Pattypan](https://github.com/yarl/pattypan) to batch-upload either the .WAV or the .ogg files on Wikimedia Commons.

Findings so far
-----------
![time-taken- small](https://cloud.githubusercontent.com/assets/1258090/25761708/6ad2fd1a-31f9-11e7-8e67-8b68ee9485bc.gif) • It takes about **20-25 mins** to record **100 words**; A batch processing to convert and do overall auto-cleanup using Audacity will take about **5 mins** for a 100-word-batch; It takes an average of **30 secs** for **1 word** to manually clean up, check quality, trim extra portions and other such editing work (meaning it will take about **45 mins** to clean up a batch of 100 words) using Audacity; It takes about **5-10 mins** for setting up Pattypan to upload the cleaned up words on Wikimedia Commons; On an average one would spend roughly about **1.5 hrs** from recording to cleaning up to uploading for a batch of **100 words**


***Other useful resources***
* [Pronuncify by Asaf Bartov](https://github.com/abartov/pronuncify), a Kathabhidhana-like command line tool for both Linux/Mac and [Windows](https://github.com/abartov/pronuncify.net).
* [LinguaLibre](https://lingualibre.fr/), a web and GUI-based tool developed by the Wikimedia France for a similar workflow like Kathabhidhana with more functions

Attribution
-----------
* Project led by Subhashish Panigrahi and the [iOS tool](https://github.com/OdiaWikimedia/Kathabhidhana/tree/master/Kathabhidhana%20for%20iOS) is led by Prateek Pattanaik. All the media and text content are available under a [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license
* All the software component is licensed under [GNU General Public License (GPL) version 3](https://www.gnu.org/licenses/gpl.html) (read the [License](https://github.com/OdiaWikimedia/Kathabhidhana/blob/master/License.md) page for more details)
* This project and part of the documentation are based on the [Voice recorder for Tawiktionary](https://github.com/tshrinivasan/voice-recorder-for-tawictionary) project created by [Shrinivasan T](https://github.com/tshrinivasan) (please attribute Shrinivasan T if you're making a derivative of the software)

Blogs/media shoutouts
----------
* Panigrahi, Subhashish. "[A simple command-line tool for recording audio](https://opensource.com/article/17/5/simple-command-line-tool-recording-audio)". Opensource.com (May 12, 2017)
* Ojha, Bikash. Mishra, Chinmayee. Pattanaik, Prateek. Panigrahi, Subhashish. Patnaik, Sailesh. Elsharbaty, Samir. [Community digest: As Odia Wikisource turns two, a project to digitize rare books kicks off; news in brief](https://blog.wikimedia.org/2017/03/30/digest-odia-wikisource/). Wikimedia Blog (March 30, 2017)
* Rezwan. ["A New Audio Uploading Tool for Crowdsourced Wiktionary Project in Odia Language"](https://globalvoices.org/2017/02/12/a-new-audio-uploading-tool-for-crowdsourced-wiktionary-project-in-odia-language/). Global Voices (February 13, 2017)

Talks/workshops
--------
* [Workshop "Kathabhidhana: Recording words for Wiktionary and preparing for an AI assistant](https://wikimania2017.wikimedia.org/wiki/Submissions/Kathabhidhana:_Recording_words_for_Wiktionary_and_preparing_for_an_AI_assistant) (*selected for Wikimania 2017, Montreal, Canada. Please join if you are attending Wikimania this year. Check back in late August for more updates about the workshop.*")
