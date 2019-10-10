# Suggested structure

The suggested structure should serve as sufficient for a wide range of
organization sizes. A variety of implementations should be considered based on
the sizes of organizational structure. 

The master state of the organization should be held ideally in a single
location, however replicated wherever possible. This said, informal
documentation can still acceptably be held outside of the core organizational
state. 

The organizational state is broken down in the following ways: 
 - high-level directives 
 - enforceable and explicit agreements based off of directives 
   - decision categories (non-mutual exclusive) 
 - on-going activities upheld by members 
 - responsibilities / privileges per member 


## Phase 1: Assessement 

Implementing the suggested structure may prove to be difficult depending
on what existing structures are in place. During the initialization phase
a utility should be mandated and populated in an attempt to reflect the 
organizations existing structures _and not_ in an attempt to reflect the 
most ideal form of the organization. This process enables the utility to 
"get it's feet off the ground" such that further conversations can be had
which mature the organization to a more ideal state. 

The following is the suggested initialization steps to be taken:
 1. Existing organization authority mandate the use of a single utility which
    meets all the requirements of a [legitamte coordination utility](TODO)
(suggested utility provided in this document).  At this point this new
structure should be declared as non-ratified.
 2. Existing organization leadership prepopulate tutorial information and
    "loose" documentation within the utility
 2. Existing organization leadership concisely define all degrees of membership
    within the organization, most importantly the list of all existing members
must be tabulated with distinction documented as to whom is a "full" member or
some form of partial membership. In this context full members are required to
fully engage and arrive at consensus within this process, whereas non-full
members, may not be required to participate.  
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
suggested-activities. Note that all these items must be clearly labelled as
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

 
## Phase 2: Ratification

Congratulations, you've made it to Phase 2. At this point you've agreed on 
what the state of the organization looks like whether we like how it looks or not. 
Before ratifying the structure voting powers should be initialized. The suggested voting
power mechanism is as follows: 
 1. Existing leadership creates the initial list of decision making categories
 2. All members review and come to consensus on the category list, potentially 
    adding or changing categories during this step. 
 3. All members rank other members confidence in other members capabilities to 
    rank voting powers (meta voting power). When members feel unqualified 
    to provide a ranking, ranking should simply not be provided. 
 4. All members rank all other members on their suggested weights per voting 
    category where they feel confident to do so. 

## Phase 3: Rectification

Now that the existing structures have been successfully documented and any
ratification blockers eradicated, it is time to rectify the organization.  


## Suggested further process

The above suggested structure is a baseline structure which arbitrary further
processes can be implemented within. Herein are further suggested processes which 
will serve as a baseline 



------------------------------------------------------

### Implementation on github

All described functionality can be fulfilled as a part of a github repository.
The breakdown is as follows: 

 - organization state: - held in repository file structure
 - voting: 

#### File structure

```
├── README.md                      // banner, overview text, hyperlinked table of contents 
├── Directives.md                  // high level directives
├── Agreements.md                  // agreements based off of directives and decisions
├── Activities.md                  // list of all active functions which projects or the organization participates in
├── Members/
│   ├── Inactive/                  // Inactive members should still be kept on record
│   ├── YourNameHere.md            // Active members 
│   └── YourFriendsName.md
├── Decision-Records/              // Complete documentation of decisions made
│   ├── GeneralDR_001.md           // General decisions which merit everyone's attention,  
│   ├── GeneralDR_002.md           //   or decisions which belong equally to multiple categories 
│   ├── ...
│   ├── ExampleCategory1/          // Decisions pertaining only-to, or primarily-to a specific category
│   │    ├── DR_001.md
│   │    ├── DR_002.md
│   │    └── ...
│   │── ExampleCategory2/
│   │   ├── DR_001.md
│   │   ├── DR_002.md
│   │   └── ...
│   └── ... 
└── Docs/                         // most docs should be referenced in Agreements.md
    ├── Tutorials/                // tutorials on how to interact with 
    ├── Contracts/
    └── Policies/                    
        └── CODE_OF_CONDUCT.md    // how users ought to interact with each other
```
