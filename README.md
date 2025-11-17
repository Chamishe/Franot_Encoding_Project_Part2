# READ_ME

In the context of the encoding project, I chose three manuscript deeds from the "Archives départementales des Ardennes" : A confirmation of the Mezieres' Charters from 1404, a sales contract from 1663 and a Charles IX letters patentes from 1540.

I selected these texts because I worked on them during an intership in this institution, which resulted in a memoir treating the impact of numerisation on the Ardennes' departemental archives seals. During my internship I added the seals in the french seals data base "SIGILLA" and in my memoir I discussed how the texts were overshadowed by the seals in the data base, even though they are essential for the comprehension of the seal. 

My objective with the encoding of these deeds are to highlight the informations we select in order to understand the seal (Who owned it, who sealed it, when etc...). To do so, I only selected limited parts of the texts : the "subscription" and the "corroboration". These parts are the only one to refer to the seal in any way and in order to still understand the full text, I wrote a short `<summary>` of the text in the `<TEIheader>`.
Next, concerning the transcription, I put effort in making the text as comprensible as possible for mainstream people. If seals are very comprehensible by themselves, the text is not as only a few people practice paleography. Transcription is supposed to ease their comprehension of the context in which the seal was sealed. That is why, when I did not find the right entity for the letter "v/u/b", I chose to keep the correct transcription of the letter in order to ease the comprehension. 
Finally, I created lists containing relevant informations to the comprehension of the creation's context of the text and seal with an `@id` in order to identify in the text where they were mentionned. especially as they were not always referenced with the exacts same terms. 

No gen AI was used in this assignment.
