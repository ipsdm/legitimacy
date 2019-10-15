# Structure

The suggested structure provided herein should serve as sufficient for a wide
range of organization/group sizes. This file is broken down by the following
subsections:
 - [Platform](./structure.md#Platform) - Discussions surrounding platform
   requirements for implementing the structure. 
 - [State](./structure.md#State) - Outline of the minimum elements of the state
   of the structure.  
 - [Process](./structure.md#Process) - Tangible process for transitioning to
   this structure. 

Additionally, at the end of this file a discussion surrounding an example
implementation on github is provided.


## Platform

A variety of implementations of said structure should be considered based on
the organization. Amending or modifying the provided structures to the specific
needs of your organization is encouraged through the formation of new top-level
[agreements](./structure.md#Agreements). 

The master state of the organization should be held in a single location
(however replicated wherever possible). This said, informal or inaffectual
documentation can still acceptably be held outside of the core organizational
state, so long as it is explicitly and clearly designated as inaffectual. The
following are the requirements for any platform chosen: 
 - clear version history, 
 - the ability to suggested changes, 
 - discussion threads on suggested changes, 
 - general discussion threads without suggesting changes, 
 - clear history of all discussions, 
 - verifiable voting, 
 - replicatability of all state.


## State

An organization's state should be broken down approximately into the following
sections:

### Directives

high-level directives of the organization. All agreements and decisions made
should be able to be referenced within the context of the directives.  

### Definitions

Definitions of agreed upon terminology used throughout the organizations state.
This section should include a definition of different levels of membership
within the organization.  

### Agreements

Concisely worded statements agreed upon by all members of the organization to
aid the progression of the company directives. Agreements should be enforceable
within the organization. The agreements section need-not contain an exhaustive
list of all decisions made within the company, but a list _of how_ decisions
are made, and _of how_ process is changed. All agreements should be made via
the [consensus process](./definitions.md#Consensus), any single
disagreement on any element within any agreement is enough to bring that
agreement into a state of [contention](./definitions.md#Contention). 

### Decision Records

Decision records document what, why, by who, any particular decision is made.
In many organizational structures it is anticipated that many decisions will be
made _outside_ of an organization-wide consensus process. Some organizations
may choose to categorize kinds of decisions, and grant decision making
privileges to certain members or sub-groups within the organization. The form
by which decisions are permitted to be made must be documented and stated 
within the organizations Agreements. 

The suggested structure for contents of each decision record is the following:
 - Decision 
   - State the decision as concisely as possible. 
   - By Authority Of
     - State the members/agreements which legitimize this decision.
 - Justification
   - Provide a complete list of rational/justifications as to why this decision was
     made.  
 - Link
   - List references to other decisions records and agreements which form the
     basis for this decision. If new activities are formed as a part of this
     decision, the activity should be linked here as well.  This is especially
     important for indexing and updating this decision when upstream
     agreements/decisions are modified or overturned. 
 - New Agreements Formed
  - List any new agreements formed during the ratification of this decision.
 - Supplementary Information
 - Other non-mandatory sections:
   - raw conversations/discussions
   - voting records 
   - external references
   - etc.

### Activities 

An activity is defined as an ongoing responsibility within an organization.  It
is anticipated that most organizations will have ongoing processes which either
do or do not consist of making formally documented decisions. If an activity
involves making important decisions, those decisions should be documented and
categorized through the same structure. Where activities do not involve making
many formally documented decisions it is important that those activities be
clearly documented in a special _Activties_ section of organization state. 

All activities should _belong_ explicitly to a member of sub-group of members,
whereby the responsible parties for engaging in that activity should be listed
directly beside the activities definition, as well as in any relevant member
cards. 


### Members

Each member should maintain a "member-card" which document all core facets of
how each particular member has and will engage with the organization. This
should consist of an exhaustive list of members': 
   - Responsibilities
     - Desired Changes
   - Privileges
     - Desired Changes
   - Attributes
   - Achievements
   - Contracts

Modification of members cards must be done with the consent of that members,
but should not exclusively controlled by that member. For instance, in most
instantiations of legitimate structures it should be permissible to suggest
changes to both your own card as well as others member cards. In either case
a process of accepting amendments to member cards must be undertaken. 


## Process
Implementing the suggested structure may prove to be difficult depending on
what existing structures are in place. The goal of this section is to provide a
comprehensive transition strategy from existing structures to the most
legitimate structure conceivable. This transition period may take anywhere from
a week to several years depending on the size of the organization.

### Phase 1: Assessment 

During the initialization phase a utility should be agreed upon through verbal
consensus or mandated in a [moment of
autocracy](./definitions#Moment-of-autocracy). The utility should then be
collectively populated in an attempt to reflect the organizations existing
structures _and not_ in an attempt to reflect the most ideal form of the
organization. This process enables the utility to "get it's feet off the
ground" such that further conversations can be had which mature the
organization to a more ideal state. 

The following is the suggested initialization steps to be taken:
 1. Existing organization authority mandate the use of a single utility which
    meets all the requirements of a [legitamte coordination utility](TODO)
(suggested utility provided in this document).  At this point this new
structure should be declared as non-ratified.
 2. Existing organization leadership pre-populate tutorial information and
    "loose" documentation within the utility
 2. Existing organization leadership concisely define all degrees of membership
    within the organization, most importantly the list of all existing members
must be tabulated with distinction documented as to whom is a "full" member or
some form of partial membership. In this context full members are required to
fully engage and arrive at consensus within this process, whereas non-full
members, may not be required to participate. This documentation should be added
to the organization's [Definitions](./structure.md#definitions). 
 2. All members perform tutorial exercises familiarizing themselves with the
    mandated coordination utility
 3. Within this utility, all members self-document all existing privileges and
    responsibilities currently held within the organization attempting to be as
truthful and comprehensive as possible. At this point members should refrain
from documenting what _they would like_ their privileges and responsibilities
to be but instead only focus on what privileges and responsibilities they
truthfully already hold within the organization.  
 4. Existing organization leadership populated a best approximation of the
    ideal company suggested-directives, suggested-agreements, and
suggested-activities. Note that all these items must be clearly labeled as
suggested and not mandated.
 6. A table (dubbed "the matrix") should not be created which lists documents,
    and their state of review from all the full members.
 5. All organization members should now review and add suggestions to all other
    members self-documented privleges and responsibilities as well as suggested
directives, agreements, and activities, for truthfulness as to closeness to
approximation of the existing structure - again _not_ in attempt to hone in on
what is most ideal, but only to attempt to approximate what the _existing_
structures/hierarchies truthfully are. Once each member is satisfied with a
document and all their questions/concerns have been addressed they should mark
the document as "approved at version-XXX" within the matrix, where the
"version-XXX" represents a version number or commit hash of the document. It is
anticipated that several iterations may be required in order to arrive at a final
state of consensus for all the most recent document versions. 

 
### Phase 2: Ratification

Congratulations, you've made it to Phase 2. At this point you've agreed on what
the state of the organization looks like whether we like how it looks or not.
Before ratifying the structure, voting powers should be initialized. This is
especially important as it serves as the basis or legitimacy for old structures
to be rectified.  It's recommended that the weights are independent for
sub-categories of decision making within the organization. The suggested
approach for determining the weight value for each member for each category is
to "confidence-weight"-average all members suggested weights for all other
members. Here the _confidence-weight_ refers to a non-weighted simple average
of all members for all other members as to what their confidence is in that
member to choose others weights. By having a confidence weight, leadership
within an organization which has earned the respect may be granted exceptional
privileges of more readily determining others decision making weights. 

A generalized calculation for the aforementioned structure is as follows:

```
MemberX_confidence_weight = Sum(confidence_weights TO MemberX) 
                            / Sum(confidence_weights) 
MemberX_categoryY_weight  = Sum(confidence-weighted categoryY_weights TO MemberX) 
                            / Sum(confidence-weighted category weights FOR categoryY) 
```

The suggested process for determining voting power is then as follows: 
 1. Existing leadership creates the initial list of decision making categories
 2. All members review and come to consensus on the category list, potentially 
    adding or changing categories during this step. 
 3. All members rank other members confidence in other members capabilities to 
    rank voting powers (meta voting power). When members feel unqualified 
    to provide a ranking, ranking should simply not be provided by that member.
 4. All members rank all other members on their suggested weights per voting 
    category where they feel confident to do so. 
 5. Decision making weights per category are weight-averaged and results 
    made accessible. 
 6. Members of organization perform vote to ratify the new structure.

### Phase 3: Rectification and Continued Engagement

Now that the existing structures have been successfully documented and
ratified, it is time to rectify the organization. It is at this point that
members should begin creating suggestions to the organizations through this new
structure.  This will likely beginning with suggestions for decision making,
and ways in which to modify the organizations processes. The sky is really the
limit here.  

During the initialization of this process its suggested that one of the first
new agreements is to impose some form of queue and rate limit for all incoming
suggestions to core-structure modification. This will help to prevent the
scenario where there are too many suggestions to provide a useful level of focus 
and critical feedback on each decision. 

Beyond this initial rectification, the processes should continue to adapt to the 
changing needs of the organization. Good luck! 


------------------------------------------------------

## Example implementation using github

All described required functionality described in
[Platform](./structure.md#Platform) can be fulfilled as a part of a github
repository:
 - clear version history, 
   - git version history on repository
 - the ability to suggested changes, 
   - pull requests
 - discussion threads on suggested changes, 
   - pull request reviews  
 - general discussion threads without suggesting changes, 
   - github issues.
 - clear history of all discussions, 
   - All history easily accessible in current or closed issues/pull-requests. 
 - verifiable voting, 
   - (weakest point) can be achieved through either editing a github
     issue/comment box; or sending commits to a file which contains votes
     (commit history is verifiable). 
 - replicability of all state.
   - core state replicated with `git`, issues and pull request threads
     exportable through github APIs

Within github the following file structure could be used in as the `git`
repository to represent the organizational state: 

```
./
├── README.md                      // banner, overview text, hyperlinked table of contents 
├── directives.md                  // high level directives
├── agreements.md                  // agreements based off of directives and decisions
├── definitions.md                 // list of agreed upon definitions relavent to the organization structure
├── activities.md                  // list of all active functions which projects or the organization participates in
├── members/
│   ├── inactive/                  // Inactive members should still be kept on record
│   ├── your-name-here.md          // Active members 
│   └── your-friends-name.md
├── decision-records/              // Complete documentation of decisions made
│   ├── generalDR-001.md           // General decisions which merit everyone's attention,  
│   ├── generalDR-002.md           //   or decisions which belong equally to multiple categories 
│   ├── ...
│   ├── example-category1/         // Decisions pertaining only-to, or primarily-to a specific category
│   │    ├── DR-001.md
│   │    ├── DR-002.md
│   │    └── ...
│   │── example-category2/
│   │   ├── DR-001.md
│   │   ├── DR-002.md
│   │   └── ...
│   └── ... 
└── docs/                          // most docs should be referenced in Agreements.md
    ├── tutorials/                 // tutorials on how to interact with 
    ├── contracts/
    └── policies/                     
        └── CODE-OF-CONDUCT.md     // how users ought to interact with each other
```

For specially permissioned actors inherent to github such as, the repository
admins, or members of the github `CODEOWNERS` file, explicit agreements should
be made such that if a specially permissioned actor was to breach their
agreement consequences could be enforced.

For more details on this example structure see the [template](./template/)
