# GermanWords-FM
FileMaker app for learning German Words

![callouts 0](https://user-images.githubusercontent.com/35608297/223508692-4f8c5c73-3d6c-4cbf-baa7-bdf7ff3c4edb.jpg)

## **Reason for this repo**

Offered as an example of my FileMaker UI skills. Most of my professional projects have been covered by NDA agreements. This simple app was developed for my own personal use so it's free of restrictions.

## **FileMaker for the uninitiated**

This app was built using FileMaker Pro Advanced v18. A wholly-owned subsidiary of Apple, FileMaker software recently had a name change to Claris. That paid software has similarities to no-code/low-code and client-server architectures. This demonstration app is meant to be saved to an iPhone and run on the FileMaker Go iPhone app. However it will also run on a FileMaker desktop client.

## **This app Features**

Effort has been made to streamline the data entry and search features. The idea is to make it easy to use while traveling. An internet connection is not necessary for basic features.

### Search for existing words

![callouts 1](https://user-images.githubusercontent.com/35608297/223508840-7de407b3-0c2e-42c4-8cad-73cf0d8ca3a5.jpg)

- partial word, words beginning with, or specific word searches possible
- search may be limited to English or German words only

After entering the search character string, the user may tap on the refresh icon in upper left, or anywhere in the empty list, to do a search.

![callouts 2](https://user-images.githubusercontent.com/35608297/223508909-b4820ced-10d8-47a0-aad8-b62ec1178ed7.jpg)

If more than one word is found that matches the search characters, the user is left looking at the list of found words. From there they may tap a word to see its details

If only one word is found, then the user is left in that word's detail view.

![callouts 3b](https://user-images.githubusercontent.com/35608297/223509930-1cd8d575-abb6-432e-9e2e-4cb8272b4090.jpg)

### New word entry

When new word record is created, the word is immediately copied to the clipboard. Then the user may open the Universal Dictionary (aka: Dict Box) iPhone app. That app assumes the clipboard word needs to be translated so it immediately does so. The user may then copy the translation.

Going back to the FileMaker app the user finds the cursor already in the English translation field. Instead of just pasting in the copied translation the user may instead enter shortcuts to speed data entry...
| key | meaning |
| --- | --- |
| d | German word is a noun |
| dd | word is a noun with more than one meaning |
| z | word is a verb |
| zz | word is a verb with more than one meaning |
| n | word is most anything else (adjective, adverb, etc) |
| nn | word is most anything else with more than one meaning |
| s | like n but also is a sentence |
| c | like n but also is a colocative (more than one word commonly found together) |

When exiting the English translation field

- the word type is automatically entered
- for verbs: "to " prefixes the pasted text
- for words with more than one meaning: "1) " prefixes the pasted text
- for s or c: the appropriate checkmark is set at the bottom of the screen
- the user is left in a different screen appropriate to the word type

### Buttons

Buttons on the right copy the German word and open translation web sites using it. (For this obviously an internet connection is needed.) These buttons help confirm the first translation and provide access to verb conjugations.

Common font styling may also be carried out using buttons on the lower right.

### Jump to other words

To reference other entries, a German word can be highlighted, then the blue arrow in the lower left tapped. If the word had already been entered, the user is left viewing that word.

If that word had not yet been entered the user is given the option to create it now. In doing so, the starting word is also automatically entered as a "compare to" in the explanation field.)

## Learning page

![callouts 4](https://user-images.githubusercontent.com/35608297/223509089-a82edb5b-52c1-47aa-877a-0acb12d216f2.jpg)

### Daily activity log

Lists words that are displayed in detail view or entered as new (highlighted in green). The last word of previous session is highlighted in grey

### Misc learning tips

- helpful conjugation tables
- total count of words (my count 8,112 as of 3/4/23)
