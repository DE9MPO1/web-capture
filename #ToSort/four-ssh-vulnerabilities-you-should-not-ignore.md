# Four SSH Vulnerabilities You Should Not Ignore

_Captured: 2018-04-18 at 07:33 from [dzone.com](https://dzone.com/articles/four-ssh-vulnerabilities-you-should-not-ignore?edition=374212&utm_source=Daily%20Digest&utm_medium=email&utm_campaign=Daily%20Digest%202018-04-17)_

Learning by doing is more effective than learning by watching - that's why [Codebashing](https://dzone.com/go?i=274431&u=https%3A%2F%2Fwww.checkmarx.com%2Fcodebashing%2F%3Futm_medium__c%3Dreferral-content%26utm_source__c%3Ddzone%26utm_campaign__c%3Dcodebashing%26utm_content__c%3Dwhy-codebashing%26utm_medium%3Dreferral-content%26utm_source%3Ddzone%26utm_campaign%3Dcodebashing%26utm_content%3Dwhy-codebashing) offers a hands-on interactive training platform in 10 major programming languages. [Learn more](https://dzone.com/go?i=274431&u=https%3A%2F%2Ffree.codebashing.com%2F%3Futm_medium__c%3Dreferral-content%26utm_source__c%3Ddzone%26utm_campaign__c%3Dcodebashing%26utm_content__c%3Dtry-codebashing-free%26utm_medium%3Dreferral-content%26utm_source%3Ddzone%26utm_campaign%3Dcodebashing%26utm_content%3Dtry-codebashing-free) about AppSec training for enterprise developers.

![](https://www.cyberark.com/wp-content/uploads/2016/04/cyberark_ssh_-thumbnail.png)

The Secure Shell (SSH) protocol was created in 1995 by a researcher from the University of Helsinki after a password-sniffing attack. SSH is the tool of choice for system admins and is used throughout traditional and virtual datacenter environments to enable secure remote access to Unix, Linux, and, sometimes, Windows systems. You can think of the SSH key, which enables this remote access, as a " [Swiss Army Knife](https://www.cyberark.com/blog/ssh-keys-powerful-unprotected-privileged-credentials/) " for IT teams, in that it helps administrators and developers authenticate to systems, build authentication into systems and applications, and encrypt the resulting traffic between its users and systems.

During the authentication process, these SSH keys often establish direct, privileged, or root access to a variety of critical systems, effectively turning these cryptographic assets into privileged credentials. SSH keys are granted the same access as passwords, but when most people think about securing their privileged credentials, they forget about SSH keys. As a result, these keys can easily fall into the wrong hands, and instead of protecting access to important assets, these keys can become "[virtual skeleton keys](https://www.cyberark.com/resource/idc-market-spotlight-minimizing-cybersecurity-risk-with-vigilant-ssh-key-management/)." To make matters worse, when an attacker gains access to one privileged SSH key, she or he can access every SSH key stored on that machine and spider the entire company network, often gaining access to all company data. As few as five to 20 unique SSH keys can grant access to an entire enterprise through transitive SSH key trust, providing attackers with privileged access to the organization's most sensitive systems and data.

### **Four SSH Vulnerabilities You Should Not Ignore:**

  1. **SSH Key Tracking Troubles. **It's not uncommon for a typical large enterprise with 10,000+ servers to have more than one million SSH keys - making it incredibly difficult, if not impossible, to find and manage each key. Organizations typically accumulate large numbers of SSH keys because end users can create new SSH keys (credentials) or even duplicate them without oversight, unlike certificates, or passwords. Once a large number of SSH keys are built up over time, an organization could, for example, easily lose track of these credentials when development servers are migrated into production environments (assuming the development environment credentials are not scrubbed) or when employees leave the company and their keys are not changed. The result? Unaccounted-for SSH keys can provide attackers with long-term privileged access to corporate resources. If attackers gain access to a key that is never revoked or rotated, the attackers could have a permanent network entry point and impersonate the user that the SSH key originally belonged to.
  2. **When it Comes to SSH Keys, Sharing Isn't Caring. **For the sake of efficiency, SSH keys are often shared or replicated across a common group of employees or servers and infrastructure components. Noted above, as a result of SSH key duplication, as few as five to 20 unique keys can grant access to all machines throughout an enterprise. This approach may make IT teams' jobs easier in the short-term, but it also makes attackers' lives easier in the long-term. SSH key duplication creates complicated, many to many private-public key mappings that significantly reduce security because it is difficult to rotate and revocation a single key without breaking untold other SSH key relationships that share the same key fingerprint. SSH key sharing is also dangerous because it reduces auditability and non-repudiation.
  3. ** Static SSH Keys, Because "Ain't Nobody Got Time for Rotation!"** It's easy to see how rotating one million plus SSH keys would be a logistical nightmare. Many IT administrators and security professionals rarely change and re-distribute keys for fear that a critical component or employee may be forgotten (which could mean anything from a simple inconvenience for a single employee to a major company-wide system outage). These factors typically result in a surge of static SSH keys, opening the door for attackers to compromise an unchanged key, use it to move laterally through the enterprise, and gain permanent, unauthorized access to sensitive data and assets.
  4. ** Embedded SSH Keys - The Ones No One Wants to Mess With. **SSH keys are frequently embedded within applications or scripts. Administrators are often fearful of changing them as they do not understand the code the keys are embedded in or are strongly discouraged from rotating them because of the level of coordination required to prevent system outages. As a result, static SSH keys embedded in applications, code, and scripts can lead to persistent backdoors for attackers.

SSH keys can present a tremendous opportunity for hackers to gain privileged access to networks, stay connected, impersonate legitimate users, hide their activity with encryption, and move about freely.

![](https://www.cyberark.com/wp-content/uploads/2016/04/SSH-Key-Graphic_V2-short-751x1024.jpeg)

> _Editor's Note: This article has been updated. It was originally published April 2016._

Find out how [CxSAST](https://dzone.com/go?i=274427&u=https%3A%2F%2Fwww.checkmarx.com%2Ftechnology%2Fstatic-code-analysis-sca%2F%2520%3Futm_medium__c%3Drefe%2520rral-content%26utm_source__c%3Ddzone%26utm_campaign__c%3D%2520cxsast%2520%26utm_content__c%3D%2520che%2520ckmarx-cxsast%2520%26utm_medium%3Dreferral-content%26utm_source%3Ddzone%26utm_campaign%3D%2520cx%2520sast%2520%26utm_content%3D%2520checkmarx-cxsast) can help you scan uncompiled and unbuilt code while identifying hundreds of security vulnerabilities in the most [prevalent coding languages.](https://dzone.com/go?i=274427&u=https%3A%2F%2Fwww.checkmarx.com%2Flanguage-overviews%2F%2520%3Futm_medium__c%3Dreferral-content%26ut%2520m_source__c%3Ddzone%26utm_campaign__c%3D%2520cxsast%2520%26utm_content__c%3D%2520coding-languages%2520%26%2520utm_medium%3Dreferral-content%26utm_source%3Ddzone%26utm_campaign%3D%2520cxsast%2520%26utm_cont%2520ent%3D%2520coding-languages)