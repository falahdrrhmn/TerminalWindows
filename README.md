<div align = "center">
  <h1> Command Terminal Windows </h1>
</div>

<br><br>

## Cara Cek Direktory
```ssh
PS D:\asep> pwd

Path
----
D:\asep
```

## Cara Tau User
```ssh
D:\asep> whoami
desktop-9eo0j5l\lenovo
D:\asep>
```

## Cara Tau Isi Direktory
```ssh
PS E:\> ls


    Directory: E:\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         5/18/2022   5:21 AM                Document
d-----          9/8/2022   6:04 AM                Flashdisk
d-----         9/23/2022   9:59 PM                Linux
d-----         4/26/2022   6:21 AM                Program Files
d-----         9/23/2022   7:17 AM                Software
d-----         5/24/2022   7:22 AM                Temp
d-----         9/22/2022   9:54 PM                VirtualBox
d-----         9/23/2022   8:59 PM                WindowsApps
d-----         4/26/2022   6:22 AM                WpSystem
d-----         9/23/2022   8:58 PM                WUDownloadCache
-a----         9/12/2022  10:24 PM          12288 DumpStack.log


PS E:\>
```

sama yang dihide

```ssh
PS D:\> ls -h


    Directory: D:\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d--hs-          4/5/2021   4:15 PM                $RECYCLE.BIN
d--hs-         9/13/2022   6:28 AM                System Volume Information
-a-hs-          4/5/2021   4:11 PM            520 desktop.ini
-a-hs-         2/22/2022  11:19 AM          12288 DumpStack.log.tmp
```

cara cek direktoi tapi make tree

```ssh
PS E:\Document> tree
Folder PATH listing for volume Data
Volume serial number is E8D1-8FE5
E:.
├───Corel
│   ├───Corel Content
│   │   ├───Fills
│   │   └───Trays
│   ├───Corel PHOTO-PAINT X7 Samples
│   └───CorelDRAW X7 Samples
├───FD MB ARIN
│   ├───album
│   ├───brina's
│   │   └───Saved Pictures
│   ├───game
│   │   ├───build
│   │   │   ├───classes
│   │   │   │   └───com
│   │   │   │       └───zetcode
│   │   │   ├───empty
│   │   │   └───generated-sources
│   │   │       └───ap-source-output
│   │   ├───dist
│   │   ├───nbproject
│   │   │   └───private
│   │   │       └───profiler
│   │   ├───src
│   │   │   └───com
│   │   │       └───zetcode
│   │   └───test
│   ├───oral presentation
│   └───ub 18
│       ├───jurnal
│       │   └───dokmor
│       └───ppt
└───RT
PS E:\Document>
```

## Cara Biar Terminal Bersih
```ssh
PS E:\> ls


    Directory: E:\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         5/18/2022   5:21 AM                Document
d-----          9/8/2022   6:04 AM                Flashdisk
d-----         9/23/2022   9:59 PM                Linux
d-----         4/26/2022   6:21 AM                Program Files
d-----         9/23/2022   7:17 AM                Software
d-----         5/24/2022   7:22 AM                Temp
d-----         9/22/2022   9:54 PM                VirtualBox
d-----         9/23/2022   8:59 PM                WindowsApps
d-----         4/26/2022   6:22 AM                WpSystem
d-----         9/23/2022   8:58 PM                WUDownloadCache
-a----         9/12/2022  10:24 PM          12288 DumpStack.log


PS E:\> clear
```

## Cara Masuk ke Direktori 
```ssh
PS D:\coba> ls


    Directory: D:\coba


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         9/26/2022  10:23 AM                asep


PS D:\coba> cd .\asep\
PS D:\coba\asep>
```


## Cara Kembali ke Direktori Sebelumnya
```ssh
PS D:\coba> cd .\asep\
PS D:\coba\asep> cd ..
PS D:\coba>
```


## Cara Kembali ke Direktori Pucuk
```ssh
PS C:\Users\Lenovo> cd ../..
PS C:\>
```

## Cara Pindah Direktori C ke D dll
```ssh
PS C:\> D:
PS D:\> E:
PS E:\>
```

## Cara Bikin Folder
```ssh
PS D:\coba> ls
PS D:\coba> mkdir asep


    Directory: D:\coba


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         9/26/2022  10:23 AM                asep
```

## Cara Bikin File 
```ssh
PS D:\coba\asep> ls
PS D:\coba\asep> fsutil file createnew coba.py 655366
File D:\coba\asep\coba.py is created
PS D:\coba\asep> ls


    Directory: D:\coba\asep


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         9/26/2022  10:32 AM         655366 coba.py
```

## Cara Ngehapus File atau Folder 

ngehapus file

```ssh
PS D:\coba\asep> ls


    Directory: D:\coba\asep


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         9/26/2022  10:32 AM         655366 coba.py


PS D:\coba\asep> rm .\coba.py
PS D:\coba\asep> ls
PS D:\coba\asep>
```

Ngehapus Folder

```ssh
PS D:\coba> ls


    Directory: D:\coba


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         9/26/2022  10:33 AM                asep


PS D:\coba> rm .\asep\
PS D:\coba> ls
PS D:\coba>
```






