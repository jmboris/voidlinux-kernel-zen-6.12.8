# voidlinux-kernel-zen-6.12.8
Kernel 6.12.8 with patch zen , template for VoidLinux


![image](https://github.com/user-attachments/assets/5b815abe-9f2e-4d31-bb01-68dab60b1c6b)

This repository contains the xsrc folder necesary to build the linux 6.12.6-zen and linux6.12.6-zen-headers, as well the template to install kernel 6.12.6 an the path for it from zen-kernel repository.


## NOTE

If you **ONLY** want to use the template you need to download the patch from zen repository (https://github.com/zen-kernel/zen-kernel/releases/tag/v6.12.8-zen1) , place it in the patches folder and create the symbolic link linux6.12.6-zen-headers.
```bash
Linux6.12.8-zen
├── files
│   ├── arm64-dotconfig
│   ├── currentx86_64-dotconfig
│   ├── i386-dotconfig
│   ├── mv-debug
│   └── x86_64-dotconfig
├── patches
│   ├── fix-musl-btf-ids.patch
│   ├── fix-musl-objtool.patch
│   ├── fixdep-largefile.patch
│   ├── linux-v6.12.6-zen1.patch
│   └── x13s-camera.patch
└── template
```

You need to create the symbolik link :

`ln -s linux6.12.8-zen/ linux6.12.8-zen-headers`

![Captura de pantalla_20250104_134039](https://github.com/user-attachments/assets/286ceabd-ff31-4739-bc59-b465c93e5e7f)

#VOID MANUAL
https://github.com/void-linux/void-packages/blob/master/Manual.md

