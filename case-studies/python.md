# Python

Project website: [Python.org](https://www.python.org)
Project governance documents: [PEP 13 - Python Language Governance](https://www.python.org/dev/peps/pep-0013/); [Python Software Foundation bylaws](https://www.python.org/psf/bylaws/)
Case Study Author(s): Shauna Gordon-McKeon ([@shaunagm](https://github.com/shaunagm))

## Summary

## Questions

### Current governance process

#### What is the legal structure of the project, if it has one?

Python consists of two distinct arms: the Python language team, and the Python Software Foundation (PSF).

The PSF is a member-elected 501(c)3 non-profit with a nine-member board of directors.  They hold the intellectual property rights behind Python, however Python is [freely licensed](https://en.wikipedia.org/wiki/Python_Software_Foundation_License) so anyone is free to use, modify and redistribute Python.

The Python language team has no distinct legal structure from the PSF but nevertheless operates independently.

#### What people have "leadership" positions? How do they get those positions?  Are they voted in, appointed, self-nominated, randomly chosen, hired, etc?

_Python language team_  

There are two main types of leaders in the Python language community.  The larger group is the core team.  New members can apply to join the core team and, after a trial period during which they're sponsored by an existing core team member, the current core team votes on whether to admit them.  If two-thirds approve of the new member, and no steering council member vetoes, then they become a core team member. 

Additionally, a five person steering council helps make high-level and controversial decisions about the project.  This council is nominated by and elected by the core team.  They hold their positions for the length of three Python releases, 

There are some less well-defined positions within the language team as well.  Core team members can be appointed to positions of authority, such as the release manager, by the steering council.  There is also an experts index which provides guidance on which core team members should take the lead in making decisions about specific areas of Python.  This is often though not exclusively through being made the "BDFL-delegate" who decides on whether a Python Enhancement Proposal should be accepted or rejected.

_Python Software Foundation_

The PSF, as previously stated, is a member-elected non-profit.  The PSF has [five kinds of members](https://www.python.org/psf/membership/#what-membership-classes-are-there):

| Type  | Criteria to join | Has voting rights  | Expires after |
| ------------- |:-------------:| -----:| -----:|
| basic      | agree to code of conduct | no | one year |
| supporting   | make an annual donation of $99 or more | yes |one year |
| managing | dedicate 5 or more hours a month to a PSF working group | yes |one year |
| contributing | dedicate 5 or more hours a month to work creating or maintaining an open source project that advances the PSF mission | yes |one year |
| fellows | nominated by community for "extraordinary efforts", voted on by members | never |

Members elect the board of directors on a staggered basis, with three cohorts each serving three-year terms.  Elections are held annually, and there are currently thirteen directors. The board then appoints officers of the PSF such as President, Executive Director, etc.

#### Is there a voting mechanism?  How often do votes actually happen?  Is there a veto mechanism?  How often is it actually used?  Are these votes recorded anywhere?

There are a variety of situations where votes occur.  These include:

_Python Software Foundation_

- The PSF members elect directors to the board of directors, annually in the late spring. **CITE**Members do not vote in any other circumstances, for instance there is no mechanism for referendums.

- The PSF directors elect the President and officers of the PSF.  **CITE**How & how often?  

- The PSF board of directors votes on [resolutions](https://www.python.org/psf/records/board/resolutions/), which occur at a rate of a dozen or so a month.  These resolutions cover a variety of matters such as authorizing small grants, bestowing community awards, and approving sponsorship applications.

_Python language team_

- The core team elects the five member steering council.  Their term lasts for the length of three releases, typically around four or five years.  If a council member resigns or can no longer serve, the remaining council [votes on a replacement](https://www.python.org/dev/peps/pep-0013/#vacancies).  Steering council votes are recorded as PEPs, for example [PEP-8100](https://www.python.org/dev/peps/pep-8100/) records the first steering council election in January 2019.

- The core team votes to approve new members on an ad hoc basis.  New members need approval by two-thirds of the existing core team.

- The steering council can vote to expel a core team member through a two-thirds vote.  Such a vote has never been held.

- The core team can vote to remove individual steering council members or to disband the steering council as a whole, through a two-thirds vote.  Such a vote has never been held.

- The core team may vote to amend [PEP-13](https://www.python.org/dev/peps/pep-0013/), the Python language team's governance document, with a two-thirds vote.  PEP-13 [has been amended once](https://www.python.org/dev/peps/pep-0013/#history-of-amendments).

Conversely, veto mechanisms are rare.  Currently there is only one formalized veto process, on the Python language team, where the steering council may veto the addition of a new core team member, even if they have the requisite two-thirds vote by the existing core team.  Such a veto has never been exercised.

#### What kinds of decisions does the project have to make?  How do they make those decisions?  Are alternate processes used when decisions are disputed or controversial? (If decisions are made via votes, feel free to simply refer the reader back to the previous question.)

Some common types of decisions that need to be made include:

_Python Software Foundation_

* What groups should receive grants.
* Where PyCon should be held.
* What the Code of Conduct is and whether it has been violated.
* Whether applicants should be accepted as sponsors.
* What community members should get awards.

_Python language team_

* Whether a feature should be added to Python and on what time scale, also known as roadmapping.

TODO: add explanations for each decision-type as to how they're made, what happens in case of controversy

#### Can community members get special statuses and if so, how?

Generally speaking, there are no mechanisms to give community members special status apart from two options: on the Python language side, delegation of authority to individuals via roles such as "release manager" by the steering council, and on the PSF side, the election of "Python fellows".

#### Can community members be suspended or banned from the community, or otherwise disciplined, and if so, how?

The PSF has a [Code of Conduct](https://www.python.org/psf/codeofconduct/) which the Python language team [also uses](https://devguide.python.org/#code-of-conduct).  The CoC is fairly vague but does provide two simple reporting options: individuals can email the entirety of the PSF staff and directors, or they can email only the executive director of the PSF.

PyCon US is Python's largest community event, and is run by the PSF.  The event has its own,much more detailed [Code of Conduct](https://us.pycon.org/2019/about/code-of-conduct/), which includes several more mechanisms for reporting as well as detailed incident handling procedures.  *All official PyCons must have a similar Code of Conduct.* (CITATION NEEDED)After each PyCon, the PSF issues a [Code of Conduct Transparency Report](https://pycon.blogspot.com/2018/06/pycon-2018-code-of-conduct-transparency.html).  Bans from PyCon appear to happen infrequently but regularly.  

Recently controversy arose when PyCon [refused to ban sponsor DataCamp](https://pycon.blogspot.com/2019/04/an-update-regarding-pycon-2019-sponsor.html), a company which had recently attracted attention for failing to address issues of sexual harrassment. The PSF [gave the following reasoning](https://pycon.blogspot.com/2019/04/an-update-regarding-pycon-2019-sponsor.html): "PyCon's sponsorship policies and Code of Conduct do not support removing a sponsor for situations that happen outside of PyCon. The Python Software Foundation Board will be meeting at PyCon and discussing ways in which PyCon's sponsorship policies may need updating."

Members of the core team may be suspended or expelled by the steering council.  So far, no such incidents have occurred.  

It is unclear how frequently (if at all) members of the PSF are suspended or banned.

### Governance History

#### Has the project always had this governance structure?  If not, what were the previous governance structures?

The Python language team recently underwent significant governance changes.  Previously, it had been headed by Python creator Guido van Rossum as the "Benevolent Dictator for Life".  

TODO: ask re: previous structures for the PSF.  May also want to ask re: how the previous structure of the Python language team evolved - for instance, rules re: core team votes, the PEP process, etc.

#### Does your project have clear guidelines for how to change its governance structure?  Has it always had those guidelines?  If not, has the lack of clear guidelines on how to change the governance structure caused any challenges, now or in the past?

#### Why did you choose the structure you did?  If there was a previous, different structure, what precipitated the change to your current structure?

See ["A New Era in Python Governance"](https://www.youtube.com/watch?v=mAC83JVDzL8), a talk from PyCon 2019, for more details about the previous governance structure and the transition process.

### Community & Governance

#### How much knowledge do you think the project's community has about its governance?  How often does the community explicitly talk about project governance?

#### What pain points is your governance process prone to?  How is that discussed in the community, if at all?  (Note that the community may discuss pain points caused by governance without explicitly discussing it as a governance issue.)

#### What do you think the governance process does really well?  How is that discussed in the community, if at all?  (Note that the community may discuss things that the governance process does well without explicitly discussing it as a governance issue.)

#### What particular values does your community care about, and do you think the governance process reflects that?

### Community Discussion

#### Where do you hold discussions? (GitHub, mailing lists, face-to-face meetings, and so on.)

The Python community is large and diverse, and conversation happens across many channels.  Limiting ourselves to places where governance-related decisions may be discussed:

_Python language team_

* discuss.python.org
* other mailing lists?  maybe also the slack channel?
* issue trackers
* language summit at PyCon

_Python Software Foundation_

* board meetings (are minutes made available anywhere?)
* PyCon members lunch
* any other forums????

#### Who has access to those discussion channels?  How is this access granted/revoked?

#### Who, if anyone, moderates those discussions?

#### Has the community had issues with heated or controversial discussions?  How has that impacted the community?

### Domain-Specific Questions: Software Projects

#### How do you decide when a release happens and what goes into it?

Python selects a release manager who manages two consecutive releases.  That person must be a member of the core team for at least the time that's expected of the role, which is three years per release with one year overlap, for a minimum five year commitment.  

No release manager has been selected via the current governance process, but previously the release manager was selected by the "Benevolent Dictator For Life".

#### How do you decide who gets commit access?

All members of the core team have commit access.  So, anyone who has been approved via a two-thirds vote of existing core team members have commit access.

#### Do you have a RFC/PEP-like process?

Python indeed has a PEP-like process: [Python Enhancement Proposals (PEPs)](https://www.python.org/dev/peps/).  From [PEP-0001](https://www.python.org/dev/peps/pep-0001/):

    PEP stands for Python Enhancement Proposal. A PEP is a design document providing information to the Python community, or describing a new feature for Python or its processes or environment. The PEP should provide a concise technical specification of the feature and a rationale for the feature.

    We intend PEPs to be the primary mechanisms for proposing major new features, for collecting community input on an issue, and for documenting the design decisions that have gone into Python. The PEP author is responsible for building consensus within the community and documenting dissenting opinions.

PEPs can be proposed by a core team member or by someone who finds a core team member to sponsor the proposal.