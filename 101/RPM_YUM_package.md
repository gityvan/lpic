102.5 Use RPM and YUM package management
----------------------------------------

Summary
-------

- Install, re-install, upgrade and remove packages using RPM and YUM.
- Obtain information on RPM packages such as version, status, dependencies, integrity and signatures.
- Determine what files a package provides, as well as find which package a specific file comes from.
- /etc/yum.conf, /etc/yum.repos.d/
- Yum, Yumdownloader
- rpm, rpm2cpio

Install, re-install, upgrade and remove packages using RPM and YUM
------------------------------------------------------------------

### YUM repositories ###

<pre><code>/etc/yum.conf                    # Config file
/etc/yum.repos.d/                # Repositories 
</code></pre>

### YUM ###

<pre><code>yum install pandoc               # Install package pandoc
yum remove  pandoc               # Remove package pandoc
yum reinstall pandoc             # Reinstall package

yum search markdown              # Search for package markdown
</code></pre>
