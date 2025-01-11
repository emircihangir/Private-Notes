## What is it?

Private Notes is a simple web app that encrypts and stores any given text.

## How to use it?

If you're a first-time user, you are required to enter a password that will be used as the encryption key. After you submit a key, you gain access to a text field where you can write your private notes. After that, you hit the save button. There is no specific 'log out' button; you can just close the tab or refresh the page to do that.

If you already have some notes stored, you will see the encrypted version of your notes when you first open the app. You can copy that text and paste it wherever you want to back up your notes. You can import them later - though this feature is not available yet.

To decrypt your notes and be able to edit them, you need to enter a key and submit it. If the key is correct, your notes will be decrypted and the text field will change.

## How does it work?

Texts are encrypted via the Advanced Encryption Standard (AES), and stored using 'window.localstorage'. It only consists of one HTML file.
