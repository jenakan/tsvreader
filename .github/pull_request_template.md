### Secure Coding Checklist
* [ ] No raw SQL executes untrusted, unsanitized or unvalidated parameters.
* [ ] Session variable is not present on the URL.
* [ ] Passwords are using an adaptive hashing algorithm.
* [ ] Code is free from XSS exploits.
* [ ] URL parameters are constrained to the logged in user.
* [ ] Administrative functionality is only provided to Wave authorized users.
* [ ] Ensure information is exposed only to authorized users.
* [ ] URLs are protected by backend authorization, rather than hiding in the front-end.
* [ ] Dynamic URL-based redirects are validated either against a white-list on the backend, mapped to a token on the backend, or reference relative url paths.
* [ ] Ensure we do not incur > O(n+1) queries when dealing with collections of data.
* [ ] Ensure any libraries are pinned to the expected version.
* [ ] Ensure that all requests to HTTPS endpoints include certificate validation
