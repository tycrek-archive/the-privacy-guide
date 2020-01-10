# The Privacy Guide

#### Note: this guide is NOT complete. However, I still appreciate and encourage Issues and Pull Requests to improve this guide. Typos, links, clarifications, or anything else would be very helpful. In the meantime, also consider checking out my [De-Google](https://github.com/tycrek/degoogle) guide.

---

A modern, easy-to-read guide on privacy and security for people of all skill levels.

This guide is intended for introducing people to what I am calling **PASS** (**P**rivacy, **A**nonymity, **S**ecurity, & **S**urveillance). It is meant to be a gentle, non-confrontational way of explaining why these concepts are important and why people should be concerned.

I will begin the guide by explaining some key concepts and definitions. I recommend beginners start here, but if you already know most of the terms, feel free to jump ahead.

If anyone has any further questions or comments, feel free to open a GitHub issue or email me at [josh.moore@jmoore.dev](mailto:josh.moore@jmoore.dev). Pull requests are not only welcomed, but encouraged.

---

## Index

### Section 1

1. [What is privacy?][11]
2. [What is security?][12]
3. [What is anonymity?][13]
4. [What is surveillance?][14]
5. [Why PASS matters][15]

### Section 2

1. [Secure your communications][21]
2. [Keep your photos private][22]
3. [Lock down your device][23]
4. [Ditch the big guys][24]

---

## What is privacy?

> *The quality or state of being apart from company or observation.* - [Merriam Webster](https://www.merriam-webster.com/dictionary/privacy)

When an individual has "privacy", it means they are free from observation. If you are at work and your boss is leaning over your shoulder, you do not have privacy. Typically, when you are at home alone, you do have privacy (to an extent).

Being observed upon, be it voluntary or involuntary, is an "[invasion of privacy](https://legal-dictionary.thefreedictionary.com/invasion+of+privacy)". This applies to all aspects of physical and digital life.

**In what ways is your digital privacy being violated?**

Chances are, if you are reading this, you are probably using a smartphone such as an iPhone or Android device or a computer. By default, your device (and most likely your browser) are tracking you and everything you do online. Google Search and Google Chrome are [tracking every search you make](https://clark.com/technology/google-chrome-do-not-track/) and every site you visit to build a profile of you: your **data**. This data can be used in many ways.

[Targeted advertising](https://edu.gcfglobal.org/en/thenow/what-is-targeted-advertising/1/) uses your data to show you ads tailored to your personal interests. If you frequently search for pet related items, you might start seeing ads for dog food or cat litter.

Sometimes your data will be used to train artifical intelligence programs. If you have told Google your age, gender, and other personal information, it can give your data and that information to an AI so the AI can also learn about you. Using information from other people similar to you, it can learn to be more accurate with its given task. An AI chatbot might learn specific ways of chatting to different demographics depending on what it learns about them. An AI could also provide suggestions to a user based on the interests of similar people. *Evidence of this would be appreciated.*

Perhaps the most controversial ways your data is used is in sales to third-party companies. Surprisingly, [Google does not actually sell your data](https://www.androidcentral.com/does-google-sell-your-data). Instead, they keep it to themselves. There is [limited evidence that Microsoft sells your data](https://nypost.com/2018/04/03/why-microsoft-and-apple-dont-need-to-sell-your-data/), but many of their policies clearly state it is collected. [Apple is a bit better](https://www.usatoday.com/story/tech/talkingtech/2018/04/17/apple-make-simpler-download-your-privacy-data-year/521786002/), with less tracking overall and no data selling, but they can still use what they do have internally. [Amazon collects and uses your data](https://www.investopedia.com/articles/insights/090716/7-ways-amazon-uses-big-data-stalk-you-amzn.asp) in a wide variety of ways, but there is limited evidence that this data is sold to third-parties. [Facebook](https://www.investopedia.com/tech/how-much-can-facebook-potentially-make-selling-your-data/) is notorious for it's tracking. Internally, it uses your data for advertising. It does not exactly sell your data to advertisers, rather [it sells access to you](https://www.vox.com/2018/4/11/17177842/facebook-advertising-ads-explained-mark-zuckerberg), although that could be interpreted differently.

Regardless of the company or purpose, it is obvious that your personal information and data is incredibly valueable to big companies as they all have methods of using it to make them more money.

Aside from big companies, there is a darker side to digital privacy. Hackers and intelligence organizations such as the FBI, CIA, NSA, and others are constantly monitoring everything going through the internet. You specifically may not be targeted, but you are still being tracked. In 2013, whistleblower [Edward Snowden](https://en.wikipedia.org/wiki/Edward_Snowden) released confidential documents detailing all the way the United State Government unconstitutionally tracks citizens all over the world (on a personal note, I highly recommend reading his autobiography [Permanent Record](https://en.wikipedia.org/wiki/Permanent_Record_(Snowden_book)), available at Ama- I mean, your local book store). We will go more in depth on surveillance [later on in this guide][4].

**In what ways are you voluntarily giving up your privacy?**

When you sign up for a service such as Gmail, Facebook, or Amazon, they always request that you fill in your personal information. This typically includes:

- Name
- Age
- Gender
- Email
- Phone number
- Physical address
- Credit card details
- Personal info for security questions, such as mothers maiden name or pets name
- and more

A lot of the time, this data is kept internal, but mistakes still happen. The [Cambridge Analytica scandal](https://www.theguardian.com/uk-news/2018/mar/22/cambridge-analytica-scandal-the-biggest-revelations-so-far) in 2018 leaked the personal information of [over 50 million Facebook users and over 70 million American citizens](https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal). Even if you are not a threat or are not targeted by a government organization or hacker, this data is still extremely valuable, especially if financial info (credit scores, SIN or SSN's, credit card details) or passwords are available.

You give up your privacy in other ways as well, and you might not even realize that you are. Apps used for [health tracking and mangement](https://www.consumerreports.org/health-privacy/are-health-apps-putting-your-privacy-at-risk/) are collecting very detailed data about almost every aspect of you. This includes details such as height, weight, BMI, blood pressure, and more. Many exercise apps also track your location. While these apps and the companies behind them may not necessarily sell or use your data, it is very common for their security to be lacking and for hackers to break in and take it.

When signing up for a website or service, there is almost always a prompt to read the [Privacy Policy](https://en.wikipedia.org/wiki/Privacy_policy). [Most people don't bother reading it at all](https://www.axios.com/few-people-read-privacy-policies-survey-fec3a29e-2e3a-4767-a05c-2cacdcbaecc8.html) and instead just blindly agree. Agreeing to these typically puts you in a bad position if your data is misused or stolen, as many companies prevent you from suing or participating in a class action lawsuit. [This article published in 2015](http://www.spzlegal.com/privacy/terms-of-use-legally-binding/) describes how most of the time, these policies are legally binding. By signing them, you agree to any rights the service has over the data you provide them.

---

## What is security?

> *The quality or state of being secure: such as freedom from danger, freedom from fear or anxiety...* - [Merriam Webster](https://www.merriam-webster.com/dictionary/security)

Now that you have a deeper understanding of your privacy, you may be wondering [what it means to be secure](https://en.wikipedia.org/wiki/Security) and how security is different.

Like privacy, security comes in both physical and digital forms. Personal physical security could include: locks on your front door; security cameras; or carrying a firearm. Digital security is the intention of protecting your device and everything on it. For the purpose of this guide, we will focus on digital security.

Digital technology enables us to live richer, fuller lives. A big part of this comes from the communication digital technology enables us to do. Messaging a relative on the other side of the planet is simply a text message away and only takes a few seconds at most. Our devices have come a long way: not only can we message, but we can see eachother through video calls; play with eachother through online gaming; research topics online; store photos of memories; and so much more. But all of these are at risk without proper security.

Digital security means that the data stored on your device, as well as data going to and from your device, is hidden away from prying eyes. Only you and the intended recipient should be able to view it. Securing digital data is accomplished using [encryption](https://en.wikipedia.org/wiki/Encryption). Encryption and decryption of data is an enourmous topic outside the scope of this guide. For now, think of encryption simply as away for no one to view what they shouldn't be able to.

Without encryption, nearly anyone can eavesdrop on your digital life. Texting using SMS or MMS is probably the least secure thing you could ever do digitally. Texts are **not** encrypted between parties and gaining access to texts is incredibly easy for a hacker or government agency using [cell tower spoofing](https://www.wired.com/2010/07/intercepting-cell-phone-calls/). This has been proven many times. A common attack method is the [StingRay phone tracker](https://en.m.wikipedia.org/wiki/Stingray_phone_tracker), a controversial device that can intercept text messages, phone calls, and sometimes, unencrypted web traffic such as searches. The StingRay mimics a cell tower which your phone connects to. It then forces your device to use older, insecure protocols so that it can gather any messages or calls from your device. The [American Civil Liberties Union](https://www.aclu.org/) has [a page dedicated to who owns StingRay devices](https://www.aclu.org/issues/privacy-technology/surveillance-technologies/stingray-tracking-devices-whos-got-them) in the USA. Chances are, if you live in a big city, the police force is probably using them.

---

## What is anonymity?

> *The quality or state of being anonymous: not named or identified* - [Merriam Webster](https://www.merriam-webster.com/dictionary/anonymity)

When one is considered "anonymous", it simply means they cannot be identified. Online anonymity means that what you do online cannot be traced back to you. For example, signing up for a Reddit account with a [screen name](https://www.techopedia.com/definition/32120/screen-name) can be considered anonymous, as long as that name has no relation to you at all. Someone named John Smith might sign up as "PartyAnimal12345". As long as nothing is posted using that account that can be linked back to the owner, it can be considered anonmyous.

Chances are, if you have a Facebook account, it is absolutely not anonymous. It is a platform for interacting with friends and family, so nearly everyone uses their real name. A photo of you could also be used to identify you.

[Anonymity](https://en.wikipedia.org/wiki/Anonymity) is a complex topic that goes much further beyond just names and photos. Further on in this guide, we will discuss way to stay anonymous online.

---

## What is surveillance?

> *Close watch kept over someone or something* - [Merriam Webster](https://www.merriam-webster.com/dictionary/surveillance)

Surveillance is the monitoring of a person, group, or other entity such as government. It is pretty easy to tell if you are being surveilled: do you live in the USA? Then you are being surveilled. What about Canada? The UK? Australia or New Zealand? Yes. This countries are apart of an alliance commonly known as the "Five Eyes". They are known to actively monitor and track not just their own citizens, but those in other countries. There are also "Nine Eyes" and "14 Eyes", which include even more countries that conduct surveillance. [This article](https://restoreprivacy.com/5-eyes-9-eyes-14-eyes/) does a fantastic job at detailing which countries are apart of these alliances. For a quick rundown:

**Five Eyes**

1. Australia
2. Canada
3. New Zealand
4. United Kingdom
5. United States

**Nine Eyes**

6. Denmark
7. France
8. Netherlands
9. Norway

**14 Eyes**

10. Germany
11. Belgium
12. Italy
13. Sweden
14. Spain

As mentioned above in *[What is Privacy?][1]*, Edward Snowden leaked documents detailing how to United States is unconstitutionally conducting surveillance on it's citizens. Snowden also appeared on the [Joe Rogan Experience](http://podcasts.joerogan.net/podcasts/edward-snowden) podcast.

## Why PASS matters

PASS is Privacy, Anonymity, Security, & Surveillance. These should be a concern for all citizens of the world regardless of who they are, where they come from, or what they believe in. An everyday person may not be the direct target of a hacker, but that is rarely the methods used anymore. Programs and "bots" crawl the internet looking for security holes to exploit. If it just so happens that your data is in this hole, it could have the potential to turn your life upside down. Hackers can use your data for identity theft to commit crimes on your behalf, or use your credit card to make expensive fraudulent purchases online. At times, your data can be used for blackmail, perhaps if you have a login for an adult-only website and don't want your family to know.

Average citizens are never the target, they just have the misfortune of being caught in the crossfire. By putting an effort into improving their privacy and security, they can be shielded from the bad side of the internet.

Many people state that they do not care if their data is stolen or used without their explicit permission. However, this is an abuse of your data. Your data is *you*. In essence, you are allowing these companies and groups to abuse who you are. It is not physical, but is harmful.

I hope that by now you are convinced on why you should care about your privacy and security. If you are still not convinced, I don't blame you. I still recommend picking up a copy of Permanent Record and listening to Joe Rogan's interview with Edward Snowden. If this is where you decide to stop reading, I hope you are at least more aware of what happens when you interact online. Read further and we will discuss various methods of improving your privacy or security. You can also go back to the [Index](#index) to select a topic.

---

## Secure your communications

This section will cover how to secure the most common ways of communicating on a smartphone or computer: texting, calling, and email.

### Texting

Texting uses two sets of "protocols" (a way for computers to communicate with eachother): **SMS** and **MMS**. SMS is used for short pieces of text, where MMS is used for much longer messages, photos, and videos. Neither of these are very secure and can be easily exploited. They are also very outdated and rarely get updated at all, just so that old devices can still work. There are a variety of ways to improve your texting PASS depending on your skill level.

#### Signal Messanger (Skill level: Easy)

**[Signal](https://signal.org/)** is an app that enables highly secure **text**, **photo**, **video**, and **voice** messaging between its users. Every Signal message between two Signal users is "end-to-end encrypted". This means that the only people who can ever see the contents are the sender and the recipient. Signal is developed by Open Whisper Systems, whom Edward Snowden personally recommends.

Signal has apps for iOS and Android, as well as programs for Windows, macOS, and Linux.

A benefit of Signal (at least for Android devices) is the ability to also send SMS or MMS to non-Signal users within the same app. Unfortunately, due to Apple control over iOS, this is not possible on iPhones. However, iPhone users can still download the app and get their friends and family to as well to enable secure communications.

Signal is full of useful features such as a dark mode; disappearing messages; group chats; voice and video calls; and more. Best of all: it is completely free and has no ads. It also provides an encrypted database for all your messages that can be locked with a passcode or fingerprint.

The main downside of Signal is that it requires a phone number to join. Because of this, the app loses the Anonymity in PASS.

#### Riot (Skill level: Easy-Medium)

**[Riot](https://about.riot.im/)** is similar to Signal in the sense that messages are end-to-end encrypted. It supports group chats, photo/file sharing, voice/video calls, and more. You can use it in your browser or download apps for Windows, macOS, Linux, iOS, and Android. Unlike Signal Android, Riot cannot send SMS or MMS. It also has a dark mode built in.

I decided to put Riot as Easy-Medium because the concept is quite easy for most people to understand. Riot uses the decentralized Matrix protocol, which means messages never go to a central server and instead are shared between users directly. The end-to-end encryption ensures that no one but the sender and recipient are able to view the messages. Riot is completely free with no ads.

#### Tox (Skill level: Medium-Hard)

**[Tox](https://tox.chat/)** is similar to Riot in the sense that it is decentralized. Like the others, it supports groups, photos, files, voice, and video. You can also share your desktop screen with other users. It is also completely free and has no ads.

Tox has programs available for Windows, macOS, and Linux. It has an app for Android and an app for iOS. The programs and apps are built by the community, so they may not have all the features that Tox offers by default.

### Email

To add: Tutanota, Protonmail, and others.

---

[11]: #what-is-privacy
[12]: #what-is-security
[13]: #what-is-anonymity
[14]: #what-is-surveillance
[15]: #why-pass-matters

[21]: #secure-your-communications
[22]: #keep-your-photos-private
[23]: #lock-down-your-device
[24]: #ditch-the-big-guys