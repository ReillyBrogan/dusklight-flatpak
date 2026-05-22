# TODO:
- Merge updates to appId things (https://github.com/TwilitRealm/dusklight/pull/1718)
- Add actual support to aurora/dusklight to check for the deps that we currently have to patch in
- Add a script to automate updating dawn along with the correct submodule commits
- Adjust the dusklight cmake so that it installs the binary to /bin and resources to /share
- Directly install .desktop/icons in the dusklight cmake so the post-install is unnecessary
- Build libnod with system deps for compression libs (bring binary size down)
