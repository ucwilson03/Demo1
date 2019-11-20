---
name: Version Description Audit
document revision history: Tell the CM experts about an upcoming software release
product version history: "[PRODUCT] v [VERSION]"
product name: "[NAME] v [TITLE]"
Configuration Manager: ''

---

| Document Vevision History
And
Deliverable (Product) Version History | Example(s) |  Repository Type(s)    | Notes |

|:------------------------------------|:--------------------------------------------------------------------|:-----------------|
|VA Service Team|
 ⦁ Release Readiness Office<br> 
 ⦁ EPMO CMD|⦁ product repository| Service teams tend to source control documentation artifacts only. </br> |
|VA Product| ⦁ BIO BIS </br> ⦁ EPRS </br>  ⦁ VDIF|⦁ product repository<br>⦁ code-project repository | VA products tend to source control both documentation and code artifacts. These repositories are based on code base and architecture. |

## EPMO Configuration Management VDD Audit Sheet
---
name: New Version Description Audit
reviewer: Tell the CM experts about an upcoming software release
product name: "[PRODUCT] v[VERSION]"
reviewer(s): "[NAME] v[TITLE]"
configuration manager: ''

---

Please check that you've completed the following, adding the appropriate version numbers and links to the checkbox items. See the Example Release below for details.

- [ ] Tag your release using semantic versioning. For example v0.1.547, like /v<Major #>.<Minor #>.<Patch/Maintenance #>.<Build #>.
	Release version: 
- [ ] Create a new Release in GitHub. 
	Release URL:
- [ ] Title your release with the component name and the version number, For example "vets-website v0.1.547", where <Product> v<Major #>.<Minor #>.<Patch/Maintenance #>.<Build #>.
- [ ] Upload a compiled/built version of the software (.jar or .war file, etc.)
- Add Release Notes with the following: 
	- [ ] High-level description of the purpose of the release, what it accomplishes.
	- [ ] Milestone that links to issues (Epics, User Stories, Tests, Bugs) addressed by this release 
		Milestone link:
	- [ ] Compare link to the previous release (baseline)
		Comparison link:


<!--	
### Example Release: Reading Time v1.1.0

Please reference the 1.1.0 release of our demonstration Reading Time app:
https://github.com/department-of-veterans-affairs/reading-time-demo/releases/tag/v1.1.0

Product/Project Name: Reading Time

Product/Project Repository: https://github.com/department-of-veterans-affairs/reading-time-demo

Release tag & title (v followed by the semantic version number): v.1.1.0

Release URL: 
https://github.com/department-of-veterans-affairs/reading-time-demo/releases/tag/v1.1.0

Release notes:

> Adding a book rating feature and other updates.
> 
> User stories and tasks addressed by this release:
> https://github.com/department-of-veterans-affairs/reading-time-demo/milestone/1
> 
> Differences between this release and the previous baseline: https://github.com/department-of-veterans-affairs/reading-time-demo/compare/v1.0.165...v1.1.0

-->

Configuration Management Identification


| Product Identification | Element |  Description	   | Notes |
|:---------------------------------|:-------------|:--------------------------------------------------------------------|:-----------------|
|VA Service Team| ⦁ EPMO CMD Offic<br> ⦁ EPMO CMD|⦁ product repository| Service teams tend to source control documentation artifacts only. |
|VA Product| ⦁ BIO BIS <br>⦁ EPRS</br>⦁ VDIF|⦁ product repository<br>⦁ code-project repository | VA products tend to source control both documentation and code artifacts. These repositories are based on code base and architecture. |
|VA Infrastructure-only Product|</br> ⦁ VA WiFi Lifecycle Refresh<br>⦁ Enterprise Endpoint Security|⦁ product repository<br>⦁ code-project repository| VA Infrastructure products can source control both documentation artifacts and Infrastructure-specific artifacts based on what is being delivered |

| Product Release Version | Example(s)  |  Repository Type(s)    | Notes |
|:---------------------------------|:-------------|:--------------------------------------------------------------------|:-----------------|
|VA Service Team| ⦁ EPMO CMD Offic<br> ⦁ EPMO CMD|⦁ product repository|Name of Runtime Deliverable to be installed into VA environment. 
Product Registration Name (PRP 1.3 - Assign project registration and development domain) |
|VA Product| ⦁ BIO BIS <br>⦁ EPRS</br>⦁ VDIF|⦁ product repository<br>⦁ code-project repository | VA products tend to source control both documentation and code artifacts. These repositories are based on code base and architecture. |
|VA Infrastructure-only Product|</br> ⦁ VA WiFi Lifecycle Refresh<br>⦁ Enterprise Endpoint Security|⦁ product repository<br>⦁ code-project repository| VA Infrastructure products can source control both documentation artifacts and Infrastructure-specific artifacts based on what is being delivered |


|Other|

