This repository contains some resources explaining how to break the Vigenere cipher using statistical methods and some simple SageMath code.
(SageMath is an open source library of mathematical functions built in Python.)

The contents are as follows:

1. Vigenere.pdf. This is a set of slides explaining the background to the Vigenere ciper.
2. Vigenere.ipnyb. A selection of SageMath code showing how to break the Vigenere cipher. If you have an installation of SageMath you can upload this file directly.
3. Vigenere.html. HTML file containing the same code. If you do not have SageMath installed, you can run the code using the following steps:
  * Click on Vigenere.html
  * Click the button in the top right of the screen to download the raw code
  * Open a new tab in your browser
  * In the File menu of your browser, select Open File
  * Open Vigenere.html in your browser
  * Open another tab and navigate to https://sagecell.sagemath.org/
  * Select the text in the first text box of Vigenere.html and copy it
  * Paste the text into the text box in sagecell.sagemath.org
  * Underneath the text you have copied into sagecell.sagemath.org, enter the commands
  
     CryptText = ShiftEncryption('WAKE UP CALL', 3)
     
     CryptText
     
  * Press the Evaluate button to see the result of your computation
  * The other commands can be executed in the same way, by entering them underneath the list of definitions you have copied from Vigenere.html
