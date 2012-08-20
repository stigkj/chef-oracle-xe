In case the how-to disappears, here are the steps:

  * echo 'deb http://oss.oracle.com/debian unstable main non-free' >> '/etc/apt/sources.list'
  * wget http://oss.oracle.com/el4/RPM-GPG-KEY-oracle  -O- | sudo apt-key add - 
  * apt-get update
  * apt-get install oracle-xe

There are some manual steps in there; hopefully these can be automated