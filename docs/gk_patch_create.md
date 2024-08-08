## gk patch create

Share changes in your commits or WIP with other developers generating a Cloud Patch

### Synopsis

The Cloud Patches preview feature enables you to easily share changes with other developers by creating a Cloud Patch from your WIP and sharing the generated link with your teammates.

Note: Cloud Patches are securely stored by GitKraken, and anyone with access to the link and a GitKraken account can view the code for now. More permissions and controls are coming soon.
For security information - https://help.gitkraken.com/cli/security/
For additional information about Cloud Patches - https://github.com/gitkraken/gk-cli#cloud-patches

```
gk patch create [flags]
```

### Options

```
  -d, --description string        Provide the description for the patch (optional)
      --from-commit stringArray   Provide the commit or commits to create the patch from
      --from-head                 Create the patch from HEAD (staged and not staged files)
      --from-staged               Create the patch from staged files
      --from-stash string         Create the patch from a selected stash
      --from-wip                  Create the patch from WIP (not staged)
  -h, --help                      help for create
  -t, --title string              Provide the title for the patch (required)
```

### SEE ALSO

* [gk patch](gk_patch.md)	 - Interact with GitKraken's Cloud Patches

###### Auto generated by spf13/cobra on 8-Aug-2024