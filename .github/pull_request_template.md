## Description
<!--- Describe your changes in detail -->
<!--- Why is this change required? What problem does it solve? -->

Fixes #(issue number)

## Type of change
<!--- Put an `x` in all the boxes that apply -->
- [ ] 🐛 Bug fix (false positive removal)
- [ ] ➕ New domains added to existing list
- [ ] 📝 New blocklist file
- [ ] 🔧 List maintenance/cleanup
- [ ] 📚 Documentation update
- [ ] ⚡ Performance improvement

## Affected blocklist(s)
<!--- List which files you've modified -->
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
- [ ] Other: ___________

## Domain changes
### Added domains:

### Add new domains here
example-tracker.com
ads.example.net

### Removed domains (false positives):
### List removed domains here
legitimate-site.com

## Validation checklist
<!--- Go over all the following points, and put an `x` in all the boxes that apply -->
- [ ] I have verified all added domains are actually ad/tracking servers
- [ ] I have checked for false positives (legitimate sites won't be blocked)
- [ ] Domains follow proper format (no http://, no paths, just domains)
- [ ] No duplicate entries added
- [ ] Lists are sorted alphabetically (if applicable)
- [ ] I have tested these changes with Pi-hole
- [ ] No whitespace or formatting issues

## Testing performed
<!--- Describe how you tested these changes -->
**Pi-hole version tested:** 
**Number of domains tested:** 
**Testing method:**
- [ ] Visited websites to confirm ads are blocked
- [ ] Checked for broken functionality
- [ ] Verified with DNS lookups
- [ ] Monitored Pi-hole query log

## Evidence
<!--- Provide evidence that domains should be blocked/unblocked -->
<!--- Screenshots, documentation, or analysis tools used -->

## Additional notes
<!--- Add any additional notes for reviewers -->
