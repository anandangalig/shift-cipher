# _Caesar's Shift Cipher: Independent Project on Drupal_

####_A basic app practicing Drupal 7. 12/09/2016_

#### By _**Anand Angalig**_


## Description

_This web application can  encrypt text inputs using Caesar's Cipher. It is a type of substitution cipher in which each letter in the inputted text is replaced by a different letter that is determined by the user's desired direction and the number of positions down the alphabet._

![Alt text](https://learncryptography.com/assets/img/content/caesar_cipher.png "Optional title")

## Setup/Installation Requirements
  * _Install and initiate MAMP or similar solution stack of your preference if your local machine does not have them already_

  * _Clone the project directory from https://github.com/anandangalig/shift-cipher.git_

  * _Initiate MAMP in the highest level of the cloned directory_

  * _Open PHPMyAdmin, create a new database, and import the latest zipped .sql file from the db-backup folder_

  * _Go to localhost:8888 in your favorite browser to use the application_


## Specs:
* _Input: Shift Value = 1, Shift Direction = right, Text = AbC_
* _Output: bcd_

* _Input: Shift Value = 1, Shift Direction = left, Text = abc_
* _Output: bcd_

* _Input: Shift Value = 1, Shift Direction = right, Text = AbC_
* _Output: zab_

* _Input: Shift Value = 1, Shift Direction = right, Text = !?%&$_
* _Output: Error Message: "The phrase needs to consist of letters and punctuations"_

* _Input: Shift Value = 1, Shift Direction = up, Text = Hello_
* _Output: Error Message: "The direction needs to be either Left or Right."_

* _Input: Shift Value = 26, Shift Direction = right, Text = Hello_
* _Output: Error Message: "Shifting 26 spots gives you the same letter back. Try harder!"_


## Known Bugs
_No bugs known. If found, please bring it to my attention via e-mail._


## Support and Contact Details
_Please feel free to contact us at:_
    _anandangalig@gmail.com_

## Technologies Used

* _Drupal 7_
* _PHP_

### License
_Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:_

_The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software._

_THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE._

Copyright (c) 2016 **_Anand Angalig_**
