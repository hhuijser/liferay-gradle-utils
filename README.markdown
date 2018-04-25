# Liferay Gradle Utilities

## Some Features

### Add missing `.lfrbuild-portal` marker files

```posh
.\gradlew addPortalBuild '-PdirName=com-liferay-commerce-private'
```

### Fix JSP Compilation Classpaths

```posh
.\gradlew fixTestClasspaths '-PmodulesRootDir=s:/lr/com-liferay-commerce-private' '-PtaskName=compileJSP'
```

## License

[UNLICENSE](./UNLICENSE)