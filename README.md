# 🛡 Backup Files Finder Nuclei Template

This Nuclei template is designed to discover hidden backup files on web servers. Exposing backup files can be a critical security vulnerability.

## 🚀 Usage

You can run the template against a single target or a list of targets.

### Single Target

To scan a single URL, use the following command:

```bash

nuclei -u https://your-target.com -t backup-file-finder.yaml

nuclei -u https://yourtarget.com -t backup-file-finder.yaml
```

### List of Targets

To scan a list of URLs from a file:

```bash
nuclei -l your-target-list.txt -t backup-file-finder.yaml
```

## 🤔 Why is this important?

Backup files can inadvertently expose sensitive information. They might contain:
-   Source code
-   Configuration files with credentials (API keys, database passwords)
-   User data
-   Older, vulnerable versions of an application

Finding these files can provide critical insights for security assessments.
=======
nuclei -l yourtargetlist.txt -t backup-file-finder.yaml
    