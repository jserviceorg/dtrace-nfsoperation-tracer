# NFS opeation tracer

Trace NFS operations on a server

# Sample output
<pre>
$ nfstrace
Executable Operation    Type     Time    Size   Path
mkdir      nfs3_lookup  physical 359953  N/A    /opt/nfs/htdocs/test
mkdir      nfs3_getattr logical  17481   N/A    /opt/nfs/htdocs/test
mkdir      nfs3_getattr logical  7577    N/A    /opt/nfs/htdocs/test
mkdir      nfs3_mkdir   physical 843500  N/A    /opt/nfs/htdocs/test/test
rmdir      nfs3_access  logical  19772   N/A    /opt/nfs/htdocs/test
rmdir      nfs3_lookup  logical  69222   N/A    /opt/nfs/htdocs/test/test
rmdir      nfs3_access  logical  7744    N/A    /opt/nfs/htdocs/test
rmdir      nfs3_rmdir   physical 1390474 N/A    /opt/nfs/htdocs/test/test
touch      nfs3_access  logical  19566   N/A    /opt/nfs/htdocs/test
</pre>
