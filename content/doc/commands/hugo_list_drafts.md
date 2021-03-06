---
date: 2015-08-04T03:11:10-06:00
title: "hugo list drafts"
slug: hugo_list_drafts
doc: 
- commands

---
## hugo list drafts

List all drafts

### Synopsis


List all of the drafts in your content directory.

```
hugo list drafts
```

### Options

```
  -h, --help[=false]: help for drafts
```

### Options inherited from parent commands

```
  -b, --baseUrl="": hostname (and path) to the root eg. http://spf13.com/
  -D, --buildDrafts[=false]: include content marked as draft
  -F, --buildFuture[=false]: include content with publishdate in the future
      --cacheDir="": filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/
      --config="": config file (default is path/config.yaml|json|toml)
  -d, --destination="": filesystem path to write files to
      --disableRSS[=false]: Do not build RSS files
      --disableSitemap[=false]: Do not build Sitemap file
      --editor="": edit new content with this editor, if provided
      --ignoreCache[=false]: Ignores the cache directory for reading but still writes to it
      --log[=false]: Enable Logging
      --logFile="": Log File path (if set, logging enabled automatically)
      --pluralizeListTitles[=true]: Pluralize titles in lists using inflect
      --preserveTaxonomyNames[=false]: Preserve taxonomy names as written ("Gérard Depardieu" vs "gerard-depardieu")
  -s, --source="": filesystem path to read files relative from
      --stepAnalysis[=false]: display memory and timing of different steps of the program
  -t, --theme="": theme to use (located in /themes/THEMENAME/)
      --uglyUrls[=false]: if true, use /filename.html instead of /filename/
  -v, --verbose[=false]: verbose output
      --verboseLog[=false]: verbose logging
```

### SEE ALSO
* [hugo list](/doc/commands/hugo_list/)	 - Listing out various types of content

###### Auto generated by spf13/cobra at 2015-08-04 09:11:10.030650499 +0000 UTC
