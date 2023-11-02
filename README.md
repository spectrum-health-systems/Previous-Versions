# Abatab Previous Versions

In order to keep the Abatab repositories clean, previous versions of Abatab development and Community Releases are stored here.

This is the process to archive previous versions:

1. Download the branch from GitHub
2. Extract the .zip file
3. To keep the archive file small enough to store on GitHub, the following non-critical directories are removed (if they exist):
    - `dependencies/`
    - `samples/`
    - `scripts/`
    - `src/bin/`
    - `src/obj/`
    - `tools/`
    - `test/`

4. Recompress as a .7z archive

Each branch was downloaded directly from GitHub, extracted, then compressed back into a .7z archive to save space.

For branches that ended up larger than 100MB (which is too large to be stored in a GitHub repository), files that are not required were removed.

