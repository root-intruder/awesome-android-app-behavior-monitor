## NOTE:
This repository was anynomized for review. After the review, this repository will be publicly available on Github and the links in the paper will be updated.

# Android App Behavior Monitoring / Hooking Tools

|Tool |Available|Last Active|License|APK Repacking|Root Req.|Sandbox|Device Type|Dyn. Hooking|Hooking Scope|Instrumentation|
|-------|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|ANANAS <sup>[[pub](https://ieeexplore.ieee.org/document/6657309)]</sup>|❌|2013|❌|❌|❌|❌|emulator|❌|sys & usr|passive|
|[APIMonitor](https://github.com/pjlantz/droidbox)|✔open-source|2015|GPL2|✔|❌|❌|emulator|❌|sys & usr|passive|
|AppCage <sup>[[pub](https://dl.acm.org/doi/10.1145/2714576.2714598)]</sup>|❌|2015|❌|❌|❌|✔|device & emulator|❌|sys & usr|active|
|[Aurasium](https://github.com/xurubin/aurasium) <sup>[[pub](https://www.usenix.org/conference/usenixsecurity12/technical-sessions/presentation/xu_rubin)]</sup>|✔open-source|2015|GPL3|✔|❌|❌|device & emulator|❌|sys & usr|active|
|[AppsPlayground](https://bit.ly/appsplayground) <sup>[[pub](https://dl.acm.org/doi/10.1145/2435349.2435379)]</sup>|✔open-source|2014|❌|❌|❌|❌|emulator|❌|sys & usr|passive|
|[ARTDroid](https://github.com/steelcode/art-hook-vtable-gsoc15) <sup>[[pub](http://ceur-ws.org/Vol-1575/paper_10.pdf)]</sup>|✔open-source|2015|GPL2|❌|✔|❌|device & emulator|❌|sys & usr|active|
|[ARTist](https://github.com/Project-ARTist) <sup>[[pub](https://ieeexplore.ieee.org/document/7961998)]</sup>|✔open-source|2019|Apache|✔|✔|❌|device & emulator|❌|sys & usr|active|
|[Aurasium](https://github.com/xurubin/aurasium) <sup>[[pub](https://www.usenix.org/conference/usenixsecurity12/technical-sessions/presentation/xu_rubin)]</sup>|✔open-source|2015|GPL3|✔|❌|❌|device & emulator|❌|sys|active|
|[Boxify](https://web.archive.org/web/20201018033341/https://github.com/monojo/Box) <sup>[[pub](https://dl.acm.org/doi/10.5555/2831143.2831187)]</sup>|❌|2016|❌|❌|❌|✔|device & emulator|✔|sys & usr|active|
|CopperDroid <sup>[[pub](https://www.researchgate.net/publication/300925104_CopperDroid_Automatic_Reconstruction_of_Android_Malware_Behaviors)]</sup>|❌|2018|❌|❌|❌|❌|emulator|❌|sys|passive|
|[CydiaSubstrate](http://www.cydiasubstrate.com/)|❌|2014|❌|❌|✔|❌|device & emulator|✔|usr|active|
|[DroidBox](https://github.com/pjlantz/droidbox)|✔open-source|2015|Apache|❌|❌|❌|modified OS|❌|sys|passive|
|[DroidScope](https://github.com/decaf-project/Droidscope) <sup>[[pub](https://dl.acm.org/doi/10.5555/2362793.2362822)]</sup>|✔open-source|2018|GPL3|❌|❌|❌|emulator|❌|sys|passive|
|[Frida](https://github.com/frida/frida)|✔open-source|2021|wxWin|✔|✔|❌|device & emulator|✔|sys & usr|active|
|[Introspy](https://isecpartners.github.io/Introspy-Android/)|❌|2014|❌|❌|✔|❌|device & emulator|✔|usr|active|
|Malton <sup>[[pub](https://dl.acm.org/doi/10.5555/3241189.3241213)]</sup>|❌|2017|❌|❌|❌|✔|device & emulator|❌|sys|passive|
|MobileSandbox <sup>[[pub](https://dl.acm.org/doi/10.1145/2480362.2480701)]</sup>|✔open-source|2015|Apache|❌|❌|❌|modified OS|❌|sys|passive|
|Ninja <sup>[[pub](https://dl.acm.org/doi/10.5555/3241189.3241193)]</sup>|❌|2017|❌|❌|❌|❌|device|✔|sys|passive|
|Njas <sup>[[pub](https://dl.acm.org/doi/10.1145/2808117.2808122)]</sup>|❌|2015|❌|❌|❌|✔|device & emulator|❌|sys|active|
|[ptrace/strace](https://github.com/strace/strace)|✔open-source|2020|GPL2|❌|✔|❌|device & emulator|✔|sys|active|
|Retroskeleton <sup>[[pub](https://dl.acm.org/doi/10.1145/2462456.2464462)]</sup>|❌|2013|❌|✔|❌|❌|device & emulator|❌|sys & usr|active|
|[Riru](https://github.com/RikkaApps/Riru)|✔open-source|2020|❌|❌|✔|❌|device & emulator|✔|usr|active|
|Ronin <sup>[[pub](https://www.researchgate.net/publication/328611051_Android_Hooking_Revisited)]</sup>|✔open-source|2017|MIT|✔|❌|❌|device & emulator|✔|sys & usr|active|
|[SandHook](https://github.com/Casperinous/Ronin)|✔open-source|2020|anti996|❌|✔|❌|device & emulator|✔|usr|active|
|SIF <sup>[[pub](https://dl.acm.org/doi/10.1145/2462456.2465430)]</sup>|❌|2013|❌|✔|❌|❌|device & emulator|❌|sys|active|
|[SmartDroid](https://github.com/boyliang/SmartDroid) <sup>[[pub](https://dl.acm.org/doi/10.1145/2381934.2381950)]</sup>|✔open-source|2013|❌|❌|❌|❌|emulator|❌|sys & usr|active|
|[StaDynA](https://github.com/zyrikby/StaDynA) <sup>[[pub](https://dl.acm.org/doi/10.1145/2699026.2699105)]</sup>|❌|2015|❌|❌|❌|❌|modified OS|❌|sys|passive|
|[TaintDroid](https://github.com/TaintDroid) <sup>[[pub](https://dl.acm.org/doi/10.5555/1924943.1924971)]</sup>|✔open-source|2013|Apache|❌|❌|❌|modified OS|❌|sys|passive|
|TraceDroid <sup>[[pub](https://www.researchgate.net/publication/270576401_Dynamic_Analysis_of_Android_Malware)]</sup>|❌|2013|❌|❌|❌|❌|modified OS|❌|sys|passive|
|UpDroid <sup>[[pub](https://dl.acm.org/doi/10.1145/3212480.3212504)]</sup>|❌|2018|❌|❌|❌|❌|device & emulator|❌|events|passive|
|[VetDroid](https://github.com/Xbalien/vetdroid) <sup>[[pub](https://www.researchgate.net/publication/326054920_Towards_Dynamically_Monitoring_Android_Applications_on_Non-rooted_Devices_in_the_Wild)]</sup>|✔open-source|2016|❌|❌|❌|✔|modified OS|❌|sys|passive|
|[VirtualHook](https://github.com/PAGalaxyLab/VirtualHook)|✔open-source|2020|❌|❌|❌|✔|device & emulator|❌|sys|active|
|[Xposed](https://github.com/rovo89/Xposed)|✔open-source|2018|❌|❌|✔|❌|device & emulator|✔|sys|active|
|[YAHFA](https://github.com/PAGalaxyLab/YAHFA)|✔open-source|2020|GPL3|❌|✔|✔|device & emulator|✔|sys & usr|active|
   	
