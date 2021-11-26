# Textual Variations Affect Human Judgements of Sentiment Values

## Citation

This repository contains the collected comments and their manual analyses which are released as part of the following paper.

Phoey Lee Teh, Paul Rayson, Irina Pak, Scott Piao, Jessica Sze Yin Ho, Andrew Moore and Yu-N Cheah (under review) Textual Variations Affect Human Judgements of Sentiment Values. Electronic Commerce Research and Applications.
	

## Licence

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## Collected Comments

Phase 1 of our study involved the collection of comments on commercial items from social media websites. A total of 1,041 comments containing 105,437 words from 10 different product categories were collected from a variety of social media platforms, including Amazon, Facebook, E-bay and GSM Arena. To ensure a wide comment coverage, the 10 product categories were selected from the main categories displayed on the Yahoo! homepage (at the time of data collection), namely "Mobiles and Tablets", "Fashion", "Jewellery and Watches", "Cameras", "Home Appliances", "Consumer Electronics", "Computers", "Beauty and Health", "Toys and Kids" and "Sporting Goods". This data is available in `OriginalData.xlsx` and the comments only are extracted in `Comments.txt`. A Wmatrix frequency list for the comments appears in `CommentsFreq.txt`.

## Manually assigned sentiment values

Sentiment values were assigned manually by 500 university students for a range of different textual variants, and the results appear in `SentimentValues.xls`. In this spreadsheet, the columns A to G represent the following items, corresponding to part one in the sample questionnaire, with codes for each column shown in a sub-list: 

* A: English
  * 1: Yes
  * 2: No
* B: Age
  * 1: 18 and below
  * 2: 19-35
  * 3: 36-50
  * 4: 51 and above
* C: Gender
  * 1: Male
  * 2: Female
* D: DoYouComment
  * 1: Yes
  * 2: No
* E: WhichSocialMedia
  * 1: Facebook.com
  * 2: Amazon.com
  * 3: eBay.com
  * 4: Twitter.com
  * 5: Other
* F: WhatIsYourPurpose
  * 1: Sharing experience
  * 2: Giving warning to others
  * 3: Giving suggestion
  * 4: Expressing yourself
  * 5: Sharing experience
  * 6: Other
* G: WhatIsTheCategory
  * 1: Mobile and Tablets
  * 2: Fashion
  * 3: Jewellery and Watch
  * 4: Camera
  * 5: Home Appliance
  * 6: Consumer Electronics
  * 7: Computer
  * 8: Beauty and Health
  * 9: Toys and Kids
 
The coding system indicated by the numbers above is also shown in `AtoGcoding.docx`.
 
Further columns in the spreadsheet are labelled Q1 to Q30 (corresponding to questions such as in the sample questionnaire), and for each question there are eight columns with additional labels a-h:

* a: plain text version (e.g. I love it)
* b: A whole phrase in capital letters (e.g. I LOVE IT).
* c: A phrase that ends with two exclamation marks (e.g. I love it!!).
* d: A phrase that ends with four exclamation marks (e.g. I love it!!!!).
* e: A phrase with specific word(s) in capital letters (e.g. I LOVE it).
* f: A phrase with repeated letters (e.g. I looooooove it).
* g: A phrase with a positive emoticon (e.g. I love it :-)).
* h: A phrase with a negative emoticon (e.g. I love it :-(). 

For each of these columns Q1a to Q30h, the cell values represent the following levels:

 1. Strongly Dislike
 2. Dislike
 3. Slightly Dislike
 4. Neutral
 5. Slightly Like
 6. Like
 7. Strongly Like
 
## Sample Questionnaire

A sample questionnaire is available named `SampleQuestionnaire.docx` which was provided to the participants.


## Ethical Approval

This research project has received approval from the Sunway University Research Ethics Committee (Approval code: SUREC 2015/002). If you have any concerns about this project you can contact the Research and Enterprise Office, Sunway University, Tel: +6 03 7491 8622. 

## Updates

A snapshot of this data as released with the paper is available via a Lancaster University DOI.
This set of data is also available on the UCREL GitHub, where any future updates will be  made:

https://github.com/UCREL/HumanJudgementsOfSentimentValues

