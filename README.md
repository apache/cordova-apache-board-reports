### Repo for Apache Cordova Board Reports

Apache Cordova reports due each quarter: **March, June, September, and December.**


Reports are due **at least one week** before the [Apache Board Meeting](http://www.apache.org/foundation/board/calendar.html). The relevant dates are highlighted below.

###2016 Board calendar

    - 20 January 2016
    - 17 February 2016
    - >>>>16 March 2016<<<<
    - 20 April 2016
    - 18 May 2016
    - >>>>15 June 2016<<<<
    - 20 July 2016
    - 17 August 2016
    - >>>>21 September 2016<<<<
    - 19 October 2016
    - 16 November 2016
    - >>>>21 December 2016<<<<

---

### Board Report Template

- [http://community.apache.org/boardreport.html](http://community.apache.org/boardreport.html)

### Current Cordova Committee List

- [https://whimsy.apache.org/roster/committee/cordova](https://whimsy.apache.org/roster/committee/cordova)

### Search for a Committer

- [https://whimsy.apache.org/roster/committer/](https://whimsy.apache.org/roster/committer/)
 
### Change the PMC Chair:

- [http://www.apache.org/dev/pmc.html#newchair](http://www.apache.org/dev/pmc.html#newchair)

### We want to add a developer as a committer, and consequently the PMC (our project rule). What does the PMC chair have to do?

1. Adding a new Committer (by any PMC member): [https://community.apache.org/newcommitter.html](https://community.apache.org/newcommitter.html) - make sure to include a link to the [Committer's FAQ](www.apache.org/dev/committers.html)
2. Adding a new PMC member (by any PMC member): [http://www.apache.org/dev/pmc.html#newpmc](http://www.apache.org/dev/pmc.html#newpmc), wait 72 hours for any Board objections
3. Create a New Account Request (PMC Chair only): [https://id.apache.org/acreq/](https://id.apache.org/acreq/) OR add an existing account as committer/pmc: [https://www.apache.org/dev/pmc.html#SVNaccess](https://www.apache.org/dev/pmc.html#SVNaccess)
4. Update (by any PMC member) [https://svn.apache.org/repos/private/committers/board/committee-info.txt](https://svn.apache.org/repos/private/committers/board/committee-info.txt) with the new PMC member's details and the effective join date (date that the file was updated).
5. Update the LDAP records for Cordova using Whimsy (PMC Chair only) at [whimsy.apache.org](https://whimsy.apache.org/roster/committee/cordova).

    If that fails, you will need to SSH to minotaur.apache.org and run the `modify_committee.pl` command (run it without parameters to see the help text)

**All five steps have to be done properly to fulfill all Apache Board requirements (you'll get a reminder eventually if you did anything wrong).**

Optionally, you might want to automatically [ subscribe the new PMC member to the private list.](http://untroubled.org/ezmlm/manual/Remote-Administration.html). For example to add `name@example.com` to the `private@cordova.apache.org` mailing list, email to:

    private-subscribe-name=example.com@cordova.apache.org

### URL Shortener for Board Reports:

- [http://s.apache.org/](http://s.apache.org/)

### Generating/Calculating Stats for Board Reports:

For example, if doing the board report for September, you should tally the numbers for the previous 3 months of Aug, July and June (exclude the current reporting month).

- commits: count the # of emails in the [commits@ mailing list](https://mail-archives.apache.org/mod_mbox/cordova-commits/)
- emails: count the # of emails in the [dev@ mailing list](https://mail-archives.apache.org/mod_mbox/cordova-dev/)
- issues/comments on issues: count the # of emails in the [issues@ mailing list](https://mail-archives.apache.org/mod_mbox/cordova-issues/)
- iCLAs: counting them in [private@](https://mail-search.apache.org/pmc/private-arch/cordova-private/), filtered. Note that only Apache Members can search this type of list, PMC members (even Chairs), cannot -- so you will have to search your own private email archive.
- downloads: [cordova stats on npm](http://npm-stat.com/charts.html?package=cordova)

OR you can use this as a starter:

- [https://reporter.apache.org/](https://reporter.apache.org/)

### Posting Board Reports (PMC Chair)

1. Email "board (at) apache (dot) org". Use subject: "[REPORT] Apache Cordova (MONTH YEAR)".
2. Update the appropriate Board Agenda text file at https://svn.apache.org/repos/private/foundation/board/

OR use this tool:

- [https://whimsy.apache.org/board/posted-reports](https://whimsy.apache.org/board/posted-reports)

### Resignation of a PMC Member (PMC Chair)

See [http://www.apache.org/dev/pmc.html#emeritus](http://www.apache.org/dev/pmc.html#emeritus) for steps.

### Apache Mailing Lists

- [Public: http://www.apache.org/foundation/mailinglists.html](http://www.apache.org/foundation/mailinglists.html)
- [Private: https://mail-search.apache.org/](https://mail-search.apache.org/)

### Links

- [http://community.apache.org/boardreport.html](http://community.apache.org/boardreport.html)
- [http://apache.org/foundation/board/reporting](http://apache.org/foundation/board/reporting)
- [http://www.apache.org/dev/pmc.html](http://www.apache.org/dev/pmc.html)
- [https://svn.apache.org/repos/private/committers/board/committee-info.txt](https://svn.apache.org/repos/private/committers/board/committee-info.txt)


