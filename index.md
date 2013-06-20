---
title: Hello, World!
layout: default
---

# IGI Releases

Welcome to IGI Releases pages!

You'll find here usefull information regarding INFN developed grid middleware software releases, roadmaps, documentation and support.

* [IGI Release Portfolio](#portfolio)
* [Release Schedule](#relsched)
* [Supported platforms](#supportedplatf)
   * [Supported packaging formats](#relcontent)
* [Release Repositories](#releaserepos)

<a name="introduction">&nbsp;</a>
## IGI Release Portfolio

<p> The IGI Release represents the collection of the grid middleware software developed by INFN: </p>
* [CREAM products](https://wiki.italiangrid.it/twiki/bin/view/CREAM/WebHome "CREAM CE")
  * [BLAH](https://wiki.italiangrid.it/twiki/bin/view/CREAM/BlahUserGuide "BLAH") - **B**atch **L**ocal **A**scii **H**elper Service
  * [CREAM CE](https://wiki.italiangrid.it/twiki/bin/view/CREAM/SystemAdministratorDocumentation "CREAM CE") - **C**omputing **R**esource **E**xecution **A**nd **M**anagement Service
  * [CREAM <batch-system> modules](https://wiki.italiangrid.it/twiki/bin/view/CREAM/SystemAdministratorGuideForEMI2#1_6_Batch_system_integration "CREAM <batch> modules") for [LSF](https://wiki.italiangrid.it/twiki/bin/view/CREAM/SystemAdministratorGuideForEMI2#1_6_2_LSF "LSF"), [TORQUE](https://wiki.italiangrid.it/twiki/bin/view/CREAM/SystemAdministratorGuideForEMI2#1_6_1_Torque "TORQUE"), [SLURM](https://wiki.italiangrid.it/twiki/bin/view/CREAM/SystemAdministratorGuideForEMI2#1_6_3_Grid_Engine "SLURM")
  * [CREAM clients](https://wiki.italiangrid.it/twiki/bin/view/CREAM/UserDocumentation "CREAM clients") 
  * [Cluster](https://wiki.italiangrid.it/twiki/bin/view/CREAM/SystemAdministratorGuideForEMI3#1_2_1_CREAM_CE_and_gLite_cluster "Cluster")
* [DGAS](http://www.to.infn.it/grid/INFNGRID/TESTING/accounting/index.html "DGAS") - **D**istributed **G**rid **A**ccounting **S**ystem
* [StoRM](http://italiangrid.github.io/storm/index.html "StoRM") - **Sto**rage **R**esource **M**anager
* [VOMS](https://github.com/italiangrid/voms/wiki "VOMS") - **V**irtual **O**rganization **M**embership **S**ervice
* [WMS](https://wiki.italiangrid.it/twiki/bin/view/WMS/WebHome "WMS") - **W**orkload **M**anagement **S**ystem       

<a name="relsched">&nbsp;</a>
## Release Schedule
### Time-based releases
 * **Major releases** - at the “distribution level” every 6 months a Major release is  “cut” 
 * **Minor/Revision releases** - monthly updates are pushed to production repositories

### Support Model
 * in a Major Release for each component or service only the latest revision released is supported.
 * for each component/service a (major) release is supported for 6 months after the release of the respective component’s/service next major version.

<a name="supportedplatf">&nbsp;</a>
## Supported platforms

 * IGI releases are/will be supported for the following platforms:
    * all components:
       * Scientific Linux 5.x with EPEL 5 and SL 6.x with EPEL 6,  x86_64
       * Deb6, amd64
    * clients/libraries/API - in addition to the above:
       * Scientific Linux 5.x/EPEL5 and 6.x/EPEL6, i386/i686
       * Deb6, i386

<a name="relcontent">&nbsp;</a>
### Supported artifacts & packaging formats
 * binary packages - executable packages
   * SL5.X/SL6.X - *.rpm
   * Deb6 - *.deb
 * source packages - package files that contain all of the necessary files to compile/build the respective piece of software
   * SL5.x/Sl6.X - *.src.rpm
   * Deb6 - *.dsc, *.debian.tar.gz, + *.tar.gz

<a name="releaserepos">&nbsp;</a>
## Release Repositories

<h3><font style="color="#FC0813"">Coming soon!</font></h3>




