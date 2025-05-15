# uig-keyboards

These are the files required to implement a chromeos uyghur language extension. In order to install, follow the following instructions:

1) Open Chrome and go to chrome://extensions

2) Toggle Developer Mode (top right)

3) Click "Load unpacked"

4) Select your folder (e.g., my-keyboard-extension/)

5) After it loads, your IME should appear as an available input method under chrome://settings/languages

Existing Uyghur keyboards overlay different Uyghur characters on top of each other, requiring the use of the shift button to access part of the alphabet. Although this system technically works, it makes the affected letters less accessible to users, which is especially significant because two of these letters, خ‎ and ئۆ‎, are quite important, with one of them being a vowel and the other being a commonly used consonant. We moved these letters to new positions on the keyboard, often replacing lesser used symbols such as \ or - with a letter, instead making them accessible via the shift key.

We kept لا in its usual place because it is a compound between two already represented letters, and can be created by typing in the two component letters. Thus, we felt that although there was no need to remove this character from the keyboard, it was unnecessary to move it to a more accessible spot.

Additionally, we moved ء to a new position below ئى. Although ء is barely used at all in Uyghur writing, it often comes in tandem with ئى when it appears, so we thought it made sense to associate these symbols on our new keyboard. Similarly, we addressed the usage of initial vowel characters, binding to two component characters together to prevent the computer from treating vowel characters as two separate letters.

We also moved ڭ to the side to make room for the vowel ئۆ, which we thought belonged spatially nearby the other vowel letters.

We hope that this new keyboard makes typing more accessible for Uyghur speakers.
