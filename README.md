# Flushed Ray's ROTMG Chatbots

Simple Chatbots created using Pulover's Macro Creator
Download Pulover's Macro Creator [here](https://www.macrocreator.com/download/).

## Setup - Existing Text

To set up the bot with existing texts, download a .txt from this repo and place it in the root of your C: drive, so it can detect it.

1. Run Pulover's Macro Creator as administrator and open the matching .pmc file.

2. Press the white play button inside the blue circle.

3. Go into the instance of ROTMG that you plan on chatting from. Go to Settings>Controls>Social and bind Activate Chat to \ (backslash, |)
*if you want to paste into guild chat, bind "Begin Guild Chat" to \ instead*

5. Press the blue play button. This CANNOT BE STOPPED UNTIL IT IS COMPLETED without going into task manager, which is pretty difficult while it's spamming inputs.

## Setup - Custom Text

**To format text properly, all chat messages must have ``{enter}{enter}\`` between each message you want to send.**

### A. If you are formatting an existing text to work with the script that has line breaks (such as a novel, or the bible) do the following:

1. Confirm that no lines stretch past the character limit of 128 characters.

2. Go to https://onlinetexttools.com/replace-line-breaks-in-text

3. Paste the text you want to use in "Input Text" box.

4. Put ``{enter}{enter}\`` in the "Line Break Symbol" box.

5. Enable "Replace Consecutive Line Breaks"

6. Do steps in section C.

### B. If you are formatting text that DOES NOT have line breaks, or the line breaks are too sparse, do the following:
*note: this will not look very good and words will be chopped in half quite often.*

Go to https://phrasefix.com/tools/add-string-after-number-of-characters/
In the top box, paste your text.

1. Put ``{enter}{enter}\`` in the "Custom Append Text" box

2. Set "Append after this many characters" to 128

3. Turn on "Reset Counter After Line Break"

4. Do steps in section C.

### C. Running the custom text macro

1. Take the output and put it in a file named ``customtext.txt`` located in the root of your C: drive

2. Open PMC as administrator and open ``customtext.pmc``

3. Go into the instance of ROTMG that you plan on chatting from. Go to Settings>Controls>Social and bind Activate Chat to \ (backslash, |)
*if you want to paste into guild chat, bind "Begin Guild Chat" to \ instead*

4. Press the blue play button. This CANNOT BE STOPPED UNTIL IT IS COMPLETED without going into task manager, which is pretty difficult while it's spamming inputs.

# DO NOT DISTRIBUTE OR EDIT MY MACROS WITHOUT CREDITING ME PLEASE! YOU CAN EDIT THEM AND DO WHATEVER YOU WANT TO THEM, JUST CREDIT ME! 
