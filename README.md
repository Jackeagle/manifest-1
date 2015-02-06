# TeamGlade Testing Repos #

### Installing Repo ###

```bash
# Make a directory where Repo will be stored and add it to the path
$ mkdir ~/bin
$ PATH=~/bin:$PATH

# Download Repo itself
$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo

# Make Repo executable
$ chmod a+x ~/bin/repo
```

### Initializing Repo ###

```bash
# Create a directory for the source files
# This can be located anywhere (as long as the fs is case-sensitive)
$ mkdir WORKSPACE
$ cd WORKSPACE

# Install Repo in the created directory
$ repo init -u https://github.com/SkyLabTeam/manifest -b skylab
```

### Downloading The Repo ###
```bash
# Start by synchronising the source codes to your local drive
$ repo sync -j(No.of jobs you want)
$ For example: repo sync -j8(*Note:This will consume a lot of network data)
```
