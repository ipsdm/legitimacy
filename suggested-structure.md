# Suggested Structure

The suggested structure should serve as sufficient for a wide range of organization sizes. 
A variety of implementations should be considered based on the sizes of organizational structure. 

The master state of the organization should be held ideally in 
a single location, however replicated wherever possible.
This said informal documentation can still acceptably be held outside
of the core organizational state. 

The organizational state is broken down in the following ways: 
 - High-level directives 
 - Enforceable and explicit agreements based off of directives 
   - Decision catagories (non-mutual exclusive) 
 - On-going activities 
 - Responsibilities / privledges of all members
 - 

The following utilities should also be considered 
 - Rapid Polling
 - Voting



### Implementation on github

All described functionality can be fulfilled as a part of a github repository.
The breakdown is as follows: 

 - organization state: - held in repository file structure
 - voting: 

#### file structure

```
 ./README.md                       // banner, overview text, hyperlinked table of contents 
 ./Directives.md                   // high level directives
 ./Agreements.md                   // agreements based off of directives and decisions
 ./Activities.md                   // list of all active functions which projects or the organization participates in
 ./Members/
      Inactive/                    // Inactive members should still be kept on record
      YourNameHere.md              // Active members 
      YourFriendsName.md
      ... 
 ./Decision-Records/               // Complete documentation of decisions made
      GeneralDR_001.md             // General decisions which merit everyone's attention,  
      GeneralDR_002.md             //   or decisions which belong equally to multiple categories 
      ...
      ExampleCategory1/            // Decisions pertaining only-to, or primarily-to a specific category
           DR_001.md
           DR_002.md
           ...
      ExampleCategory2/
           DR_001.md
           DR_002.md
           ...
      ... 
 ./Docs/                           // most docs should be referenced in Agreements.md
      Tutorials/                   // tutorials on how to interact with 
      Contracts/
      Policies/                    // 
           CODE_OF_CONDUCT.md      // how users ought to interact with eachother
```
