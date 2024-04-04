# Users are all you need

When we look at successful deployments of human access to technology, we find examples like OpenID Connect where users already had accounts at Yahoo and Google, Then the smaller web sites needed to rapidly enroll users who were overwhelmed by the shear complexity and confusion of too many sites asking them to create accounts that required the sort of secret sharing passwords that human are not good at remembering. Let’s consider the parties to the effort and why each thought that it was a win for them.

1. Google and Yahoo cemented their role as gatekeepers for new technology.
2. Emergent web sites were able to get users to create accounts easily.
3. Users had few secrets that they needed to both remember and maintain.

Also, the proposed solution was remarkable simple. Any programmer could gin up a new web site with full user account control in a matter of hours. Compare this to what happens when a government decides to create a user access control system.

Government, schools and employers have complete control of user access technology and are able to impose whatever solutions that want on their subjects. The results tend to be ugly, hard to maintain and difficult to change. In sum, top-down solutions are seldom popular with users. We have some specific examples of problems created by this approach: prompt fatigue and insecurity. Somehow the EU parliament got the idea that cookies were evil because of the way that cookies enabled tracking of people, so they gave users the right to ask for cookies not to be collected. The cookie threat has been (soon) eliminated by the deprecation of third-party cookies, but the incessant and insensible barrage of requests to allow cookies continues to force the users to continuously make security choices to the point where they just accept everything. The security threat to user private data is magnified by the judges in the EU that created the “right to be forgotten”, which resulted in the collection of all those damaging secrets into a single online data base so that they WOULD NOT be displayed in a search but certainly will show up, in their entirety, on the dark web soon. A new security threat has been proposed that will force users to trust web sites or credential verifiers approved by any one of the 27 (or more) governments that issue electronic identifiers. Napolean and Bismark created codes, some parts of which survive even to this day, but the results turned out well for neither man, nor for the countries that adopted them. Some news reports follow showing where government effort can succeed:

1. [User Report from Chicago](https://thepointsguy.com/news/united-precheck-touchless-id-ohare/)
2. [Al Rocker on La Guardia Terminal C](https://www.instagram.com/reel/C33LjrYOxbf/?igsh=MXh5c3dwNjBmdGhubw%3D%3D)
3. [Fox news on Las Vegas](https://fox59.com/news/national-world/airport-self-screening-security-lanes-being-tested-in-las-vegas/)
4. [TSA uses ‘minimum’ data to fine-tune its facial recognition](https://www.nextgov.com/emerging-tech/2024/01/tsa-uses-minimum-data-fine-tune-its-facial-recognition-some-experts-still-worry/393672/)
5. [Remote Identity Validation Tech Demo Challenge](https://www.dhs.gov/science-and-technology/news/2024/01/23/dhs-st-announces-track-3-remote-identity-validation-tech-demo-challenge)

So, what government solutions work? The US TSA is a remarkable example of applying new user access control that users really appreciate after long abuse by existing governmental solutions.

How do we get the same three-party win described above:

1. Issuers: Can happen with little or no human costs
2. Holders: Can access remotely and have it always with them + has full control of release of their data
3. Verifiers: Will need to be able to issue a query independent of issuer without extensive change to their existing processes

## Keep it Simple Stupid (KISS)

This is the motto for undergraduates entering the Mechanical Engineering program at MIT as reported by Seth Llyod, a professor there. For digital id to work it must be really simple at the UX level. The following pages show a super great example which is designed to answer all of the normal questions a user has:

- Who: Starship Concert hall
- What: Requesting Proof of age
- When: Now (context)
- Where: Here (context)
- Why: Age Restrictions (the purpose of the request)
- How: This is optional and depends on whether more assurance is needed from the user - it may just be part of the UX on the phone and not on the display

THe conflation of What and Why may be indicative of the nature of the request from the user's perspective. It is worth a deeper use case analysis.

  ![proof of age](https://github.com/TomCJones/All-you-need/assets/11299542/470bc81d-f095-47f8-a652-dbe431d11a23)



