# Robot Core manual installation and execution

Robot Core is a cross-platform version of Astro Robot

**Ubuntu installation**

1. Open Ubuntu Store

![](<../../.gitbook/assets/image (217).png>)

&#x20; 2\. Install .NET Runtime 5.0

![](<../../.gitbook/assets/image (268).png>)

3\.  Execute

```
sudo apt install -y libgdiplus libc6 libc6-dev
sudo apt install -y fontconfig libharfbuzz0b libfreetype6
```

4\. Open robot folder and allow file Astro.Robot to be executable

![](<../../.gitbook/assets/image (265).png>)

&#x20; 5\. Open WebDriver folder and allow all files to be executable

![](<../../.gitbook/assets/image (232).png>)

&#x20; 6\.  Start robot using terminal. For example:

```
./Astro.Robot instantStart noOrchestrator "projPath=/home/astro/Downloads/Core" "seqPath=/home/astro/Downloads/Core/Main.ltw"

```
