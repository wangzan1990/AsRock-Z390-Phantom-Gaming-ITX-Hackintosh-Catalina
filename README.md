# AsRock-Z390-Phantom-Gaming-ITX-Hackintosh-Catalina

![tonymac](https://user-images.githubusercontent.com/6239630/73441762-8d9eb300-4364-11ea-8566-80372069032c.jpg)

It's my version of EFI folders for booting Catalina 10.15.1<br>
I not reccomend to update Catalina to 10.15.2 because in my case eGPU lost half performace.


Support&Remote install on Telegram App:<br> 
![t_logo](https://user-images.githubusercontent.com/6239630/73442546-179b4b80-4366-11ea-9a1e-1e96102aa86c.png) @hackintosh_by 

<h3>Catalina 10.15.1 &  Native NVRAM</h3>

<h2>Hardware</h2>
<ul>
<li>Intel i7 8700K</li>
<li>Asrock Z390 Phantom-Gaming ITX/ac . BIOS P4.2</li>
<li>Sapphire Radeon RX5700 </li>
<li>32Gb RAM</li>
<li>NVME SSD Samsung 970 EVO Plus (latest firmware)</li>
<li>Wi-Fi NGFF-M2.KEY.E BCM94360CS2 – From Macbook Pro</li>
</ul>

<h2>Clover – all works – sleep and TB3 and USB-C.</h2>
<h2>OpenCore – USB-C and TB3 works but sleep not. Problem with wake up.</h2>

![Screen Shot 2020-01-23 at 01 55 02](https://user-images.githubusercontent.com/6239630/73441672-6811a980-4364-11ea-9a9d-8fa5576e271b.png)

<h2>Clover v.5103</h2>
<h3>UEFI Drivers</h3>
<ul>
<li>ApfsDriverLoader-64.efi</li>
<li>AptioMemoryFix-64.efi</li>
<li>VBoxHfs.efi</li>
<li>VurtualSMC.efi</li>
</ul>

<h3>Kexts</h3>
<ul>
<li>ApfsDriverLoader-64.efi</li>
<li>AptioMemoryFix-64.efi</li>
<li>VBoxHfs.efi</li>
<li>VurtualSMC.efi</li>
</ul>

<h3>ACPI Patches</h3>
<ul>
<li>IntelMausiEthernet.kext</li>
<li>AppleALC.kext</li>
<li>USBports.kext</li>
<li>Lilu.kext</li>
<li>VurtualSMC.kext</li>
</ul>

<h2>Tests&Benchmarks</h2>

![Screen Shot 2020-01-30 at 03 11 24](https://user-images.githubusercontent.com/6239630/73441975-01d95680-4365-11ea-85fb-dfe8fc4ab023.png)

