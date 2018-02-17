# Vulnerability in passwordsquirrel's password app.

A critical security flaw has been found in passwordsquirrel's password management app.

## Details

The url: /getpw.php is vulnerable to SQL injection.

get url parameters are:
```
username
password
pwname
```

If a user passes the authorization check, the pwname filed is susceptible to an injection attack.

It does not appear username and password are vulnerable, but further investigation should be done.


## Example

to come...

