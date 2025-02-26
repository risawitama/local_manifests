----------------

    git clone https://github.com/risawitama/local_manifests.git .repo/local_manifests
----------------

    repo sync --force-sync -j$(nproc -all) --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken
