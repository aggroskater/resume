# Preston Maness - July 04 2016

* __Phone__: 512-955-1048 (Signal calls/texts preferred; let's keep the spooks on their toes, shall we?)
* __Email/Public-Key__: aspensmonster@riseup.net
    * Fingerprint: 7989 5B2E 0F87 503F 1DDE  80B6 4976 5D7F 0DDD 9BD5
    * Keybase.io: [https://keybase.io/aspensmonster](https://keybase.io/aspensmonster)
* __Code__: [https://github.com/aggroskater/](https://github.com/aggroskater/) 
* __LinkedIn__: [http://www.linkedin.com/pub/preston-maness/8b/973/202](http://www.linkedin.com/pub/preston-maness/8b/973/202)

# The Involvement

This is the stuff that I'm passionate about. These are the things I put effort 
into and learn for no better reason than "because." Because technology is 
awesome and community is important. There's a mix of software and hardware
projects and languages/tools here given my formal EE education.

* Participation in Open Source and Free Software Community
    * [Staying on top of bugs my code introduces](https://github.com/BOINC/boinc/issues/1530) (My idle detection code for the BOINC project had a null pointer dereference bug)
    * [Debian GNU/Linux Package Maintenance](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=815214) (Fixed logging problems when moving from sysv init to systemd by tweaking the service file of the BOINC package.)
    * [Regression squash and feature enhancement for BOINC distributed computing project](https://github.com/BOINC/boinc/pull/1453) ( __C++__ ; A pull request that fixed idle detection regression in BOINC client --originally reported in a [Debian GNU/Linux bug](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=721298) I helped to troubleshoot-- and improved its handling of various edge cases. This also introduced me to the autotools build suite/toolchain.)
    * [Devops/Bug Squashing/Feature building work for Youtube Center](https://github.com/YePpHa/YouTubeCenter/issues/219) (Assisted @YePpHa with automatic plugin updating for the YTC project. See [pull request](https://github.com/YePpHa/YouTubeCenter/pull/222))
    * [Initial analysis of FinFisher malware suite](https://github.com/FinFisher/FinFly-Web/tree/master/xpi) (Used prior experience with browser addons/extensions to analyze the FinFisher malware suite's Firefox browser addon/extension attack vector. See [pull request](https://github.com/FinFisher/FinFly-Web/pull/4))
    * [Member of ArchiveTeam](http://www.archiveteam.org/index.php?title=Special%3ASearch&search=aggroskater&go=Go) ( __Python__ ; Preserving digital heritage before it is `rm -rf /`'d from existence. [Extended](https://github.com/aggroskater/twitchtv-grab) existing web-scraping pipeline to perform post-processing of scraped assets contained in ISO 28500-conforming WARC files. Sampling and shrinking of payloads (High-definition VODs) reduced storage requirements by 60 to 80 percent while maintaining minimum viable archive of material.)
    * [Bug Squashing with GNU FSF's `wget`](https://savannah.gnu.org/bugs/index.php?36570) ( __C__ ; Tracked down a stubborn segfault that was killing long-running web scrapes prematurely in a non-recoverable manner)
* Projects
    * [Hardware Random Number Generator](https://github.com/aggroskater/ee4390-senior-design-i/) (Senior Design Capstone Project)
    * [Terminal-based Aces Up card game in C++](https://github.com/aggroskater/cardgame.git)
    * [4-bit ALU with complete functional verification (VHDL)](https://github.com/aggroskater/33421-vhdl-digital-design/Project-4-4bit-ALU/)
    * [Class A power amplifier](https://github.com/aggroskater/ee3350-project/blob/master/final-schem.png)
* Languages and Tools
    * __Programming__: C++, C, Java, VHDL, HCS12 assembly
    * __Scripting__: Bash, Perl, Python
    * __Development Tools__: git, ant, GCC, eclipse, make, Doxygen, jenkins,
      valgrind, autotools
    * __Software__: Xilinx ISE, NI Multisim, LT-SPICE, MATLAB, Microwind,
      iverilog, gtkwave, ngspice, vim
    * __Systems Administration__: 
        * GNU/Linux: Apache, MySQL, PHP, Perl, Varish HTTP accelerator,
	  Wordpress, MediaWiki, Nagios monitoring, pnp4nagios, Vagrant VM
manager, Ansible automation, APT and RPM package management, Debian, CentOS and
RHEL distribution experience, basic LDAP authentication and authorization
mechanisms
	* Networking: Understanding of: Cisco firewall and CSS configs, F5 load
	  balancer configs, OSI network model, VLANs (I also dabble with
Mikrotik network gear)

# The Experience, Certs, and Education

Where I've been.

* Employment
    * __360Connect__ (4 months ; Apr. 2016 - present): Software Support
      Engineer, involved in managing systems integrations and analytics
pipelines (managing middleware and some infrastructure).
      * Provided feature enhancements to Coffeescript plugins (tested with
	Mocha/Chai) for the [LeadConduit](http://activeprospect.com/products/leadconduit/) platform:
        * [extending XML integration](https://github.com/activeprospect/leadconduit-integration-custom/issues/26)
        * [extending JSON integration](https://github.com/activeprospect/leadconduit-integration-custom/pull/28)
      * Automated numerous aspects of position by utilizing public APIs,
	Selenium, and python. Wrote simple flask app to consume MailGun webhook
events and automatically email appropriate person with details. Wrote python
script to [appropriately
poll](https://documentation.mailgun.com/api-events.html#event-polling) mailgun
event API and upload to S3 for further processing. Used python extensively to
interact with [LeadConduit Platform
API](http://docs.activeprospect.com/leadconduit/resources.html) and
programmatically manage/update/deploy lead flows.
    * __Rackspace Inc.__ (11 months ; Oct. 2014 - Sep. 2015): GNU/Linux Systems
      Administrator I. Everything I did at HostGator and more :)
Customer-facing support via calls and tickets. Position requires understanding
of Cisco and F5 firewalls, load balancers, and switches, along with a
high-level understanding of datacenter network architecture (aggrs, core
routers, edge routers, multiple back-end management networks). Work with DAS,
NAS, and SAN storage mechanisms. Basic VMware tasks (clone, resize, vMotion,
etc). Support and troubleshoot our OpenStack-based cloud products. Developed
internal python tool that interacts with several internal REST APIs to automate
numerous issues where networking and systems administration teams intersect in
an effort to reduce response times to incidents even further.
    * __HostGator.com LLC__ (13 months ; Jan. 2011 - Feb. 2012): GNU/Linux Web
      Hosting Systems Administration (Calls, Chats, Email), understanding of
Apache, Exim, Dovecot, MySQL, cPanel, WHM, bash/perl scripting, strace
debugging, customer site performance evaluation and optimization. Pushed for
more thorough, root-cause analysis of customer issues at __first contact__ to
avoid unnecessarily prolonging service degredation.
    * __Pei Wei Asian Diner__ (12 months ; Jan. 2010 - Jan. 2011): Cashier.
      Performed any and all front-of-house duties as necessary (bussing,
closing, etc).
    * __Colorado School of Mines__ (4 months ; Sep. 2009 - Dec. 2009): "Digger
      Dialer" - Fundraising, Donation Solicitation, general pestering of alumni
      within a call-center environment.

* Certifications
    * Red Hat Certified System Administrator, RHEL 7,
      [150-035-228](https://www.redhat.com/wapps/training/certification/verify.html?certNumber=150-035-228&isSearch=False&verify=Verify)

* Education
    * Bachelor of Science, Electrical Engineering, Computer Engineering
      concentration, Texas State University, class of 2014
    * Associate of Science, Applied Mathematics, Texas State University, class
      of 2014

