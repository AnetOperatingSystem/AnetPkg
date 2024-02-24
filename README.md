# AnetPkg
<h2>AnetOS package manager</h2>

<h3>Flags:</h3>
<p>-f, --file: Path to package file</p>
<p>-t, --task: Install or remove the package</p>

<h3>How to make your own packages</h3>

<h4>Package contains:</h4>
<p>  pkginfo file - basic information about a package</p>
<p>  exec file - main executable (will be renamed to [package name] and copied in the /usr/bin/)</p>
<p>  desktop file - will be renamed to [package name].desktop and copied to /usr/share/applications/ (optional)</p>
<p>  data folder - will be renamed to package name and copied to /usr/share/ (optional)</p>

<h4>How to make pkginfo file</h4>
<p>1st line - Name of the package</p>
<p>2nd line - Name of the package for system (was previously marked as [package name])</p>
<p>3rd line - Has the package .desktop file? (true/false)</p>
<p>4th line - Has the package data folder (to copy in /usr/share) (true/false)</p>
