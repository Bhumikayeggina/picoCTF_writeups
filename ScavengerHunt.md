# Challenge Name: **Scavenger Hunt**

## Category: Web Exploitation
## Thought Process:
- Upon opening the webpage link, i found text saying just some basic html code and 2 tabs saying how and what.
- i opened its source code, and found a comment saying first part of the flag, and a part of the flag was there.
- i then realized the code was divided and hidden in parts
- and then i went to the mycss.css link and found the 2nd part.
- and then opened the myjs.js link, it had no part of the flag but had a comment saying how can i keep google from indexing.
- as the hint suggested I accessed /robots.txt and found the 3rd part and a comment saying something like apache server.
- and so i accessed /.htacces and found the 4rd part and another comment saying "i like making websites on mac".
- and since mac file= /.DS_Store, i accessed it finding the last part.
## Tools And Techniques used:
- Browser dev tools: Inspect → View Source
- Manual URL navigation to /mycss.css, /myjs.js, /robots.txt, /.htaccess, and /.DS_Store
- Basic Google research to understand .htaccess and .DS_Store
## Final Steps to Solve it:
ctrl+U → /mycss.css → /myjs.js → /robots.txt → /.htaccess → /.DS_Store
## Flag:
picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_f7ce8828}
