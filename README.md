# fdroid
This repository hosts an [F-Droid](https://f-droid.org/) repo for patched android apps. This allows you to install and update apps very easily.

### Apps

<!-- This table is auto-generated. Do not edit -->
| Icon | Name | Description | Version |
| --- | --- | --- | --- |
| <a href="https://github.com/gopi487krishna/obsidian-apk-patch"><img src="fdroid/repo/icons/md.obsidian.197.png" alt="Obsidian Molten icon" width="36px" height="36px"></a> | [**Obsidian Molten**](https://github.com/gopi487krishna/obsidian-apk-patch) | Patched version of obsidian apk with support for self signed certificates | 1.8.10 (197) |
<!-- end apps table -->

### How to use
1. At first, you should [install the F-Droid app](https://f-droid.org/), it's an alternative app store for Android.
2. Now you can copy the following [link](https://raw.githubusercontent.com/xarantolus/fdroid/main/fdroid/repo?fingerprint=080898ae4309aeceb58915e43a4b7c4a3e2cda40c91738e2c02f58339ab2fbd7), then add this repository to your F-Droid client:

    ```
    https://gopi487krishna.github.io/fdroidgk/fdroid/repo
    ```

    Alternatively, you can also scan this QR code:

    <p align="center">
      <img src=".github/qrcode.png?raw=true" alt="F-Droid repo QR code"/>
    </p>

3. Open the link in F-Droid. It will ask you to add the repository. Everything should already be filled in correctly, so just press "OK".
4. You can now install my apps, e.g. start by searching for "Notality" in the F-Droid client.

Please note that some apps published here might contain [Anti-Features](https://f-droid.org/en/docs/Anti-Features/). If you can't find an app by searching for it, you can go to settings and enable "Include anti-feature apps".

### For developers
If you are a developer and want to publish your own apps right from GitHub Actions as an F-Droid repo, you can fork/copy this repo and see  [the documentation](setup.md) for more information on how to set it up.

### [License](LICENSE)
The license is for the files in this repository, *except* those in the `fdroid` directory. These files *might* be licensed differently; you can use an F-Droid client to get the details for each app.
