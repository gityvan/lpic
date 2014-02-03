102.5 Use RPM and YUM package management
----------------------------------------

Summary
-------

- Install, re-install, upgrade and remove packages using RPM and YUM.
- Obtain information on RPM packages such as version, status, dependencies, integrity and signatures.
- Determine what files a package provides, as well as find which package a specific file comes from.
- Yum, Yumdownloader
- rpm, rpm2cpio


Yum, Yumdownloader
------------------

### YUM repositories ###

<pre><code>/etc/yum.conf                    # Config file
/etc/yum.repos.d/                # Repositories 
</code></pre>

### YUM ###

<pre><code>yum install pandoc               # Install package pandoc
yum remove  pandoc               # Remove package pandoc
yum reinstall pandoc             # Reinstall package

yum search markdown              # Search for package markdown

yum list gcl                     # Short package information of gcl
yum info gcl                     # Information of package gcl
yum list all                     # List of installed and available packages
yum list installed               # Installed packages
yum list available               # Available packages in yum repositories


</code></pre>

### Yumdownloader ###

<pre><code>

</code></pre>


rpm, rpm2cpio
-------------

### rpm ###

<pre><code>

</code></pre>

### rpm2cpio ###

<pre><code>

</code></pre>
