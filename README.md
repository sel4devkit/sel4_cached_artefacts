# seL4 Cached Artefacts

This repository holds pre-built arfefacts (tools and libraries) for use when building seL4.

To use these artefacts clone them to the build environment and set the environment variable SEL4_CACHE_DIR to point at the cloned location prior to building.

```bash
mkdir /host/cache_directory
cd /host/cache_directory
git clone https://github.com/sel4devkit/sel4_cached_artefacts
export SEL4_CACHE_DIR=/host/cache_directory
```
