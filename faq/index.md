---
layout: alt-page2
title: F.A.Q.
excerpt:
---

1. [How to Use LinkedIn Export Tool to extract your connections](#question1)

2. [LinkedIn bans me. Can't get access to LinkedIn site. What should I do?](#question2)

3. [Why some fields are empty in the output file?](#question3)

4. [XML does not open properly on MAC. How to export contacts to CSV?](#question4)

5. [How to inform about troubles?](#question5)

6. [Does the tool send or store my information somewhere?](#question6)

<hr><a name="question1"/>

#####How to Use LinkedIn Export Tool to extract your connections:

* Install the extension from [Google Chrome Webstore](https://chrome.google.com/webstore/detail/linkedin-export-tool/kgipmhdegifoehfbbffcfbmpfmbjaiem)
* Open Linkedin in Chrome
* Click on “Connections” tab 
* Select connections you would like to export (_if tick off  “select all” connections, please scroll down until the end of the page to make sure all your connections have been downloaded_)
* Click on extension icon (in the right side of chrome address bar) and start the export
* When the download is completed open xml or csv file in Excel

<hr><a name="question2"/>

#####LinkedIn bans me. Can't get access to LinkedIn site. What should I do?

Due to [LinkedIn limitations](https://developer.linkedin.com/documents/throttle-limits) you can't export more than 1.5K per day. The idea of limits is that you can't visit more than 1.5K pages per day. If you do so you will be banned by the end of a day (UTC 00:00). 

In order to extract information about contact export tool gets contact's page witch affect limitations. The best way to work with export tool extension and LinkedIn during the day is to change limits on LinkedIn Export Tool settings page (I suggest to set it ~1K and it is by default).

![Set Limits]({{ site.url }}/images/settings-limits.PNG)

You should find a balance between automatic export and manual work with LinkedIn.

<hr> <a name="question3"/>

#####Why some fields are empty in the output file?

LinkedIn has flexible privacy settings, some users don’t want to share sensitive information. The tool try to get maximum information about the contact, but due to the privacy settings some fields could be empty. 
If you see that user has this information and you can manually find it, please contact us and if it is possible switch on a debug mode on the extension settings page and send us a log file.

<hr><a name="question4"/>

#####XML does not open properly on MAC. How to export contacts to CSV?

In order to get a CSV file instead of XML, please, go to the extension option page (chrome://extensions/) and choose CSV file format. 

![Export Format]({{ site.url }}/images/settings-export-format.PNG)

<hr> <a name="question5"/>

#####How to inform about troubles and send logs?

If you run into any issue and whant to fix it, please, write an email with description and logs (if possible) to [me](mailto:li.exporttool@gmail.com).

To write logs you need to switch on debug mode under the extension option page (chrome://extensions/).

<hr> <a name="question6"/>

#####Does the tool send or store my information somewhere?

LinkedIn Export Tool does not store or use your personal information. Some information is stored in chrome local storage. Information about chrome storage you can find [here](https://developer.chrome.com/apps/storage).
