|Version  |3.4 |3.5 |3.6 |3.7 |3.8 |
|---------|-----|-----|-----|-----|-----|
|Release date| Mar. 15 2022|  May 31 2022 |Aug. 16 2022 |Nov. 8 2022 |Mar. 7 2023 |
|| [Release notes](github.com)|[Release notes](github.com)|[Release notes](github.com)|[Release notes](github.com)|[Release notes](github.com)|

### Secret scanning features
|Feature  |3.4 |3.5 |3.6 |3.7 |3.8 |
|------------------------------------------------------------|-----|-----|-----|-----|-----|
|Partner pattern count|155|169|173|173|183|
|User defined patterns|✅|✅|✅|✅|✅|
|Enterprise level API for secret scanning|✅|✅|✅|✅|✅|
|Secret scanning push protection||✅|✅|✅|✅|
|Dry runs for secret scanning push protection (repo level)||✅|✅|✅|✅|
|Secret scanning support for archived repos||✅|✅|✅|✅|
|Custom pattern events in the audit log||✅|✅|✅|✅|
|Push protection events in the audit log|||✅|✅|✅|
|Push protection in the web editor|||✅|✅|✅|
|Enable secret scanning at the enterprise level||||✅|✅|
|Dry runs for secret scanning push protection (org level)||||✅|✅|
|Email notification for push protection bypass||||✅|✅|
|Custom links in push protection notification||||✅|✅|
|View secret scanning enablement status at the org-level via API||||✅|✅|
|Enable secret scanning at the enterprise level using the REST API|||||✅|
|Add comment when dismissing a secret scanning alert in UI or API|||||✅|


### Code scanning features
|Feature  |3.4 |3.5 |3.6 |3.7 |3.8 |
|------------------------------------------------------------|-----|-----|-----|-----|-----|
|CodeQL "toolcache" Installed Version|2.7.6|2.8.5|2.9.4|2.10.5|2.11.6|
|Python, Javascript, Java, Go, C/C++, C#, Typescript"|✅|✅|✅|✅|✅|
|Ruby Support|☑️|☑️|☑️|☑️|✅|
|Apple M1 support for CodeQL|☑️|☑️|☑️|☑️|✅|
|Org-wide code scanning alerts via the REST API||✅|✅|✅|✅|
|Add comments when dismissing alerts|||✅|✅|✅|
|Code scanning alert comments in the pull request conversation tab||||✅|✅|
|Users can publish CodeQL packs to the container registry||||✅|✅|
|CodeQL query filters to exclude individual queries||||✅|✅|
|Enterprise-wide code scanning alerts via the REST API||||✅|✅|
|Filter API results by severity|||||✅|
|Kotlin language support|||||☑️|

### Supply-chain security features

|Feature  |3.4 |3.5 |3.6 |3.7 |3.8 |
|------------------------------------------------------------|-----|-----|-----|-----|-----|
|Go modules support|✅|✅|✅|✅|✅|
|Poetry support|✅|✅|✅|✅|✅|
|Cargo support|||✅|✅|✅|
|Dependabot Alerts - Docs|✅|✅|✅|✅|✅|
|Ungrouped alerts / alerts per single vulnerability||✅|✅|✅|✅|
|Reopen dismissed alerts	|||✅|✅|✅|
|Dependabot alerts show vulnerable function calls - Blog post|||☑️|☑️|☑️|
|Dependabot Alert timeline||||✅|✅|
|Bulk Editing of Alerts||||✅|✅|
|Add comment when dismissing dependabot alert||||✅|✅|
|Dev Dependencies label	||||✅|✅|
|Alert to PR Mapping||||✅|✅|
|Alerts pages now auto refresh||||✅|✅|
|View Dependabot enablement status via org-level API||||✅|✅|
|Receive alerts for vulnerable GitHub Actions||||✅|✅|
|Dependabot alert webhooks||||✅|✅|
|Suggest improvements to an advisory|||||✅|
|Labels in the row page act as filters|||||✅|
|Dependabot alerts REST API endpoint for repository org and enterprise|||||☑️|
|Dependabot Updates - Docs|☑️|✅|✅|✅|✅|
|Actions authors can automatically update dependencies within workflow files|||||✅|
|Dart and Flutter (using Pub) support for updates|||||✅|
|Dependency Review - Docs|✅|✅|✅|✅|✅|
|Enforcement Action - Docs (excludes scopes/licenses)|||✅|✅|✅|
|Dependency Submission API - Docs||||✅|✅|


### Administrative and visibility features
|Feature  |3.4 |3.5 |3.6 |3.7 |3.8 |
|------------------------------------------------------------|-----|-----|-----|-----|-----|
|Security Overview - Docs|✅|✅|✅|✅|✅|
|Organization view|☑️|✅|✅|✅|✅|
|Enterprise view||☑️|☑️|✅|✅|
|Organization-level Code Scanning Alert View||✅|✅|✅|✅|
|Organization-level Dependabot Alert View||✅|✅|✅|✅|
|Enterprse-level view of Dependabot alerts|||✅|✅|✅|
|Enterprse-level view of code scanning alerts||||✅|✅|
|Enterprse-level view of secret scanning alerts||||✅|✅|
|Coverage and Risk Security Overview pages|||||☑️|
|||||||
|Security Managers Role - Docs|✅|✅|✅|✅|✅|
|Manage Security Managers role via the API||||✅|✅