# Clone dockerhub repositories

This script copies every image and tag from one dockerhub repository to another.

# Usage

First set source / destination environment variables:

```bash
export SRC_USERNAME=src_user
export SRC_PASSWORD=src_pass
export SRC_REPOSITORY=src
export DST_USERNAME=dst_user
export DST_PASSWORD=dst_pass
export DST_REPOSITORY=dst
```

Then run scropt:

```
./dockerhub_clone
```
