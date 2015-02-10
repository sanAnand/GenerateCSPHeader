# GenerateCSPHeader
Based on a given URL, generate Content Security Policy headers for the entire website. 

V1.0 goals:

 - Command line interface
 - Provide URL (home page preferably) as input
 - Expect 3 kinds of CSP headers as output (Strict, Optimal, Minimal)
 - Code written in Python
 - Applicaiton crawls the website, attempts to find all 3rd party images, scripts, frames etc and forms aforementioned CSP headers
 
V2.0 goals:
   - Add UI
   - Add "known-good" websites (e.g.: Twitter CDN is OK)
   - Allow people to share
   

