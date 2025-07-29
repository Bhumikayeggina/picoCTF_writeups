# Challenge Name: **Local Authority**

## Category: Web Exploitation
## Thought Process:
- Upon opening the webpage link, it asked for login credential.
- i gave some dummy login and it said login failed.
- i opened the devtools, went to source tab and opened secure.js
- the username and passwords were mentioned there.
- i logged in using those, the final flag was found there
## Tools And Techniques used:
- Browser Developer Tools → Network / Sources
- Viewing JavaScript file (secure.js) to find hidden credentials
- Using discovered credentials to access the admin page
## Final Steps to Solve it:
- username: admin
- password: strongPassword098765
## Flag:
picoCTF{j5_15_7r4n5p4r3n7_a8788e61}
