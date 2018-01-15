## Clone all map repos

To clone everything:

```
$ cd ~/work/maps  ## or wherever you wish to use as a working root folder
$ bash -s < <(curl https://raw.githubusercontent.com/triplea-maps/Project/master/bin/clone_all.sh)
```

Note, new map repos will take time to show up in the github CLI API, perhaps up to a day or more. 

## Bulk Git operations

The _git\_*_ scripts in this folder perform various Git operations in bulk on all map repos.  They are intended to be run from the parent folder where all map repos were cloned.

Note that the scripts do not distinguish between map repos and the `Project` repo.  Therefore, you may wish to ensure the `Project` repo is not cloned into the same folder as the map repos if you don't want it affected by a bulk operation.
