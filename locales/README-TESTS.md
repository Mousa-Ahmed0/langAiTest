# GitLang AI Test Cases

استخدم هاي الملفات لتجربة كل الحالات.

1. Basic missing keys:
Source: 01-basic-source-en.json
Target: 01-basic-target-ar.json

2. Variables + HTML validation:
Source: 02-variables-source-en.json
Target: 02-variables-target-ar.json

3. Extra keys:
Source: 03-extra-keys-source-en.json
Target: 03-extra-keys-target-ar.json

4. Nested JSON:
Source: 04-nested-source-en.json
Target: 04-nested-target-fr.json

5. Bulk translation:
Source: 05-large-source-en.json
Target: 05-large-target-ar.json

6. Risky keys + quality score:
Source: 06-risky-source-en.json
Target: 06-risky-target-ar.json

7. Multi-file:
07-multifile-common-source-en.json + 07-multifile-common-target-ar.json
07-multifile-auth-source-en.json + 07-multifile-auth-target-ar.json

8. New language file:
Source: 08-new-language-source-en.json
Target: 08-new-language-empty-target-fr.json

9. Review system:
Source: 09-approved-rejected-source-en.json
Target: 09-approved-rejected-target-ar.json

10. Duplicate path protection:
Use 10-duplicate-path-source-en.json and choose ar + fr with same target path.

11. Translation memory import:
Upload translation-memory-import.csv or translation-memory-import.json.
