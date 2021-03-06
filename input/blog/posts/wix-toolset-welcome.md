---
LayoutRef: blog
Title: Welcoming WiX Toolset to the .NET Foundation
Author: 
Published: 2016-05-04 18:14:00.0000000
---
<p>The <a href="http://wixtoolset.org/">WiX toolset </a>project holds a special place in my heart. I've built many installers in my time using the toolset and had nothing but positive interactions with the community as a developer, but also the <a href="http://wixtoolset.org/">WiX toolset</a>&nbsp;was one of the very first open source projects that came out of Microsoft. <a href="http://robmensching.com/">Rob </a>and his team blazed a trail that we <g class="gr_ gr_47 gr-alert gr_spell gr_run_anim ContextualSpelling" id="47" data-gr-id="47">where</g> then able to follow with .NET and so many other open source projects <g class="gr_ gr_50 gr-alert gr_spell gr_run_anim ContextualSpelling multiReplace" id="50" data-gr-id="50">afterwards</g>. That is why I'm especially thrilled that now I get to work more with the project as <a href="http://robmensching.com/blog/posts/2016/5/4/wix-toolset-joins-the-.net-foundation/">they have decided to make the .NET Foundation their home</a>.</p>

<p>For those few people who have been under a rock for the past decade and didn't know about it, the WiX toolset lets developers create installers for Windows Installer, the Windows installation engine used by many traditional desktop applications and also Windows Server installation mechanisms. The core of WiX is a set of build tools that build Windows Installer packages using the same build concepts as the rest of your product: source code is compiled and then linked to create executables; in this case .exe setup bundles, .msi installation packages, .msm merge modules, and .msp patches. The WiX command-line build tools work with any automated build system. Also, MSBuild is supported from the command line, there is an excellent&nbsp;Visual Studio integration along with links into Team Build / VSTS.</p>

<p>WiX includes several extensions that offer functionality beyond that of Windows Installer. For example, WiX can install IIS <g class="gr_ gr_35 gr-alert gr_spell gr_run_anim ContextualSpelling ins-del" id="35" data-gr-id="35">web sites</g>, create SQL Server databases, and register exceptions in the Windows Firewall, among others. It's used by every single .NET development shop I know.</p>

<p>With Burn, the WiX bootstrapper, you can create setup bundles that install prerequisites like the .NET Framework making it easier for end users to run <g class="gr_ gr_44 gr-alert gr_gramm gr_run_anim Grammar multiReplace" id="44" data-gr-id="44">your</g> .NET based applications. You can also use it to create installers for applications created using other runtimes. I once quickly knocked up an installer using the WiX toolset that installed Java + Eclipse + Team Explorer Everywhere along with demo projects, test data and demo scripts just to make my demos quicker to get set up back when I was looking after the Eclipse tooling in Microsoft. Burn also lets you download packages or combine them into a single downloadable .exe.</p>

<p>The WiX SDK includes managed and native libraries that make it easier to write code that works with Windows Installer, including custom actions in both C# and C++. &nbsp;If you haven't tried it yet then what are you waiting for - <a href="http://wixtoolset.org/">give it a go now</a>. &nbsp;If there is any functionality that you want to add then <a href="http://wixtoolset.org/development/">get involved</a>&nbsp;with the amazing community and contribute.</p>

<p>May the 4th be with you. Always.</p>

<p>Martin Woodward<br />Executive Director.</p>
