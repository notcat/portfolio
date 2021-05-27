portfolio.txt

## Source VTF format modifier

When you are put on board with a new team, you get the pleasure of fixing what the people before you did. I ran into an interesting scenario where I had hundreds of VTF materials for models on a Source Engine game, but these files were using the DXT3 compression format over the DXT5 compression format, making the filesize 3x the size it should be. The images did not store any transparency so the higher bit format was unnecessary.

```
image of dxt3 vs dxt5 filesize
```
```
image of recursive folder searching and progress bar
```

## Sourcepawn CI/CD Enviornment

Having good DevOps makes developing for communitys and companies many times easier for the developers and allows increased collaboration and productivity, which is why I spent the agregious task of setting it up for my community. Using github actions, I compile each new versions of my plugin on each commit and automatically deploy the compiled plugin to my ftp server. Through bash scripts the server can automatically detect new plugin changes and reload the plugins to have seamless code to product synergy.

When a commit is stable enough for release, merging it to the master branch will run the CI/CD Github Actions and will be created as a release, the live production server will pull the release automatically and deploy it with a live reload to have no downtime on the server with players currently playing on it.

```
image of github actions
```
```
image of my balls
```
