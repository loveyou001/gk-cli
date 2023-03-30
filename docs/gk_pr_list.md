## gk pr list

Display every open pull request from the repositories within a workspace

```
gk pr list [flags]
```

### Examples

```
  
  $ gk pr list

  
  $ gk pr list --title pr_Title

  
  $ gk pr list origin --title pr_Title --opened-by userName --created-after 20-01-2022
```

### Options

```
      --all                     Filter pull requests shown by the title
  -a, --created-after string    Filter pull requests created after a certain date (DD-MM-YYYY)
  -b, --created-before string   Filter pull requests created before a certain date (DD-MM-YYYY)
  -h, --help                    help for list
  -o, --opened-by string        Filter pull requests by who has opened them
  -t, --title string            Filter pull requests shown by the title
```

### SEE ALSO

* [gk pr](gk_pr.md)	 - Interact with pull requests

###### Auto generated by spf13/cobra on 30-Mar-2023