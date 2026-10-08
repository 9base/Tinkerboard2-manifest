> [!NOTE]
> **9base status: Preserved** · **Lifecycle: archived reference copy.**
>
> This is a historical fork of [TinkerBoard2/manifest](https://github.com/TinkerBoard2/manifest).
> 9base retains it for provenance and reference and does not actively maintain it.
> Upstream source and inherited authorship remain attributed to their original contributors.

# Tinkerboard2-manifest — 9base preservation notes

## Role and branch index

This repository coordinates the vendor's Tinker Board 2 Debian/Linux source
checkout using Repo manifests. The default `main` branch originally contains
only the small upstream README retained below. The actual XML manifests live
on [linux4.19-rk3399-debian10](https://github.com/9base/Tinkerboard2-manifest/tree/linux4.19-rk3399-debian10),
including [default.xml](https://github.com/9base/Tinkerboard2-manifest/blob/linux4.19-rk3399-debian10/default.xml). That manifest uses revision
`linux4.19-rk3399-debian10` and the `https://github.com/TinkerBoard2/` remote.

The 8 October 2026 audit found `main` identical to same-named upstream and the
Linux release branch 0 ahead / 1 behind. No account-linked Zaryob-authored
commit was returned on either exposed branch; this is not an exhaustive test
of every possible unlinked historical author identity. No distinct current
9base integration purpose was established. Manifest contents and the default
branch are retained as found, and no full BSP build has been validated here.

## Tinker Board 2 platform family

| Layer | Preserved 9base repository |
| --- | --- |
| Linux checkout manifests | [Tinkerboard2-manifest](https://github.com/9base/Tinkerboard2-manifest) |
| Linux kernel | [Tinkerboard2-kernel](https://github.com/9base/Tinkerboard2-kernel) |
| U-Boot bootloader | [Tinkerboard2-uboot](https://github.com/9base/Tinkerboard2-uboot) |
| Buildroot build system | [Tinkerboard2-buildroot](https://github.com/9base/Tinkerboard2-buildroot) |
| Debian/rootfs scripts | [Tinkerboard2-debian](https://github.com/9base/Tinkerboard2-debian) |
| Rockchip firmware and loaders | [Tinkerboard2-rkbin](https://github.com/9base/Tinkerboard2-rkbin) |
| Poky/OpenEmbedded/BitBake | [yocto-poky](https://github.com/9base/yocto-poky) |
| Android checkout manifests | [Tinkerboard2Android-manifest](https://github.com/9base/Tinkerboard2Android-manifest) |

The [Linux release manifest](https://github.com/9base/Tinkerboard2-manifest/blob/linux4.19-rk3399-debian10/default.xml) explicitly names the kernel, U-Boot,
Buildroot, Debian, rkbin and yocto-poky components. Its remote still points to
`TinkerBoard2`, not these 9base forks; it does not automatically select 9base's
historical Debian fix. This family is only a retained subset of the vendor's
larger source graph, not a self-contained complete BSP checkout.

The Android manifests concern the same board family but target a separate
`TinkerBoard2-Android` source graph; they do not establish use of these 9base
Linux components.

## Historical note

These preservation notes were reconstructed on **8 October 2026** from the
repository tree, exposed branches, commit history and upstream comparisons.
They are new archival documentation, not evidence that this explanation existed
at the historical fork date. The original reason for retention or any deployment
is not established by the inspected record. No contemporary build, support or
upstream synchronization commitment is implied.

---

## Original upstream README (preserved)

# manifest