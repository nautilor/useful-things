# Bash snippet

```bash
# Search for files in root and subdirectory folder with the specified string
find . -type f -print0 | xargs -0 grep -l "search string"
```
