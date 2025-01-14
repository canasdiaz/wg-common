# Release Frequency

Question: How often does a project publish a release of their software / artifact?

Context Tags: Lifecycle (Time/Duration), Software

Keywords: release, bug fixes, security, version, release cycle, cadence

## Description
The frequency of project software / artifact releases over time. This includes the major releases and smaller point releases that might contain bug fixes and security updates. 

## Objectives
When software developers update the code for an open source project, they also need to put those changes into a release that users can install. Consumers rely on these releases to contain new features, bug fixes, and security updates. Releasing updates that contain accessibility features or bug fixes that impact accessibility could have a positive impact on Diversity Equity and Inclusion (DEI) when they are released quickly or a negative impact when accessibility updates are delayed. Delays in incorporating changes into a release, especially when the changes contain security updates, can mean that users don’t have an easy way to upgrade from an insecure version and are open to malicious attacks or other vulnerabilities. 

A higher frequency of releases indicates that software artifacts are iterating rapidly to respond to user needs. Software projects belong to different industries and fields, and no two projects have the same needs, so release frequency is highly variable. A consistent release frequency may indicate a more stable or mature project.

## Implementation

### Filters
- Type of release. E.g., major, minor, bug fix, pre-release, alpha, or based on semantic versioning [1].
- Tag name.
- Count. Total number of releases during the period.
- Dates. Creation, publication.
- Period of time. Start and finish date of the period. 
- Size. Bytes or lines of code.

### Visualizations
- Count per time period (i.e., weeks, months, years) over time

These could be grouped by applying the filters defined above. These could be represented as bar charts or as individual points with time running in the X axis.

### Tools Providing the Metric 

[OSS-Compass](https://oss-compass.org/) Visualization[2]:
![OSS Compass Recent Releases Count visualization](https://raw.githubusercontent.com/chaoss/wg-common/main/focus-areas/time/images/release-frequency-oss-compass.png)

Visualization of Augur data using Python [3]:
![Releases visualized across time using data from Augur graphed using Python scripts](https://raw.githubusercontent.com/chaoss/wg-common/main/focus-areas/time/images/release-frequency-python-augur.png)

### Data Collection Strategies

In many cases, this data can be collected from the same platform as the source code (e.g., GitHub, GitLab, Gitee); however, some projects may also release code via package managers, web pages, or other locations. The data collection should align with where the project publishes their releases and makes them available to their customers.

## References
- [1] [https://semver.org/](https://semver.org/)
- [2] [OSS-Compass](https://oss-compass.org/)
- [3] [CHAOSScon NA 2021 Lightning Talk](https://www.youtube.com/watch?v=DynqP2_W1ts)

## Known Contributors
- Dawn Foster
- Yehui Wang 
- Sean Goggins
- Elizabeth Barron 
- Matt Germonprez
- Vinod Ahuja
- Kevin Lumbard

*The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other laws. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md) for additional guidance.* 
