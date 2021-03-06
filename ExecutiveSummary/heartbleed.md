Heartbleed
==========
**Your boss comes to you and says, "While I was driving in to work, on the radio they mentioned some virus or something called Heartbleed. I'm worried about our website. Look into it and report back to me on it." and he forwards you this news article: [Heartbleed is about to get worse, and it will slow the internet to a crawl](http://www.washingtonpost.com/blogs/the-switch/wp/2014/04/14/heartbleed-is-about-to-get-worse-and-it-will-slow-the-internet-to-a-crawl/). Investigate the issue (not just this one article) and write an executive summary to explain the matter to your boss, along with suggestions.**

Executive Summary I
-------------------
Together our security team has looked into the impact of the Heartbleed vulnerability. This vulnerability, which allows an attacker to gain access to vital system information, is caused by a bug in OpenSSL. We heavily use OpenSSL across many of our systems for secure authentication, so it is with utmost importance that we fix this issue.

Since then we have updated our servers to use LibreSSL instead of OpenSSL. This simple update removes all vulnerabilities related to Heartbleed and allows us to continue running securely. We will monitor the fallout from this vulnerability and continue to provide updates.

Executive Summary II
--------------------
The Heartbleed bug aﬀects a vast amount of web servers, which in turn aﬀect all of the users of these servers. Speciﬁcally, it is a bug found in the OpenSSL library that is treated as an industry standard; in other words, it is used almost everywhere. We must be sure to take the necessary precautions against this bug, and follow the prescribed remedies.

Common Vulnerabilities + Exploits, or CVE for short, catalog exploits from around the world and oﬀer ﬁxes. For this speciﬁc vulnerability, the ﬁx is simple; update OpenSSL to the latest version, and the vulnerability will be gone. System administrators have reported that updating OpenSSL will not aﬀect day-to-day server operations, so it is a simple process that will result in minimal downtime.

Executive Summary III
---------------------
If the site is using Open SSL service, then we need to patch the whole that heartbleed makes, and change our security keys and passwords. Otherwise you don’t have to do anything. We will do a quick fix that will patch the major vulnerabilities to protect the site certificate. If we do have to change the security keys, it will take customers longer to get into the site, because they have to update the security keys.

Executive Summary IV
--------------------
The Heartbleed bug is a serious security threat to our website. A malicious entity could easily get the certificates to our website and use them to misrepresent us. This is a huge legal and business problem since we could potentially be liable for the security flaw and lose business in the process. I recommend we fix our website by upgrading our servers to the new version of OpenSSL. This will ensure that hackers can't steal sensitive information from the server using this vulnerability. We will examine the server logs to determine if bug has been exploited, and notify our users if it has.

Heartbleed is security flaw in OpenSSL, a piece of software used by many websites, including large sites like Facebook and Google. We need to take action to secure our web server. We can fix it by upgrading our version of OpenSSL. This will protect us from damages both legal and financial. We will also need to request a new SSL certificate, and then require users to change their passwords after the site is secured.

Executive Summary V
--------------------

Heartbleed is an SSL exploit that hacker can use to obtain proprietary information from websites.

* Possible Problems
  * Certificate theft
  * User information leaks
Hackers may have obtained a copy of our security certificate meaning they may be able to duplicate our website to trick clients.  They also may have obtained our users’ information.  

* Recommendation
  * Update security information
  * Update client information
  * Update Software 
We’ll need to update our security information and web certificate in case they were obtained by hackers.  We should also alert all users that their information may have been compromised, and that they should update this information.  We must also upgrade to the latest version of SSL to prevent future security risks.

* Conclusion
Poor programming practices led to security risks amongst modern hacking society.  This has affected nearly all websites.  The course of action outlined in this summery will insure security and authenticity of the website, reevaluating for the Heartbleed bug.


Executive Summary VI
--------------------
**Purpose of Study**

The Heartbleed bug opens up vulnerabilities that allows sensitive information to be accessed by hackers through OpenSSL certificates.
With the services our website provides, it is crucial to check our security implementations and verify that all data is safe and secure.

**Findings**

There is no way of knowing if or how much data was compromised due to the Heartbleed bug.
However, we determined that our website was vulnerable to the Heartbleed bug, and therefore issued emails to all users to change their passwords in case they were stolen, as well as update their account security (i.e. security questions).
Additionally there is no method of calculating the cost of damages.

To prevent future exploitations we recommend the following actions be taken:

**Recommendations**

* Mandatory:
  * Update our website security certificates by updating OpenSSL.
  * All users must be contacted via emailed and asked to change their account passwords and update other security information. 
  * Require users to change their passwords upon next logon.

* Suggested:
  * Implementing two-factor authentication for all users, as another measure of trying to protect data and block any nefarious actions by unknown parties.
  * The best plan for a user to insure their privacy of data is:
    * Update their account details.
    * Clear all security certificates so that they may be replaced with new, secure ones



On our end, we should verify all security measures and test our certificates and user – database interactions for any potential security issues.
