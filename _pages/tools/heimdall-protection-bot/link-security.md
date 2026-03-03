# Link Security

***

#### Link Security <a href="#link-security" id="link-security"></a>

Heimdall automatically checks links posted in chat for safety:

* **Safe domain whitelist:** Configurable list of trusted domains (cached with regular updates)
* **Redirect chain following:** Follows shortened URLs (bit.ly, t.co, tinyurl.com, etc.) to check the final destination
* **Pattern matching:** Regex patterns detect phishing, malware, and scam content on linked pages
* **404 detection:** Links returning 404 errors are flagged as dangerous
* **Re-checking:** Previously checked URLs are re-validated every 7 days
