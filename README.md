# Remote language packs

Upload the ten `*.json.gz` files in this folder to the root of the public GitHub repository:

```text
https://github.com/Abhay0324/21-days-language-packs
```

The public URLs must keep these exact file names, for example:

```text
https://raw.githubusercontent.com/Abhay0324/21-days-language-packs/main/challenges_hi.json.gz
https://raw.githubusercontent.com/Abhay0324/21-days-language-packs/main/challenges_ja.json.gz
```

The download URL is configured in the root `gradle.properties` file:

```properties
LANGUAGE_PACK_BASE_URL=https://raw.githubusercontent.com/Abhay0324/21-days-language-packs/main
```

English remains bundled in the app as the offline fallback.
