# Security
Simple Security Tips

Ok, as you may know downloading random files isn't a smart thing to do as you can get a virus! this is a big no no. Virus come in many forms but fall under Malware meaning anything which causes harm to a Computer/ComputerSystem. I Guess Hard-ware would fall under Mal-ware but that’s if someone really wants to go after you or that area.

If you download a file you don’t fully trust, you should do what i usually do. I download the Sysinternal Suite and specifically go after the [ProcessExplorer](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer) tool, I would run ProcExp64.exe as Admin depending on if you got 64/32bit depends but anyways, after running it as admin, I would click Options->VirusTotal.com->Check VirusTotal.com, click accept EULA etc so I can enable VirusTotal scans, any process which hash matches a hash that was flagged for being malware, those Antiviruses will return a report, this will generate an out of where the Malware would have a tag in the format NoAV'sDetected/AllScannedAV's.

![ProcessExplorer](https://news-thewindowsclubco.netdna-ssl.com/wp-content/uploads/2014/01/process-explorer-virustotal.png)

Anything which was red in ProcessExplorer was flagged for having malware, some may be false positives such as if only like 5 engines detected it and it’s an old tool which you trust. If the file is 100% a virus and didn’t popup as a virus well lemme tell you what that means:

Someone crafted a FUD(Fully UnDetectable) malware which is fresh out of production and you have it, you ran it but nothing seems to happen it just hides, you popup ProcessExporer and it says nothing on it, what yado? well, you manually upload the malware on VirusTotal and you lockup that file is a zip or something, you clean out your pc with AV'S, Malwarebytes, ADWCleaner, super antispyware, hitmanpro etc. The file is still running you simply boot into safe mode and kill it and eradicate its existence except for that locked file.

![HitmanPro](https://www.bleepstatic.com/download/screenshots/h/hitmanpro/scan-results.jpg)

you should be safe but you not cuz ur on windows because Microsoft.

Assuming your computer is clean, you unlock that file to upload it to [any.run](https://any.run) so basically what have you done?
you've essentially publicly distributed the 'hackers' malware to a bucket load of free Malware Analysers who will dissect, debug, analyse, decompile and generate source codes on that malware and upload it for everyone to learn. The analysers will then say it’s a malware and now EVERY SINGLE AV on the block will have it in its definition in like a weeks’ time or so!!! which means if you do a rescan on that file, it’s no longer hidden also its encryption patterns will be learned and added to AV's which means if they simply generate another, that also would instantly be detected.

![any.run](https://www.bleepstatic.com/images/news/security/sites/a/any.run/monitor-activity.jpg)

Why go through the effort? someone vulnerable may have a AV which was updated with your newly added malware in it, their AV protected them because of you and now they are safe which means they can keep their money and banking information and password and secrets and photos and ...

Use the built in windows Sandbox tool to run files you don’t trust, use Snadboxie and dump it into a container, dump it in a VM isolated, share it to malware analysts, they will put the 'Hacker' in their place, use an antivirus and DONT DOWNLOAD ANYTHING YOU DONT KNOW ABOUT!!! NO CRACKS, NO MODS, NO HACKS, NO FREE VBUCK GENERATOR, NO KEYGEN, NO WHATEVER, cuz this is the most common way people get malware.

Stay safe lads and peace out!!!
