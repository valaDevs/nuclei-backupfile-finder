# Bakup Files Finder Nuclei Template

This YAML file is a nuclei template used for discovering the hidden backup files in the webservers.

## Usage



```bash
  nuclei -u https://yourtarget.com -t vabro-backup-file-finder.yaml
```
or
```bash
nuclei -l yourtargetlist.txt -t vabro-backup-file-finder.yaml
    
