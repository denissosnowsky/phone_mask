# phone_mask
Phone mask for the websites' forms

I've been searching in the Internet for phone masks for my website, but usually I've been encountering some JQuery masks. I wanted to use basic JavaScript for the website, I decided to create my own phone mask using basic JavaScript and no libraries.

This mask allows to input only numbers, and automatically shows a mask of the phone pattern, where "_" means numbers of the phone. Also, no matter where you put your cursor, the mask will input numbers in the right places.

"phoneInputElement" - means the selector of your phone input in the form

In order to work perfectly in the form, a script for the form button is needed, which will prohibit form submission unless all the numbers are written.
