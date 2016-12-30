# Learn _`IT Security & Privacy`_ [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/learn-security/issues)


Security, Privacy and Data Protection in information technology
systems is **NOT** "_**Optional**_". <br />
And yet, _most_ people prefer to _ignore_ the subject ...

![image](https://cloud.githubusercontent.com/assets/194400/21071387/95ef3cc4-be96-11e6-83b6-1ae4c9009cb3.png)

resorting to "[_ignorance is bliss_](https://youtu.be/l5y68ErffgM)"
_convincing_ themselves that the problem will somehow go away.

## _Why_?

For _most_ (_small/medium_) **organizations** (_and **many** large ones!_) technology project(s) **security**
is an "[***afterthought***](https://en.wiktionary.org/wiki/afterthought#Noun)", <br />
which people only _consider_ when they
_have_ to; _usually when the "**unthinkable**" (data compromise) happens_...

The loss of people's data can be [_devastating_](http://www.today.com/money/id-theft-can-take-heavy-emotional-toll-victims-1D80305639)
_both_ on a personal and organizational level.


## _Who_?

_Everyone_ in your organization _**must**_ have a _**security mindset**_! <br />

![security-fail-cable-tie-chain](https://cloud.githubusercontent.com/assets/194400/21071637/a8ee1798-be9e-11e6-98b3-e08b3d4ad6ac.jpg)

_Preferably **everyone** in all the organizations you **work/associate with** will have be **security-educated**,
because sadly, (naive/well-meaning) **people** remain the "[**weakest link**](http://www.cio.com/article/2895404/cybercrime/people-remain-the-weakest-link-in-security.html)"_.


## _What_?

> Firstly we must come to terms with the fact that it's **impossible to be 100% secure** because there will
_always_ be "_uncertainty_". That does not mean we should "_give up_"

There are _many_ areas of IT security that people in your team(s)
need to be aware of, they include:

+ Malware: https://youtu.be/cKlRc1_f5NY
+ Phishing: https://youtu.be/WpaLmeHTp3I
+ WiFi Safety: https://youtu.be/T5HCy3udooo

## How?

![magic-pill](https://cloud.githubusercontent.com/assets/194400/21573069/440ea2d0-ced8-11e6-9dca-537e5dab857f.jpg)

Sadly there is no "***magic pill***" we can take to make _everything_ secure. <br />
Thankfully, there are _several_ simple principals/practices we can follow that will help!

### Be Paranoid

Be paranoid about security. <br />
(_Sadly_) Personal data is ["**_Big_ Business**"](http://europe.newsweek.com/secretive-world-selling-data-about-you-464789) <br />
(_Unscrupulous_) people/organizations _are_ (_actively_) trying to ["_acquire_"](https://www.engadget.com/2016/12/30/facebook-buys-data-on-users-offline-habits-for-better-ads/) your data. <br />
"_Nasty_" people are _constantly_ running scripts, trying to ["_crack_" websites](http://www.forbes.com/sites/jameslyne/2013/09/06/30000-web-sites-hacked-a-day-how-do-you-host-yours). <br />
If you _hope_ to be successful, you should _expect_ your website/application to
be "_probed_" by somebody somewhere.
Don't _wait_ till the _breach_ happens. Plan ahead and be paranoid!

![image](https://cloud.githubusercontent.com/assets/194400/21573821/1efd939e-cee1-11e6-8cba-1142fa2efc82.png)

> Highly recommend reading "**Only the Paranoid Survive**" by Andy Grove: <br />
https://www.amazon.com/Only-Paranoid-Survive-Exploit-Challenge/dp/0385483821 <br />
If you don't have "_time_" to read it, _listen_ to the summary: https://youtu.be/jisR88yR9pk <br />
Also, watch: **10 Things to be Paranoid About as an Entrepreneur**: https://youtu.be/LqQomkp0P9Y



### Principal of _Least Priviledge_

> "_Every program and every privileged user of the system should operate
using the **least** amount of **privilege necessary** to complete the job_."

The level of access granted to a person/user or program/script should be
only that necessary for its legitimate purpose. The simple rule of thumb is:
if the person/program only needs read-access don't give it write access.
https://en.wikipedia.org/wiki/Principle_of_least_privilege

### Never Share User Accounts/Passwords

If you have an account on a system (_e.g: GitHub or AWS_)
maintain _accountability_ for yourself an others by _never_ sharing your account
or password with others.

> **Note**: this is not a question of "_trusting_" the people in your life/work!
We trust drivers with our lives each time we get into a vehicle with them,
but not all trust is the same. <br />
_Most_ non-technical people do not have good "_security habits_". <br />
**e.g**: _some_ people click on _any_ (_every_) link sent to them by "Facebook".
_Most_ people cannot distinguish a "_real_" email from "Facebook" from a
a fake (_phishing_) email. These people are _trivial_ to socially engineer.
Despite our _multiple_ attempts to "_educate_" these people,
unless they have "_felt the pain_" of identity fraud, for example,
they are unlikely to see the _benefit_ of being _careful_ online.

I know this might sound "dramatic" but if I can impress the _seriousness_ of this
upon you, in a _memorable_ way I will do so:
think about sharing your password like sharing a _needle_!

![djs-dont-share-needles](https://cloud.githubusercontent.com/assets/194400/21574204/d9c1ae0e-cee6-11e6-8e45-9f686697cfe2.png)


> Note: this is why systems that charge per user-account per month are to be avoided <br />
because they _perversely_ incentivize people to
share account in order to avoid paying <br />
for more "seats" or "licenses". Salesforce/Jira/Microsoft we're looking at you!

### Use Encryption!

![encryption](https://cloud.githubusercontent.com/assets/194400/21574006/757862e2-cee3-11e6-8a84-6b1ab67c467f.jpeg)

Encrypting data which does not need to be full-text searchable is _generally_ a good idea. <br />
Encrypting any/all personally identifiable data required by your application is _essential_.

> If you are new to cryptography (_encryption_) see:
https://github.com/dwyl/learn-cryptography


### OWASP Top 10

The **O**pen **W**eb Application Security Project (OWASP)

https://en.wikipedia.org/wiki/OWASP

> Cheat Sheet: https://www.owasp.org/index.php/OWASP_Top_Ten_Cheat_Sheet


## ISO 27001 ?

If you are interested in the ISO 27001 Information Technology Security standard, <br />
please see: https://github.com/dwyl/ISO-27001-2013-information-technology-security


## Recommended Reading

+ Why do we _still_ write insecure software? (_by Jeremy Bowers_): http://www.jerf.org/iri/post/2942
+ Google (_Online_) Safety Center: https://www.google.com/safetycenter (_lots of good advice_)
+ The UK’s 15 most infamous data breaches:
http://www.techworld.com/security/uks-most-infamous-data-breaches-2016-3604586/
+ Cyber Security Breaches Survey 2016 (_Official UK Gov report_):
https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/521465/Cyber_Security_Breaches_Survey_2016_main_report_FINAL.pdf
+ EU General Data Protection Regulation:
https://en.wikipedia.org/wiki/General_Data_Protection_Regulation
+ **Robot Laws** (Data Protection Regulation - Tableflip Podcast):
https://overcast.fm/+HVTBxY7_w
+ Guide to data protection
https://ico.org.uk/for-organisations/guide-to-data-protection/
+ Data Protection Principals:
https://ico.org.uk/for-organisations/guide-to-data-protection/data-protection-principles/
+ HTTPS and SSL in _plain english_: https://youtu.be/_p-LNLv49Ug
+ Calling Humans the “Weakest Link” in Computer Security Is Dangerous and Unhelpful:
http://www.slate.com/blogs/future_tense/2016/01/22/calling_humans_the_weakest_link_in_computer_security_is_dangerous.html

## Videos

+ Security Now https://twit.tv/shows/security-now is the go-to place to learn
"_complex_" topics in _general_ security and _technology_ security _specifically_.
+ Securing your WiFi network: https://youtu.be/_WHynHcXm7c
