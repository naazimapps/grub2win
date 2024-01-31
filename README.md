# Grub2Win 2.3.8.4

Grub2Win boots native GNU Grub version 2.12 code. Everything is installed to a single 22 MB directory on your Windows C: drive. The install also updates your EFI partition.

Automatically generates config files for PhoenixOS, Android, Ubuntu, Debian, Suse, Fedora, Manjaro, Mint, Clover, POSROG and Windows. You can import Linux config files for Chrome and most other distributions.

You can enter your own custom commands for each menu entry.

Grub2Win began in 2010. It has been downloaded more than 1,200,000 times in 180 countries worldwide.

## Features
• Supports both 64 and 32 bit EFI as well as BIOS firmware.

• Installs to Windows 11, 10, 8, 7 and XP.

• Requires just one directory on the Windows C: drive, about 20 MB disk space.

• Works with all languages. Boot time help is available in 32 languages.

• Simple Windows GUI easily sets up Grub2Win in seconds.

• Lets you set your EFI firmware boot order from within Windows.

• Preview and customize the 9 included graphic background themes. You can also create and customize your own background themes.

• Works with all filesystems including Mac HFS and BTFRS.

• Can search for and boot a partition by it's UUID or label. Supports advanced scripting.

• Works with both GPT and MBR disks - up to 128 primary partitions per drive.

• Supports extremely large (over 40 TB) disks and partitions.

• Automatically generates config files for Windows, PhoenixOS, Android, Ubuntu, Debian, Suse, Fedora, Manjaro, Mint, Clover, POSROG and more.

• Import config files for Chrome and most other Linux distributions.

• Grub customization is done from Windows - Configuration in Linux is not required.

• Includes open source GNU Grub 2.12 boot modules and libraries. Frequent releases and enhancements.

• No adware or spyware - No hassles... It just works.

# Installing Grub2Win
This software modifies low level boot code. Make sure you have proper backups of your boot drive and EFI partition. Note that all Grub2Win executables are digitally signed to ensure that they are genuine.

1) Download the grub2win-Setup.exe file from the Releases tab.
2) Run the exe. This will require administrator access. 
3) Setup will download the most current Grub2Win modules and start the installation. Follow the prompts to select the drive where the \grub2 product directory will be installed (usually C:)
4) Once the setup program has completed successfully, a Delete the setup files checkbox will appear. The setup files are no longer needed. Check the box if you want the setup program to clean up these files.
5) If your machine is running EFI firmware, disable the "Secure Boot" parameter in your firmware settings. This step is not required for machines running BIOS firmware.

# Running Grub2Win
1) Click on the Grub2Win desktop shortcut or go to the C:\grub2 directory and run grub2win.exe. This will require administrator access.

2) The program will prompt you for your graphics preference, Windows boot timeout and grub timeout. You can also set the Grub2 language. The defaults should work fine, but you can change them if desired. Now click "Manage Boot Menu".

3) Add the partitions you want Grub to display at boot time. Detailed instructions will be found by clicking Help.

4) Now click Apply to return to the main Grub2Win screen. When you are satisfied with the options, click OK. Grub2Win will now generate a customized C:\grub2\grub.cfg file with the systems and options you have selected.

5) Shut down and re-boot your machine. On BIOS systems, you can choose to boot either Windows or the Grub2Win menu. On EFI systems, the Grub2Win menu will appear immediately. You can now use the Grub2Win menu to select the OS you would like to boot.

You can run Grub2Win as often as you like to add, change or remove the systems on your boot menu. Many items, including Linux boot parms, icons, timeouts and partition addresses can be tailored. Your choices will preserved across multiple runs.

## More Info: 
Grub2Win is a tool that lets you boot grub2 from your PC's EFI firmware or MBR. It supports Windows 11, 10, 8, 7, Vista and XP. Download this simple Windows program and instructions that help you get grub2 booting quickly. 

All the files for Grub2Win reside on the Windows C: drive. On EFI systems, five small modules are copied to your EFI partition. You don't have to depend on the availability of any Linux partition to boot your computer. 

Grub2 supports extremely large disks (over 40 TB) and GPT partitions allowing you to have many OS images on a single physical disk drive. Grub2 also supports search, advanced scripting and many partition types. Supported filesystems include Btrfs, ext4, ext3, ext2, NTFS, Fat and Mac hfsplus. Booting from CD and USB is also supported by grub2.

Boot time help and messages can be displayed in 30 major languages.

Side note: Yes, i understand that i did not create Grub2Win, but it does not have a good GitHub listing, so I created one.
