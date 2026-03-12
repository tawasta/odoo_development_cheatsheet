# Odoo development cheatsheet

Collection of commonly needed material in Odoo development.

This repository is just to provide some helpers that aren't necessary well-tested.
Use at your own risk.

## Contents
- [[8.0] Security groups](security_groups/security_groups_8.0.md)
- [[9.0] Security groups](security_groups/security_groups_9.0.md)
- [[10.0] Security groups](security_groups/security_groups_10.0.md)
- [[11.0] Security groups](security_groups/security_groups_11.0.md)
- [[12.0] Security groups](security_groups/security_groups_12.0.md)
- [[13.0] Security groups](security_groups/security_groups_13.0.md)
- [[14.0] Security groups](security_groups/security_groups_14.0.md)
- [[15.0] Security groups](security_groups/security_groups_15.0.md)
- [[16.0] Security groups](security_groups/security_groups_16.0.md)
- [[17.0] Security groups](security_groups/security_groups_17.0.md)
- [[18.0] Security groups](security_groups/security_groups_18.0.md)

## Updating
1. Create a new security_groups-file in [Security groups](security_groups)
2. Go to https://runbot.odoo.com/ and login to an instance (Enterprise-version)
3. Order by name
4. Export all security groups as CSV (name, external id)
5. Open with your favourite regex-capable text editor and replace `^([^,]+),([^ ]+)$` with `- **\1** - *\2*`
6. Fix the headers (fist line) by hand
7. Check that everything seems sane
8. Add a new link to the Contents-section above -^
9. Commit and push. Thanks!

---
Licensed WTFPL - feel free to utilize this as you see fit
