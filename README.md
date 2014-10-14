### Repo for Apache Cordova Board Reports

Apache Cordova reports due each quarter: **March, June, September, and December.**


Reports are due **at least one week** before the Apache Board Meeting. The relevant dates are highlighted below.

###2014 Board calendar

    - 15 Jan 2014
    - 19 Feb 2014
    - >>>>19 March 2014<<<<
    - 16 April 2014
    - 21 May 2014
    - >>>>18 June 2014<<<<
    - 16 July 2014
    - 20 August 2014
    - >>>>17 September 2014<<<<
    - 15 October 2014
    - 19 November 2014
    - >>>>17 December 2014<<<<

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
3. Create a New Account Request (PMC Chair only): [https://id.apache.org/acreq/](https://id.apache.org/acreq/)
4. Update (by any PMC member) [https://svn.apache.org/repos/private/committers/board/committee-info.txt](https://svn.apache.org/repos/private/committers/board/committee-info.txt) with the new PMC member's details and the effective join date (date that the file was updated).
5. ssh (PMC Chair only) to [people.apache.org](ssh://people.apache.org) then:

        modify_committee.pl {project} --add id
        
**All five steps have to be done properly to fulfill all Apache Board requirements (you'll get a reminder eventually if you did anything wrong).**

Optionally, you might want to automatically [ subscribe the new PMC member to the private list.](http://untroubled.org/ezmlm/manual/Remote-Administration.html). For example to add `name@example.com` to the `private@cordova.apache.org` mailing list, email to:

    private-subscribe-name=example.com@cordova.apache.org

### URL Shortener for Board Reports:

- [http://s.apache.org/](http://s.apache.org/)

### Calculating Stats for Board Reports:

For example, if doing the board report for September, you should tally the numbers for the previous 3 months of Aug, July and June (exclude the current reporting month).

- commits: count the # of emails in the [commits@ mailing list](https://mail-archives.apache.org/mod_mbox/cordova-commits/)
- emails: count the # of emails in the [dev@ mailing list](https://mail-archives.apache.org/mod_mbox/cordova-dev/)
- issues/comments on issues: count the # of emails in the [issues@ mailing list](https://mail-archives.apache.org/mod_mbox/cordova-issues/)
- iCLAs: counting them in [private@](https://mail-search.apache.org/pmc/private-arch/cordova-private/), filtered. Note that only Apache Members can search this type of list, PMC members (even Chairs), cannot -- so you will have to search your own private email archive.
- downloads: [cordova stats on npm](http://npm-stat.com/charts.html?package=cordova)


### Apache Mailing Lists

- [Public: http://www.apache.org/foundation/mailinglists.html](http://www.apache.org/foundation/mailinglists.html)
- [Private: https://mail-search.apache.org/](https://mail-search.apache.org/)

### Links

- [http://community.apache.org/boardreport.html](http://community.apache.org/boardreport.html)
- [http://apache.org/foundation/board/reporting](http://apache.org/foundation/board/reporting)
- [http://www.apache.org/dev/pmc.html](http://www.apache.org/dev/pmc.html)
- [https://svn.apache.org/repos/private/committers/board/committee-info.txt](https://svn.apache.org/repos/private/committers/board/committee-info.txt)


