# Users are all you need
So, let's make it really easy to acquire them!

When we look at successful deployments of human access to technology, we find examples like OpenID Connect where users already had accounts at Yahoo and Google, Then the smaller web sites needed to rapidly enroll users who were overwhelmed by the shear complexity and confusion of too many sites asking them to create accounts that required the sort of secret sharing passwords that human are not good at remembering. Let’s consider the parties to the effort and why each thought that it was a win for them.

1. Google and Yahoo cemented their role as gatekeepers for new technology.
2. Emergent web sites were able to get users to create accounts easily.
3. Users had few secrets that they needed to both remember and maintain.

Also, the proposed solution was remarkable simple. Any programmer could gin up a new web site with full user account control in a matter of hours. The result was presented to the users as **Single Sign-On**, an attractive alternate to individual account names and passwords at every website where the user wanted to maintain some context from one access to another. Compare this to what happens when a government decides to create a user access control system. The downside was that the website got access to your email account and often other identifity information.

## Groups of Users - The Circle

The single-signon solutions were desinged by corporations to control connections between humans and web sites. For the future let's try to create solutions which are oriented to the way that humans engage with each other and build solutions that focus on human needs rather than website needs in a world where Artificial Agents help humans organize their lives. Consider how the **family circle**, **church circle**, and **social circle** compare to other group formations by looking at their **structure, purpose, and dynamics**. These circles represent deeply rooted forms of human congregation, but they’re just part of a broader landscape of how people come together.

---

### Core Circles: Family, Church, Social

| Circle Type     | Primary Bond        | Purpose                          | Trust Level        | Membership Basis         |
|----------------|---------------------|----------------------------------|--------------------|--------------------------|
| **Family Circle** | Kinship & obligation | Nurturing, support, identity     | High (often unconditional) | Birth, marriage, adoption |
| **Church Circle** | Shared beliefs       | Spiritual growth, moral guidance | Moderate to high   | Faith affiliation         |
| **Social Circle** | Friendship & affinity | Recreation, emotional support    | Variable           | Shared interests, proximity |

These circles are often **voluntary (social, church)** or **involuntary (family)** and tend to be **long-term** in nature.

---

### Other Group Formations

Compare those circels with other ways people congregate:

#### 1. **Workplace Teams**
- **Bond**: Professional goals
- **Purpose**: Productivity, collaboration
- **Trust**: Conditional, performance-based
- **Membership**: Employment or assignment

#### 2. **Online Communities**
- **Bond**: Shared interest or identity
- **Purpose**: Information exchange, support
- **Trust**: Low to moderate (anonymity plays a role)
- **Membership**: Voluntary, often fluid

#### 3. **Activist or Political Groups**
- **Bond**: Shared values or causes
- **Purpose**: Advocacy, change-making
- **Trust**: High among core members
- **Membership**: Ideological alignment

#### 4. **Educational Cohorts**
- **Bond**: Shared learning journey
- **Purpose**: Academic growth
- **Trust**: Moderate, often grows over time
- **Membership**: Enrollment-based

#### 5. **Affinity Circles** (e.g. hobby clubs, sports teams)
- **Bond**: Passion or skill
- **Purpose**: Enjoyment, mastery
- **Trust**: Moderate, based on shared experience
- **Membership**: Voluntary, interest-driven

---

### Psychological & Sociological Layers

According to [Andrei Drăgănescu’s model](https://www.andreidraganescu.info/2015/07/06/the-7-social-circle-types/), social circles can be layered by **trust and intimacy**, ranging from:
- **Devotion** (e.g., family, spiritual mentors)
- **Intimacy** (close friends, partners)
- **Principles & Experiences** (shared values or events)
- Down to **Acquaintances & Peers**

Each layer reflects how **deeply embedded** someone is in your life—and how much **emotional risk or investment** is involved.

### Moving to a new world where groups come with there own agents to manage many of the details of human interactions.

The family, church, and social circles are traditional forms, but modern life has expanded our ways of congregating—digitally, professionally, ideologically. Each group formation offers different benefits and vulnerabilities, shaped by context, culture, and personal choice.

## Who is in control

Government, schools and employers have complete control of user access technology and are able to impose whatever solutions that want on their subjects. The results tend to be ugly, hard to maintain and difficult to change. In sum, top-down solutions are seldom popular with users. We have some specific examples of problems created by this approach: prompt fatigue and insecurity. Somehow the EU parliament got the idea that cookies were evil because of the way that cookies enabled tracking of people, so they gave users the right to ask for cookies not to be collected. The cookie threat has been (soon) eliminated by the deprecation of third-party cookies, but the incessant and insensible barrage of requests to allow cookies continues to force the users to continuously make security choices to the point where they just accept everything. The security threat to user private data is magnified by the judges in the EU that created the “right to be forgotten”, which resulted in the collection of all those damaging secrets into a single online data base so that they WOULD NOT be displayed in a search but certainly will show up, in their entirety, on the dark web soon. A new security threat has been proposed that will force users to trust web sites or credential verifiers approved by any one of the 27 (or more) governments that issue electronic identifiers. Napolean and Bismark created codes, some parts of which survive even to this day, but the results turned out well for neither man, nor for the countries that adopted them. Some news reports follow showing where government effort can succeed:

1. [User Report from Chicago](https://thepointsguy.com/news/united-precheck-touchless-id-ohare/)
2. [Al Roker on La Guardia Terminal C](https://www.instagram.com/reel/C33LjrYOxbf/?igsh=MXh5c3dwNjBmdGhubw%3D%3D)
3. [Fox news on Las Vegas](https://fox59.com/news/national-world/airport-self-screening-security-lanes-being-tested-in-las-vegas/)
4. [TSA uses ‘minimum’ data to fine-tune its facial recognition](https://www.nextgov.com/emerging-tech/2024/01/tsa-uses-minimum-data-fine-tune-its-facial-recognition-some-experts-still-worry/393672/)
5. [Remote Identity Validation Tech Demo Challenge](https://www.dhs.gov/science-and-technology/news/2024/01/23/dhs-st-announces-track-3-remote-identity-validation-tech-demo-challenge)

So, what government solutions work? The US TSA is a remarkable example of applying new user access control that users really appreciate after long abuse by existing governmental solutions.

How do we get the same three-party win described above:

1. Issuers:  Digitalization can happen with little or no human costs. [Digitization excludes many people from social or economic life. They are left behind.](https://cacm.acm.org/blogcacm/digitization-puts-many-at-a-disadvantage/)
2. Holders: Can access digital credential where they need them and have them always with them + have full control of release of their data + verifiers accept them
3. Verifiers: Will need to be able to issue a query independent of issuer without extensive change to their existing processes since [Merchants Accept Digital Wallets but Will Not Invest in Innovation](https://www.pymnts.com/mobile-wallets/2023/merchants-accept-digital-wallets-will-not-invest-innovation/)

## Keep it Simple Stupid (KISS)

This is the motto for undergraduates entering the Mechanical Engineering program at MIT as reported by Seth Lloyd, a professor there. For digital id to work it must be really simple at the UX level. The following pages show a super great example which is designed to answer all of the normal questions a user has:

- Who: Starship Concert hall
- What: Requesting Proof of age
- When: Now (context)
- Where: Here (context)
- Why: Age Restrictions (the purpose of the request)
- How: This is optional and depends on whether more assurance is needed from the user - it may just be part of the UX on the phone and not on the display

THe conflation of What and Why may be indicative of the nature of the request from the user's perspective. It is worth a deeper use case analysis.
- Stax is now trying to acquire merchants that want to accept digital wallets. https://staxpayments.com/blog/digital-wallets-why-they-matter-and-how-to-accept/#:~:text=Q:%20Why%20should%20merchants%20support,enhancing%20the%20overall%20customer%20experience.
- Stripe Digital wallets 101: What businesses need to know about this payment method https://stripe.com/resources/more/digital-wallets-101


  ![proof of age](https://github.com/TomCJones/All-you-need/assets/11299542/470bc81d-f095-47f8-a652-dbe431d11a23)

