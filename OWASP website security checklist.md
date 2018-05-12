# OWASP website security checklist

## Table of Contents

* [Information Gathering](#Information)
* [Authentication](#Authentication)
* [Session](#Session)

-------
### <a name="Information">Information Gathering</a>
- [ ] Manually explore the site
- [ ] Manually explore the site
- [ ] Spider/crawl for missed or hidden content
- [ ] Check for files that expose content, such as robots.txt, sitemap.xml, .DS_Store
- [ ] Check the caches of major search engines for publicly accessible sites
- [ ] Check for differences in content based on User Agent (eg, Mobile sites, access as a Search engine Crawler)
- [ ] Perform Web Application Fingerprinting
- [ ] Identify technologies used
- [ ] Identify user roles
- [ ] Identify application entry points
- [ ] Identify client-side code
- [ ] Identify multiple versions/channels (e.g. web, mobile web, mobile app, web services)
- [ ] Identify co-hosted and related applications
- [ ] Identify all hostnames and ports
- [ ] Identify third-party hosted content
- [ ] Configuration Management:
- [ ] Check for commonly used application and administrative URLs
- [ ] Check for old, backup and unreferenced files
- [ ] Check HTTP methods supported and Cross Site Tracing (XST)
- [ ] Test file extensions handling
- [ ] Test for security HTTP headers (e.g. CSP, X-Frame-Options, HSTS)
- [ ] Test for policies (e.g. Flash, Silverlight, robots)
- [ ] Test for non-production data in live environment, and vice-versa
- [ ] Check for sensitive data in client-side code (e.g. API keys, credentials)
- [ ] Secure Transmission:
- [ ] Check SSL Version, Algorithms, Key length
- [ ] Check for Digital Certificate Validity (Duration, Signature and CN)
- [ ] Check credentials only delivered over HTTPS
- [ ] Check that the login form is delivered over HTTPS
- [ ] Check session tokens only delivered over HTTPS
- [ ] Check if HTTP Strict Transport Security (HSTS) in use

-------

### <a name="Authentication">Authentication</a>
- [ ] Test for user enumeration
- [ ] Test for authentication bypass
- [ ] Test for bruteforce protection
- [ ] Test password quality rules
- [ ] Test remember me functionality
- [ ] Test for autocomplete on password forms/input
- [ ] Test password reset and/or recovery
- [ ] Test password change process
- [ ] Test CAPTCHA
- [ ] Test multi factor authentication
- [ ] Test for logout functionality presence
- [ ] Test for cache management on HTTP (eg Pragma, Expires, Max-age)
- [ ] Test for default logins
- [ ] Test for user-accessible authentication history
- [ ] Test for out-of channel notification of account lockouts and successful password changes
- [ ] Test for consistent authentication across applications with shared authentication schema / SSO

-------

### <a name="Session">Session Management</a>
