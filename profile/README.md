# NervOS

NervOS is a custom Android ROM based on LineageOS 23.2 and Android 16.

The project is currently in early bring-up. Source organization, product
identity, and core application branding are being established before the first
device build is validated.

## Source layout

| Repository | Purpose |
| --- | --- |
| `Manifest` | Android source manifest and NervOS project mappings |
| `android_vendor_nerv` | Product configuration, versioning, and build identity |
| `android_packages_apps_Settings` | Settings fork with NervOS About phone branding |

Device trees, proprietary vendor files, and kernels are maintained separately
from the platform manifest.

## Base

- Android 16
- LineageOS 23.2
- NervOS 1.0

This organization is private while the initial ROM bring-up is in progress.
