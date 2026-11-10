# AK Developer — APK Releases

This public repository is used only to distribute Android APK builds for the AK Developer website.

- Website: https://akdev.is-a.dev
- APK releases: https://github.com/alidostkhaskheli49-commits/AK-Developer-Releases/releases

## Publishing a build

1. Open the **Releases** page and choose **Draft a new release**.
2. Create a tag such as `v1.0.0`.
3. Attach the APK file as a release asset (do not commit APK binaries to the Git repository).
4. Publish the release and keep this repository public.
5. Copy the APK asset's direct download URL.
6. In the AK Developer admin panel, open the relevant project's **APK & versions** section, paste the asset URL, enter the version label and optional release notes, then choose **Verify & register APK**.

Only published release assets from this repository are accepted by the website. Keep the source-code repository private; do not upload source code, secrets, credentials, or private customer data here.

Removing a version from the website admin panel removes only its website metadata. Delete the corresponding GitHub Release asset separately if it should no longer be publicly downloadable.
