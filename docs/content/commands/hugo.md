---
date: 2015-05-21T13:28:49+02:00
title: "hugo"
slug: hugo
url: /commands/hugo/
---
## hugo

hugo builds your site

### Synopsis


hugo is the main command, used to build your Hugo site. 
	
	Hugo is a Fast and Flexible Static Site Generator built with
love by spf13 and friends in Go.

Complete documentation is available at http://gohugo.io

```
hugo
```

### Options

```
  -b, --baseUrl="": hostname (and path) to the root eg. http://spf13.com/
  -D, --buildDrafts=false: include content marked as draft
  -F, --buildFuture=false: include content with publishdate in the future
      --cacheDir="": filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/
      --config="": config file (default is path/config.yaml|json|toml)
  -d, --destination="": filesystem path to write files to
      --disableRSS=false: Do not build RSS files
      --disableSitemap=false: Do not build Sitemap file
      --editor="": edit new content with this editor, if provided
  -h, --help=false: help for hugo
      --ignoreCache=false: Ignores the cache directory for reading but still writes to it
      --log=false: Enable Logging
      --logFile="": Log File path (if set, logging enabled automatically)
      --noTimes=false: Don't sync modification time of files
      --pluralizeListTitles=true: Pluralize titles in lists using inflect
  -s, --source="": filesystem path to read files relative from
      --stepAnalysis=false: display memory and timing of different steps of the program
  -t, --theme="": theme to use (located in /themes/THEMENAME/)
      --uglyUrls=false: if true, use /filename.html instead of /filename/
  -v, --verbose=false: verbose output
      --verboseLog=false: verbose logging
  -w, --watch=false: watch filesystem for changes and recreate as needed
```

### SEE ALSO
* [hugo benchmark](/commands/hugo_benchmark/)	 - Benchmark hugo by building a site a number of times
* [hugo check](/commands/hugo_check/)	 - Check content in the source directory
* [hugo config](/commands/hugo_config/)	 - Print the site configuration
* [hugo convert](/commands/hugo_convert/)	 - Convert will modify your content to different formats
* [hugo genautocomplete](/commands/hugo_genautocomplete/)	 - Generate shell autocompletion script for Hugo
* [hugo gendoc](/commands/hugo_gendoc/)	 - Generate Markdown documentation for the Hugo CLI.
* [hugo help](/commands/hugo_help/)	 - Help about any command
* [hugo list](/commands/hugo_list/)	 - Listing out various types of content
* [hugo new](/commands/hugo_new/)	 - Create new content for your site
* [hugo server](/commands/hugo_server/)	 - Hugo runs its own webserver to render the files
* [hugo undraft](/commands/hugo_undraft/)	 - Undraft changes the content's draft status from 'True' to 'False'
* [hugo version](/commands/hugo_version/)	 - Print the version number of Hugo

###### Auto generated by spf13/cobra at 2015-05-21 11:28:49.115941591 +0000 UTC