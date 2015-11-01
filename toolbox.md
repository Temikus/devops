##Logging:

###[Logstash](http://www.logstash.net/)  
logstash is a tool for managing events and logs. You can use it to collect logs, parse them, and store them for later use (like, for searching). Speaking of searching, logstash comes with a web interface for searching and drilling into all of your logs.

###[Stathat](https://www.stathat.com/)  
Hosted statistics tracker and aggregator. Pretty expensive (99$/month), but there is a free tier up to 10 metrics. Very good API.

##Automation:

###[Expect](http://www.nist.gov/el/msid/expect.cfm)
Expect is a tool for automating interactive applications such as telnet, ftp, passwd, fsck, rlogin, tip, etc. Expect really makes this stuff trivial. Expect is also useful for testing these same applications. And by adding Tk, you can wrap interactive applications in X11 GUIs.

###[Vagrant](http://www.vagrantup.com/)  
Automatic building of VM environments on VMware fusion and Virtualbox. Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.

###[BoxGrinder](http://boxgrinder.org/)  
BoxGrinder is a set of projects that help you grind out appliances for multiple virtualization and Cloud providers.

##Configuration management:

###[Etckeeper](http://joeyh.name/code/etckeeper/)
etckeeper is a collection of tools to let /etc be stored in a git, mercurial, darcs, or bzr repository. It hooks into apt (and other package managers including yum and pacman-g2) to automatically commit changes made to /etc during package upgrades. It tracks file metadata that revison control systems do not normally support, but that is important for /etc, such as the permissions of /etc/shadow. It's quite modular and configurable, while also being simple to use if you understand the basics of working with revision control.

###[Blueprint](http://devstructure.com/blueprint/)
Blueprint is a simple configuration management tool that reverse-engineers servers. It figures out what you’ve done manually, stores it locally in a Git repository, generates code that’s able to recreate your efforts, and helps you deploy those changes to production.

##Package management:

###[Pulp](http://www.pulpproject.org/)
Pulp is a platform for managing repositories of content, such as software packages, and pushing that content out to large numbers of consumers. If you want to locally mirror all or part of a repository, host your own content in a new repository, manage content from multiple sources in one place, and push content you choose out to large numbers of clients in one simple operation, Pulp is for you!

##Scripting:

###[Parallel](http://www.gnu.org/software/parallel/)
GNU parallel is a shell tool for executing jobs in parallel using one or more computers. A job can be a single command or a small script that has to be run for each of the lines in the input. The typical input is a list of files, a list of hosts, a list of users, a list of URLs, or a list of tables. A job can also be a command that reads from a pipe. GNU parallel can then split the input and pipe it into commands in parallel.

##Web utilities:

###[Aria2](http://aria2.sourceforge.net/)
aria2 is a lightweight multi-protocol & multi-source command-line download utility. It supportsHTTP/HTTPS, FTP, BitTorrent and Metalink. aria2 can be manipulated via built-in JSON-RPCand XML-RPC interfaces.

###[Siege](http://www.joedog.org/siege-home/)
Siege is an http load testing and benchmarking utility. It was designed to let web developers measure their code under duress, to see how it will stand up to load on the internet. Siege supports basic authentication, cookies, HTTP and HTTPS protocols. It lets its user hit a web server with a configurable number of simulated web browsers. Those browsers place the server “under siege.”

###[MTR](http://www.bitwizard.nl/mtr/)
mtr combines the functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.

##Directory services:

###[FreeIPA](http://freeipa.org/page/About)
FreeIPA is an integrated security information management solution combining Linux (Fedora), 389 Directory Server, MIT Kerberos, NTP, DNS, Dogtag (Certificate System). It consists of a web interface and command-line administration tools.
Nice wiki on implementation: http://linsec.ca/Using_FreeIPA_for_User_Authentication

##Security:

###[Reaver](https://code.google.com/p/reaver-wps/)
Reaver implements a brute force attack against Wifi Protected Setup (WPS) registrar PINs in order to recover WPA/WPA2 passphrases, as described in http://sviehb.files.wordpress.com/2011/12/viehboeck_wps.pdf.

###[Monkeysphere](http://web.monkeysphere.info/)
The Monkeysphere project's goal is to extend OpenPGP's web of trust to new areas of the Internet to help us securely identify servers we connect to, as well as each other while we work online. The suite of Monkeysphere utilities provides a framework to transparently leverage the web of trust for authentication of TLS/SSL communications through the normal use of tools you are familiar with, such as your web browser or secure shell.
Monkeysphere for the Web
Everyone who has used a web browser has been interrupted by the "Are you sure you want to connect?" warning message, which occurs when the browser finds the site's certificate unacceptable. But web browser vendors (e.g. Microsoft or Mozilla) should not be responsible for determining whom (or what) the user trusts to certify the authenticity of a website, or the identity of another user online. The user herself should have the final say, and designation of trust should be done on the basis of human interaction. The Monkeysphere project aims to make that possibility a reality.
Monkeysphere for OpenSSH
Frequent users of ssh are familiar with the prompt given the first time you log in to a new server, asking if you want to trust the server's key by verifying the key fingerprint. Unfortunately, unless you have access to the server's key fingerprint through a secure out-of-band channel, there is no way to verify that the fingerprint you are presented with is in fact that of the server you're really trying to connect to.
OpenSSH currently provides a functional way to manage the RSA and DSA keys required for these interactions through the known_hosts and authorized_keys files. However, it lacks any type of Public Key Infrastructure (PKI) that can verify that the keys being used really are the one required or expected.
Monkeysphere uses GnuPG's keyring manipulation capabilities and public keyserver communication to manage the keys that OpenSSH uses for connection authentication.

###[OSSEC](http://www.ossec.net/)
OSSEC is an Open Source Host-based Intrusion Detection System that performs log analysis, file integrity checking, policy monitoring, rootkit detection, real-time alerting and active response.
It runs on most operating systems, including Linux, MacOS, Solaris, HP-UX, AIX and Windows.

##Connectivity:

###[com0com](http://com0com.sourceforge.net/)
The Null-modem emulator allows you to create an unlimited number of virtual COM port pairs and use any pair to connect one COM port based application to another. Each COM port pair provides two COM ports. The output to one port is the input from other port and vice versa.
http://realterm.sourceforge.net/
Realterm is a terminal program specially designed for capturing, controlling and debugging binary and other difficult data streams. It is far better for debugging comms than Hyperterminal. It has no support for dialing modems, BBS etc - that is what hyperterminal does.

##Continuous integration:

###[Travis](https://travis-ci.org/)
Travis CI is a hosted continuous integration service for the open source community. It is integrated with GitHub and offers first class support for 14 languages.

###[Jenkins](http://jenkins-ci.org/)
Jenkins is an award-winning application that monitors executions of repeated jobs, such as building a software project or jobs run by cron. Among those things, current Jenkins focuses on the following two jobs:
Building/testing software projects continuously, just like CruiseControl or DamageControl. In a nutshell, Jenkins provides an easy-to-use so-called continuous integration system, making it easier for developers to integrate changes to the project, and making it easier for users to obtain a fresh build. The automated, continuous build increases the productivity.
Monitoring executions of externally-run jobs, such as cron jobs and procmail jobs, even those that are run on a remote machine. For example, with cron, all you receive is regular e-mails that capture the output, and it is up to you to look at them diligently and notice when it broke. Jenkins keeps those outputs and makes it easy for you to notice when something is wrong.

##Monitoring:

###[MoSShE](http://freecode.com/projects/mosshe)
MoSShE (MOnitoring in Simple SHell Environment) is a simple, lightweight (both in size and system requirements) server monitoring package designed for secure and in-depth monitoring of a handful of typical/critical Internet systems. It supports email alerts and SLA monitoring out of the box, and whatever you can script. The system is programmed in plain (Bourne) SH, and made to be compatible with BASH and Busybox so it can easily be deployed on embedded systems. Monitoring is designed to be distributed over multiple systems, usually running locally. As no parameters are accepted from the outside, checks cannot be tampered or misused from outside. The system is designed to allow decentralized checks and evaluation as well as classical agent-based checks with centralized data accumulation. Agent data is transferred via HTTP, so available Web servers can be co-used for agent data transfer. Each agent creates simple (static) HTML pages with full and condensed status reports on each system, allowing simple local checks.

###[Dashing](http://shopify.github.io/dashing/)
Dashing is a Sinatra based framework that lets you build beautiful dashboards.

###[Adagios](http://adagios.org/)
Adagios is a web based Nagios configuration interface built to be simple and intuitive in design, exposing less of the clutter under the hood of nagios. Additionally adagios has a rest interface for both status and configuration data as well a feature complete status interface that can be used as an alternative to nagios web interface.

###[Sensu](https://sensuapp.org/)
A monitoring framework written in Ruby that aims to be simple, malleable, and scalable.

###[Bosun](http://bosun.org/)
Bosun is an open-source, MIT licensed, monitoring and alerting system by Stack Exchange. It has an expressive domain specific language for evaluating alerts and creating detailed notifications. It also lets you test your alerts against history for a faster development experience.

###[Circle-CI](https://circleci.com/about) 
**Used by:** Shopify, Cisco, Sony  
CircleCI provides development teams the confidence to build, test, and deploy—quickly and consistently—across numerous platforms. Built to address the demanding needs of today's application development environments, CircleCI supports every component of a modern application, including mobile apps (iOS and Android), conventional web applications (built with platforms like Rails and Django), browser-based apps (built with frameworks like AngularJS and Ember), and containerized apps (built with tools like Docker).

###[Hound](https://houndci.com/repos)  
**Developer:** Thoughtbot  
Hound, a hosted service that reviews GitHub pull requests for Ruby, JavaScript, CoffeeScript, and SCSS style guide violations.

###[Codeship](https://codeship.com/)  
Hosted Continuous integration and delivery service. Supports parallel runs, ACL's, good integration with 3rd party services.

##DNS:

###[Unbound](http://unbound.net/)
Unbound is a validating, recursive, and caching DNS resolver.
Unbound is designed as a set of modular components, so that also DNSSEC (secure DNS) validation and stub-resolvers (that do not run as a server, but are linked into an application) are easily possible.

###[PowerDNS Authoritative Server](https://www.powerdns.com/auth.html)
PowerDNS Authoritative Server is the only solution that enables authoritative DNS service from all major databases, including but not limited to MySQL, PostgreSQL, SQLite3, Oracle, Sybase, Microsoft SQL Server, LDAP and plain text files.
DNS answers can also be fully scripted using a variety of (scripting) languages such as Lua, Java, Perl, Python, Ruby, C and C++. Such scripting can be used for dynamic redirection, (spam) filtering or real time intervention. PowerDNS Authoritative Server is the leading DNSSEC implementation, hosting the majority of all DNSSEC domains worldwide.

###[PowerDNS Recursor](https://www.powerdns.com/recursor.html)
PowerDNS Recursor is a high-end, high-performance resolving name server which powers the DNS resolution of at least a hundred million subscribers. Utilizing multiple processors and supporting the same powerful scripting ability of the Authoritative Server, the Recursor delivers top performance while retaining the flexibility modern DNS deployments require.

###[Namebench](https://code.google.com/p/namebench/)
Namebench hunts down the fastest dns servers available for your computer to use. namebench runs a fair and thorough benchmark using your web browser history, tcpdump output, or standardized datasets in order to provide an individualized recommendation. namebench is completely free and does not modify your system in any way. This project began as a 20% project at Google.

##WebMail:

###[Mailpile](https://www.mailpile.is/)
Mailpile is a modern, fast web-mail client with user-friendly encryption and privacy features. The development of Mailpile is funded by a large community of backers and all code related to the project is and will be released under an OSI approved Free Software license.　Mailpile places great emphasis on providing a clean, elegant user interface and pleasant user experience. In particular, Mailpile aims to make it easy and convenient to receive and send PGP encrypted or signed e-mail.

###[Roundcube](http://roundcube.net/)
Roundcube webmail is a browser-based multilingual IMAP client with an application-like user interface. It provides full functionality you expect from an email client, including MIME support, address book, folder manipulation, message searching and spell checking.

###[AfterLogic](http://www.afterlogic.org/)
AfterLogic WebMail is an open-source webmail script for your existing IMAP server.