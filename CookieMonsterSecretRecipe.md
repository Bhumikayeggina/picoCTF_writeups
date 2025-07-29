
# Challenge Name: **Cookie Monster Secret Recipe**

## Category: Web Exploitation
## Thought Process:
- Upon opening the webpage link, it asked for login credential.
- i gave some dummy login and it said acces denied
- But there was a hint, asking me if i checked the cookies recently.
- i opened the devtools, went to applications tab -> cookies
- the cookie value seemed URl-encode, base64 encode.
- i used cyber chef to decode it, revealing the final flag
## Tools And Techniques used:
- Web browser + Developer Tools
- Application → Cookies tab inspection
- CyberChef (URL Decode & Base64)
- Browser Console with JavaScript decoding
## Final Steps to Solve it:
- cookie value: cGljb0NURntjMDBrMWVfbTBuc3Rlcl9sMHZlc19jMDBraWVzXzA1N0JDQjUxfQ%3D%3D
## Flag:
picoCTF{c00k1e_m0nster_l0ves_c00kies_057BCB51}
