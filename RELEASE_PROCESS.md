# Release Process

1. Build packages from the private `Pic2Pet` source repository.
2. Copy packages to local `downloads/` for staging.
3. Calculate byte sizes and SHA-256 hashes.
4. Update `release.json`.
5. Create a GitHub Release tag, such as `v0.1.0-beta`.
6. Upload packages and `release.json` as release assets.
7. Update the Pic2Pet website manifest URLs to the public release asset URLs.
8. Deploy `website-v2` to Vercel.

Expected GitHub Release asset URL pattern:

```text
https://github.com/hyeon023/Pic2Pet-Releases/releases/download/v0.1.0-beta/Pic2Pet_0.1.0_macOS_x64.zip
```

The final URL must be checked after the GitHub release exists.
