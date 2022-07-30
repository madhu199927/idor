# idor
Authorization bypasses tricks:✅
🔸 Wrap ID with an array {“id”:123} --> {“id”:[123]}
🔸 JSON wrap {“id”:123} --> {“id”:{“id”:123}}
🔸 Send ID twice URL?id=<LEGIT>&id=<VICTIM>
🔸 Send wildcard {"user_id":"*"}


1) google dork site:domain login
2) visit the home page
3) see the js file in the site
4) idor boom! leak email and phone

We all try to change the valuse of parameters to find vulnerabilities , but did you know that you can also try 
to change the name of the parameter ?
ex: ?parameter==123  ==> 200 ok
?parameter[]==123 ==> Bypass Prtotection    && ?parameters[id']==123 ==> sql injecton 
