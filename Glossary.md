# Glossary

A list of useful terms for the Linux ecosystem software and hardware.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/213405830-b5e38f04-ff80-4984-8b6d-659691221ca4.png">
<br />
</p>

A

[AppArmor](https://www.apparmor.net/) is an effective and easy-to-use Linux application security system. AppArmor proactively protects the operating system and applications from external or internal threats, even zero-day attacks, by enforcing good behavior and preventing both known and unknown application flaws from being exploited.

[Appvm](https://github.com/jollheef/appvm) is a simple application VMs (hypervisor-based sandbox) based on Nix package manager. It uses one read-only /nix directory for all appvms. So creating a new appvm (but not first) is just about one minute.

[APT (Advanced Package Tool)](https://en.wikipedia.org/wiki/APT_(software)) is a higher-level package management systemtool, that is more commonly used than dpkg as it can fetch packages from remote locations.

[Anaconda](http://fedoraproject.org/wiki/Anaconda) is an OS installer used by Fedora, Red Hat Enterprise Linux (RHEL), CentOS Stream and other Linux distributions.

[Arch Linux](https://archlinux.org/) is an independently developed, x86-64 general purpose GNU/Linux distribution versatile enough to suit any role. Development focuses on simplicity, minimalism, and code elegance.

[Arch Linux User Repository (AUR)](https://aur.archlinux.org/) is a software repository that contains thousands build scripts, for compiling nearly 68,000 installable packages from source using the Arch Linux makepkg application.

[AppImageHub](https://www.appimagehub.com) is a build and distribution service for AppImage applications.

[Awesome](https://awesomewm.org/), a highly configurable, next generation framework window manager for X. 

B

[Btrfs](https://btrfs.wiki.kernel.org/index.php/Main_Page) is a modern copy on write (CoW) filesystem for Linux aimed at implementing advanced features while also focusing on fault tolerance, repair and easy administration.

[Bcachefs](https://bcachefs.org/) is an advanced new filesystem for Linux, with an emphasis on reliability and robustness and the complete set of features one would expect from a modern filesystem. Scalability has been tested to 50+ TB, will eventually scale far higher. 

[Bspwm](https://github.com/baskerville/bspwm), a tiling window manager based on binary space partitioning with a focus on resource efficiency.

[Budgie Desktop](https://getsol.us/solus/experiences/), a feature-rich, modern desktop designed to keep out the way of the user.

C

[Canonical](https://canonical.com) makers of Ubuntu Desktop and Server.

[CBL-Mariner](https://github.com/microsoft/CBL-Mariner) is an internal Linux distribution for Microsoft’s cloud infrastructure and edge products and services. CBL-Mariner is designed to provide a consistent platform for these devices and services and will enhance Microsoft’s ability to stay current on Linux updates.

[CentOS Stream](https://www.centos.org/centos-stream/) is a continuously delivered distro(uses the Fedora OS base) that tracks just ahead of Red Hat Enterprise Linux (RHEL) development, positioned as a midstream between Fedora Linux and RHEL.

[Cinnamon Desktop](https://cinnamon-spices.linuxmint.com/), a Linux desktop which provides advanced innovative features and a traditional user experience.

D

[Debian](https://www.debian.org/) is an operating system and a distribution of Free Software. It is maintained and updated through the work of many users who volunteer their time and effort.

[dpkg(Debian Package)](https://www.digitalocean.com/community/tutorials/dpkg-command-in-linux) is the package management system in Debian and its OS derivatives. 

[DEB](https://www.debian.org/distrib/packages) is a Debian Software Package file used on Debian-based Linux systems such Debian, Ubuntu, Linux Mint, and Pop!_OS.

[DNF(Dandified Packaging Tool)](https://docs.fedoraproject.org/en-US/quick-docs/dnf/) is a software package manager that installs, updates, and removes packages on Fedora and is the successor to YUM (Yellow-Dog Updater Modified). DNF makes it easy to maintain packages by automatically checking for dependencies and determines the actions required to install packages.

[Deepin Desktop](https://www.deepin.org/en/dde/), an elegant, easy to use and reliable domestic desktop environment.

[DXVK](https://github.com/doitsujin/dxvk) is a Vulkan-based translation layer for Direct3D 9/10/11 which allows running 3D applications on Linux using Wine.

E

[EPEL (Extra Packages for Enterprise Linux)](https://docs.fedoraproject.org/en-US/epel/) is an free and open source community-based repository project from the Fedora team which provides 100% high-quality add-on software packages for Linux distribution including RHEL (Red Hat Enterprise Linux) and CentOS Stream.

[EPEL Next](https://docs.fedoraproject.org/epel/epel-about-next/) is an additional repository that allows package maintainers to alternatively build against CentOS Stream. This is sometimes necessary when CentOS Stream contains an upcoming RHEL library rebase, or if an EPEL package has a minimum version build requirement that is already in CentOS Stream but not yet in RHEL. EPEL Next packages have .next appended to the disttag (a disttag of .el8.next for epel8-next) to provide an upgrade path from an EPEL package that was built from the same distgit commit. A package maintainer can rebuild the same commit for both EPEL and EPEL Next and get two different NVRs in koji.

F

[Fedora](https://getfedora.org/) is a polished, easy to use operating system for laptop & desktop computers, with a complete set of tools for developers and makers of all kinds.

[Fedora Server](https://getfedora.org/) is a powerful, flexible operating system that includes the best and latest datacenter technologies. It puts you in control of all your infrastructure and services.

[Fedora ARM](https://arm.fedoraproject.org/) is an initiative to bring versions of Fedora tailored for running on ARM-based systems.

[Fedora Silverblue](https://silverblue.fedoraproject.org/) is a variant of the Fedora Workstation that uses rpm-ostree to provide an immutable OS image with reliable updates and easy rollbacks.

[Fedora Kinoite](https://kinoite.fedoraproject.org/) is an immutable desktop operating system. It aims to be extremely stable and reliable. It also aims to be an excellent platform for developers and for those using container-focused workflows. Kinoite is a variant of the Fedora KDE Spin.

[Fedora CoreOS](https://getfedora.org/coreos?stream=stable) is an automatically-updating, minimal operating system for running containerized workloads securely and at scale.

[Fedora Updates System](https://bodhi.fedoraproject.org/) is a place to create, test, and publish package updates for Fedora.

[FlakeHub](https://flakehub.com/new) is a platform developed by [Determinate Systems](https://determinate.systems/) for discovering and publishing [Nix flakes](https://zero-to-nix.com/concepts/flakes).

[FlatHub](https://flathub.org/) is a build and distribution service for Flatpak applications.

[Fluxbox](https://fluxbox.org/) is a stacking window manager for the X Window System, which based upon Blackbox.

G

[GNOME Desktop](https://www.gnome.org/), is an easy and elegant way to use your computer, GNOME is designed to put you in control and get things done.

H

[Hardware Enablement (HWE)](https://ubuntu.com/kernel/lifecycle) is a Ubuntu LTS enablement stack that provides the newer kernel(currently kernel 6.2 for Ubuntu 22.04 LTS) and X support for existing Ubuntu LTS releases. That stack can be enabled manually, but may also be pre-enabled with an Ubuntu LTS release. The HWE stack can be used by desktop and server systems, as well as cloud or virtual images.

[Heroic](https://heroicgameslauncher.com/) is an Open Source Game Launcher for Linux, Windows and macOS (for both Native and Windows Games using Crossover). 

[Hyprland](https://hyprland.org/) is a [wlroots-based](https://gitlab.freedesktop.org/wlroots) dynamic tiling wayland compositor written in C++ that offers unique features like smooth animations, dynamic tiling and rounded corners.

I

[init](https://en.wikipedia.org/wiki/Init) is parent of all Linux processes with PID or process ID of 1. It is the first process to start when a computer boots up and runs until the system shuts down. **init stands for initialization**. 

[i3-wm](https://i3wm.org/), a tiling window manager for X11.

[Itch.io Store](https://itch.io/app) is an app that lets you effortlessly download and run games and software from itch.io. 

J

K

[KDE Plasma Desktop](https://kde.org), is a beautiful Windows-like desktop that you use to surf the web, keep in touch with colleagues, friends and family, manage your files, enjoy music and videos; and get creative and productive at work.

L

[Lacros (Linux And ChRome OS)](https://chromium.googlesource.com/chromium/src/+/main/docs/lacros.md) is an architecture project to decouple the Chrome browser from the Chrome OS window manager and system UI.

[Linux kernel](https://www.kernel.org/) is the main component of a Linux operating system (OS) and is the core interface between a computer’s hardware and its processes. It communicates between the 2, managing resources as efficiently as possible.

[Linux Mint](https://linuxmint.com/) is a modern, elegant, and comfortable open source operating system(based on Debian and Ubuntu), which is both powerful and easy to use for both new and advanced users.

[LXQt Desktop](https://lxqt.org/),the Lightweight Qt Desktop Environment.

M

[MATE Desktop](https://mate-desktop.org/), is the continuation of GNOME 2 desktop environment. 

[Mesa3D](https://mesa3d.org/) is a 3D graphics library with open-source implementations of OpenGL, OpenGL ES, Vulkan, OpenCL, and more. Mesa 23.1 comes with support for several new Vulkan extensions for the Radeon Vulkan driver (RADV) for AMD Radeon GPUs.

[Micro DNF](https://fedoraproject.org/wiki/Changes/MajorUpgradeOfMicrodnf) is a lightweight C implementation of DNF, designed to be used for doing simple packaging actions when you don't need full-blown DNF and you want the tiniest useful environments possible. Checkout the [Micro DNF GitHub](https://github.com/rpm-software-management/microdnf).

[Mutter](https://gitlab.gnome.org/GNOME/mutter) is a Wayland display server and X11 window manager and compositor library. When used as a Wayland display server, it runs on top of KMS and libinput. It implements the compositor side of the Wayland core protocol as well as various protocol extensions. 

N

[Nala](https://gitlab.com/volian/nala) is a commandline frontend for the APT package manager. 

[NixOS](https://nixos.org/) is a Linux distribution built on top of the [Nix package manager](https://nixos.wiki/wiki/Nix). It has tools dedicated to DevOps and deployment tasks.

[Nix Flake Checker](https://github.com/DeterminateSystems/flake-checker) is a tool from Determinate Systems that performs "health" checks on the flake.lock files in your flake-powered Nix projects. Its goal is to help your Nix projects stay on recent and supported versions of Nixpkgs.

[NixOS Anywhere](https://numtide.github.io/nixos-anywhere/) is a tool that let's you install NixoS everywhere via ssh on a target machine running x86_64 Linux with [kexec](https://man7.org/linux/man-pages/man8/kexec.8.html) support. If you're installing NixOS, the nixos-anywhere (formerly known as nixos-remote) tool allows you to pre-configure the whole process.

[nix2container](https://github.com/nlewo/nix2container) isa tool that provides an efficient container development workflow with images built by Nix: it doesn't write tarballs to the Nix store and allows to skip already pushed layers (without having to rebuild them).

[NixHub.io](https://www.nixhub.io/) is a place to search for over 400,000 granular versions of nix packages.

O

[OSTree](https://ostreedev.github.io/ostree/) is an upgrade system for Linux-based operating systems that performs atomic upgrades of complete filesystem trees. It is not a package system; rather, it is intended to complement them. Checkout the [OSTree GitHub](https://github.com/ostreedev/ostree). 

[Openbox](http://openbox.org/) is a lightweight, powerful, and highly configurable stacking window manager with extensive standards support.

[openSUSE Leap](https://en.opensuse.org/Portal:Leap) is a brand new way of building openSUSE and is new type of a hybrid Linux distribution. Leap uses source from SUSE Linux Enterprise (SLE), which gives Leap a level of stability unmatched by other Linux distributions, and combines that with community developments to give users, developers and sysadmins the best stable Linux experience available. 

[openSUSE Tumbleweed](https://en.opensuse.org/Portal:Tumbleweed) is a pure rolling release version of openSUSE containing the latest "stable" versions of all software instead of relying on rigid periodic release cycles. The project does this for users that want the newest stable software. 

[openSUSE Kubic](https://get.opensuse.org/kubic/) is a multi-purpose Standalone & Kubernetes Container Operating System based on openSUSE MicroOS. Kubic uses kubeadm to provide an easy way of configuring a Kubernetes cluster across multiple machines, while our MicroOS base keeps your operating system updated automatically, with fully atomic rollbacks if required.

[openSUSE MicroOS](https://get.opensuse.org/microos/) is a M icro Service OS providing Transactional (Atomic) Updates upon a read-only btrfs root filesystem. It's designed to host container workloads with automated administration & patching.

[openSUSE Build Service](https://build.opensuse.org/) is the public instance of the Open Build Service (OBS) used for development of the openSUSE distribution and to offer packages from same source for Fedora, Debian, Ubuntu, SUSE Linux Enterprise and other distributions.

[OpenZFS](https://openzfs.org/wiki/Main_Page ) is an open-source storage platform. It includes the functionality of both traditional file systems and volume manager. 

P

[Pacman](https://archlinux.org/pacman/) is a utility which manages software packages in Arch Linux. It uses simple compressed files as a package format, and maintains a text-based package database (more of a hierarchy), just in case some hand tweaking is necessary. 

[PPA(Personal Package Archive)](https://help.launchpad.net/Packaging/PPA) is a set of software repositories that can distribute software and updates directly to Ubuntu users. Create your source package, upload it and Launchpad will build binaries and then host them in your own apt repository.

[PackageKit](https://www.freedesktop.org/software/PackageKit/) is a suite of software applications designed to provide a consistent and high-level front end for a number of different package management systems on Linux. 

[Pantheon Desktop](https://elementary.io/), a GTK desktop based on the GNOME software base maintained by the elementary OS developers.

[Pop!_OS](https://pop.system76.com/) is an operating system(based on [Ubuntu](https://ubuntu.com/)) for STEM and creative professionals who use their computer as a tool to discover and create developed by [System76](https://system76.com/).

[PipeWire](https://pipewire.org) is a server and user space API to deal with multimedia pipelines.It provides a low-latency, graph based processing engine on top of audio and video devices that can be used to support the use cases currently handled by both pulseaudio and JACK.

[Proton](https://github.com/ValveSoftware/Proton) is a compatibility layer based on Wine and additional components for Windows games to run on Linux-based operating systems.

[Pulp](https://pulpproject.org/) is a software repository platform for Fetching, Uploading, Organizing, and Distributing Software Packages.

Q

[Qt](https://www.qt.io/) is a cross-platform application development framework for desktop, embedded and mobile. Supported Platforms include Linux, MacOS, Windows, Android, and iOS.

R

[Red Hat](https://www.redhat.com/en) makers of Red Hat Enterprise Linux and sponsors to the [Fedora Project](https://getfedora.org/).

[Red Hat® Enterprise Linux® (RHEL)](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux) the world's leading enterprise Linux platform.

[RPM Package Manager (RPM)](https://rpm.org/) is a powerful package management system capable of building computer software from source into easily distributable packages installing, updating and uninstalling packaged software querying detailed information about the packaged software, whether installed or not.

[RPM Fusion](https://rpmfusion.org/) is a software repository provides software that the Fedora Project or Red Hat doesn't want to ship. That software is provided as precompiled RPMs for all current Fedora versions and current Red Hat Enterprise Linux or clones versions; you can use the RPM Fusion repositories with tools like yum and PackageKit.

[ROM OSTree](https://ostreedev.github.io/ostree/) is a hybrid image/package system. It combines libostree as a base image format, and accepts RPM on both the client and server side, sharing code with the dnf project; specifically libdnf. Thus bringing many of the benefits of both projects together.

S

[SELinux](https://github.com/SELinuxProject/selinux) is a security enhancement to Linux which allows users and administrators more control over access control.

[Snap Store](https://snapcraft.io/store) is a build and distribution service for Snap applications.

[systemd](https://systemd.io/) is a suite of basic building blocks for a Linux system. It provides a system and service manager that runs as PID 1 and starts the rest of the system. 

[Synaptic Package Manager](https://en.wikipedia.org/wiki/Synaptic_%28software%29) is a graphical package management tool based on APT.

[Steam](https://store.steampowered.com/) is a video game digital distribution service and storefront from Valve.

[Steam OS 3.0](https://store.steampowered.com/steamdeck) is an [immutable](https://en.wikipedia.org/wiki/Immutable_object) Operating System(OS) using the [KDE Plasma](https://kde.org/plasma-desktop) desktop.

[SteamGridDB](https://www.steamgriddb.com/projects) is a huge database where you can download and share custom video game assets and personalize your gaming library.

[SGDBoop](https://www.steamgriddb.com/boop) is a tool that automatically applies assets from SteamGridDB directly to your Steam library with a click of a button, removing the need to download and set them manually. 

[Steam Remote Play Together](https://store.steampowered.com/remoteplay/#together) is a steam service that let's you share your Steam local multi-player games with friends over the internet, for free.

[Steamworks](https://partner.steamgames.com/doc/home) is a free suite of tools available to any developer to use in their game or software on Steam and the Steam Deck. 

[Steam OS 3.0](https://store.steampowered.com/steamdeck) is an [immutable](https://en.wikipedia.org/wiki/Immutable_object) Operating System(OS) using the [KDE Plasma](https://kde.org/plasma-desktop) desktop.

[Simple Wireplumber GUI](https://github.com/dyegoaurelio/simple-wireplumber-gui) is a tool you can easily rename and see the properties of your audio devices if you're running **pipewire** as your audio server and **wireplumber** as it's session and policy manager. [Flatpak version](https://flathub.org/apps/io.github.dyegoaurelio.simple-wireplumber-gui)

[SUSE](https://www.suse.com) makers of SUSE Enterprise Linux.

[System76](https://system76.com) makers of [Pop!_OS](https://pop.system76.com/)

T

U

[Ubuntu](https://ubuntu.com/) is a modern open source operating system on Linux for the enterprise Server, Desktop, Cloud, and IoT developed by Canonical.

[Ubuntu Core](https://ubuntu.com/core) is a secure and minimal version of Ubuntu that is designed for IoT and embedded systems. Ubuntu Core updates itself and its applications automatically using [snap packages](https://snapcraft.io/store) exclusively to create a confined-based system.

[Unity Desktop](https://unity8.io/), a graphical shell for the GNOME desktop environment originally developed by Canonical Ltd.

V

[Valve](https://www.valvesoftware.com/) makers of the Steam, SteamOS, and [Steam Deck](http://www.steamdeck.com/).

[vkd3d-proton](https://github.com/HansKristian-Work/vkd3d-proton) is a fork of VKD3D, which aims to implement the full Direct3D 12 API on top of Vulkan. The project serves as the development effort for Direct3D 12 support in [Proton](https://github.com/ValveSoftware/Proton).

W

[Warpinator](https://github.com/linuxmint/warpinator) is a free, open-source tool for sending and receiving files between computers that are on the same network.

[Waydroid](https://github.com/waydroid/waydroid) is a container-based approach to boot a full Android system on a regular Linux system.

[WirePlumber](https://pipewire.pages.freedesktop.org/wireplumber/) is a modular session / policy manager for [PipeWire](https://pipewire.org/) and a GObject-based high-level library that wraps PipeWire’s API, providing convenience for writing the daemon’s modules as well as external tools for managing PipeWire. 

X

[XFCE Desktop](https://xfce.org/), a lightweight desktop environment for UNIX-like operating systems. 

Y

[YaST](https://yast.opensuse.org/) is a installation and configuration tool for openSUSE and the SUSE Linux Enterprise distributions. It features an easy-to-use interface and powerful configuration capabilities.

[YUM (Yellowdog Updater, Modified)](https://www.digitalocean.com/community/tutorials/what-is-yum) is a software package-management utility for Linux operating system using the RPM Package Manager.

Z

[ZFS](https://docs.oracle.com/cd/E19253-01/819-5461/zfsover-2/) is an enterprise-ready open source file system and volume manager with unprecedented flexibility and an uncompromising commitment to data integrity.

[Zypper](https://software.opensuse.org/package/zypper) is a command line package manager which makes use of libzypp. It provides functions like repository access, dependency solving, package installation, etc. Zypper repositories are similar to the ones used in YaST, which also makes use of libzypp.
