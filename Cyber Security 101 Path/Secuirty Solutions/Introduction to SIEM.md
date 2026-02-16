# Task 1 - Introduction

<p>We begin this module by learning what the "SIEM" acronym stands for; "Security Information and Event Management system"</p>
<p>Mostly we'll focus be learning about how different devices generate logs and why and how we need these logs to be handled</p>

# Task 2 - "Logs Everywhere, Answers Nowhere"

<p>There are two main categories in which we can devide log sources:</p>

1) Host-Centric Log Sources

<p>They capture events that occurred within or related to the host, such as user accessing files, adding/editing/deleting registries or PowerShell execution</p>

2) Network-Centric Log sources

<p>These are generated when hosts communicate with each other or access the internet, things like firewalls, IDS/IPS, and routers, things such as an SSH connection, Web traffic and File sharing activity.</p>

# Task 3 - Why SIEM?

<p>The basic idea behind SIEM is to have a Security solution that collects these logs, standardizes them, correlates them, and detects malicious activities using detection rules</p>
<p>It provides the following features:</p>

* Centralized Log Collection
* Normalization of Logs
* Correlation of Logs
* Real-time Alerting
* Dashboards and Reporting

# Task 4 - Log Sources and Ingestion

<p>Widnows stores logs in "Event Viewer", and Linux has files under the /var/log/ directory</p>
<p>each SIEM has its own way of ingestion.</p>

# Task 5 - Alerting Process and Analysis

<p>Using a SIEM we can fine tune settings to get alerted in particular events. If there is a lot of false positives it might be worth tweaking.</p>

# Task 6

<p>There was a rudimentary SIEM simulation, in which I detected a crypto mining process and after determining it as a true positive, it was isolated.</p>
