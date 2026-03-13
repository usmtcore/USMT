# USMT (User State Migration Tool)

Download latest version from Releases:       
https://github.com/migusmt/USMT/releases/tag/v17.4

## Introduction

USMT (User State Migration Tool) is an enterprise-grade command-line utility designed for IT professionals who manage large-scale Windows deployments and operating system transitions. It enables reliable capture, transfer, and restoration of user state data during OS refresh, in-place upgrade, or hardware replacement scenarios. USMT is widely used in managed environments where automation, consistency, and control over user data migration are critical.

The tool operates through two core components—ScanState and LoadState—which allow administrators to collect and reapply user profiles, documents, application settings, and operating system preferences. Migration behavior is fully customizable through XML configuration files, giving advanced users granular control over what data is included, excluded, redirected, or filtered. This flexibility makes USMT suitable for complex enterprise environments with strict compliance, storage, and security requirements.

USMT integrates seamlessly with deployment frameworks such as Microsoft Deployment Toolkit (MDT), Configuration Manager (SCCM), and task sequence–based workflows. It supports offline and online migrations, hard-link scenarios to reduce disk usage, and encrypted migration stores to protect sensitive user data. Logging, verbosity levels, and return codes are designed to support troubleshooting and automation at scale.

USMT is designed for high performance and automation, making it ideal for administrators, system engineers, and deployment professionals who need consistent and repeatable migrations across large numbers of endpoints. When configured correctly, it reduces user downtime while maintaining the integrity of user environments during Windows lifecycle upgrades.
