a collection of apks that don't already have up to date distribution on fdroid. can be built into a rom by including the following in a `manifest.xml`

```
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	  <project name="crobibero/android-prebuilts" path="prebuilts/crobibero" remote="github" revision="master" />
</manifest>
```

