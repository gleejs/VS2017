# VS2017
Visual Studio 2017
Creating an offiline installation

https://docs.microsoft.com/en-us/visualstudio/install/create-a-network-installation-of-visual-studio


Silent install for VS2017

https://docs.microsoft.com/en-us/visualstudio/install/use-command-line-parameters-to-install-visual-studio
https://docs.microsoft.com/en-us/visualstudio/install/workload-component-id-vs-enterprise



VS.exe --add Microsoft.VisualStudio.Workload.NetCoreTools --add Microsoft.VisualStudio.Workload.NetWeb;--includeRecommended --add Microsoft.VisualStudio.Workload.Universal;--includeRecommended --add  Microsoft.VisualStudio.Component.TestTools.MicrosoftTestManager;--includeRecommended --passive --norestart

Vs.exe --add Microsoft.VisualStudio.WorkloadNetWeb --includeRecommended --passive

VS.exe --add Microsoft.VisualStudio.Workload.NetCoreTools
 --includeRecommended --passive
