# MikaKernel Builder

Meow!


## Usage:

1. Fork this repo.

2. Edit `config.env` :

   |        Arguments        | Note                                              |
   | :---------------------: | ------------------------------------------------- |
   |    ANYKERNEL_SOURCE     | Your Anykernel3 repo                              |
   | ANYKERNEL_SOURCE_BRANCH | Your Anykernel3 branch                            |
   |      KERNEL_SOURCE      | Your kernel source repo                           |
   |  KERNEL_SOURCE_BRANCH   | Your kernel source branch                         |
   |      KERNEL_TARGET      | Your device codename                              |
   |       BUILD_ARGS        | Your kernel compile aguments, separate with space |

3. Click `Run workflow` in `Action->Build MikaKernel`

## Warning: 他妈的先Fork再修改！再开PR我骂人了！

(You must tranlate  these texts into your language and read them before you start to flash you phone!!!)
**注意：请在下载完Action里的AnyKernel3包后把anykernel.sh里第8行的do.devicecheck=1改成do.devicecheck=0以便于刷机（**
