---
name: False Positive Report
about: Report legitimate sites being incorrectly blocked
title: '[FALSE POSITIVE] '
labels: 'false-positive, priority'
assignees: ''
---

**Website/Service affected**
Name of the legitimate website or service being blocked:

**Which blocklist contains the false positive?**
- [ ] pubg-block.txt
- [ ] Facebook
- [ ] instagram-pihole
- [ ] snapchat-pihole
- [ ] tiktok-pihole
- [ ] doh-list
- [ ] hitv.list
- [ ] huawei-host
- [ ] ublock_ads_list
- [ ] Android Tracking
- [ ] tiktock-tracking
- [ ] Unknown/Multiple lists
- [ ] Other: ___________

**Incorrectly blocked domain(s)**

legitimate-site.com
api.legitimate-service.com

**What functionality is broken?**
Describe what stops working when these domains are blocked:

**Why this is a false positive**
Explain why this domain should NOT be blocked:
- [ ] Essential for website functionality
- [ ] Not an ad/tracking server
- [ ] Required for authentication/login
- [ ] Required for payment processing
- [ ] Other: ___________

**Steps to verify**
1. Block the domain
2. Visit [website]
3. Notice [specific feature] doesn't work
4. Whitelist the domain
5. Feature works again

**Evidence**
Provide any evidence that this is a legitimate domain (documentation, official sources, etc.):

**Temporary workaround**
Have you found a workaround? Share it here to help others:
