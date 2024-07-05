# Cyber-Security Hackathon
`ReadMe Last updated on: 2024/07/05 (YYYY/MM/DD)`

## Table of Content
| Content                                                       |
| ---                                                           |
| [Introduction](#content-introduction)                         |
| 🧭[Repository Navigation](#content-repositorynavigation)      |
| 🛣️[Hackathon FlowChart](#content-hackathonflowchart)          |
| 🦮[Guidance](#content-hackathonguidance)                      |

---
## <p id = "content-introduction">Introduction</p>
This is a Repository that will contain all the resources and assets for the Cyber-Security Hackathon `Coolness` hosted by the `Department of Coolness` of the `College of Coolness, Shillong, Meghalaya`




---
## <p id = "content-repositorynavigation">Repository Navigation🧭</p>
### [Challenges🪨][DirectoryLink Challenges]
- #### OSINT
- #### Digital Forensics
- #### Miscellaneous
### [Rules and Regulations⚖️][DirectoryLink-RulesAndRegulations]
- #### [Entry Requirement][DirectoryLink EntryRequirement]
- #### [Adding Challenges][DirectoryLink AddingChallenges]
- #### [Repository][DirectoryLink_Repository]
### [Hackathon Management💼][DirectoryLink HackethonManagement]





---
## <p id="content-hackathonflowchart">Hackathon FlowChart</p>
### Over-view
```mermaid
graph TB
    %%Node definition
    FA[Feasibility Analysis📊]
    TF[Teams Formation👥]
    CC[<a href="#mermaid-creatingchallenges">Create Challenges</a>🛠️]
    AE[Advertise Event📰]


    %%Node Connection
    FA-->TF
    TF-->CC
    CC-->AE

```


### <p id="mermaid-creatingchallenges">Creating Challenges</p>

```mermaid
graph TB
    %%Node definition
        CC[Create Challenge]
        CU[Challenge Update]
        FG[Follow Guidelines]
        CA{Council Approval}
        AC[Add Challenge]
        PT[Play Test]
        PTR{Play Test Result}

    CC[Create a Challenge]-->FG[Apply predefined rules<br>on challenge creation]
    FG-->CA{The Council<br>evaluates the Challenge}

    %%Challenge Acceptance
        CA--Accepted🟢--->PT
        CA--Refected🔴-->CC
        CA--Changes Needed🟡-->CU[Update the Challenge]
        CU-->FG
    
    %%Play Test
    PT[A diverse dontrol group<br>play tests the challenge]-->PTR
    PTR--Positive🟢-->AC
    PTR--Negative🔴-->CA

```




---
## <p id="content-hackathonguidance">Hackathon Guidance🦮</p>
### Over-View
- By [Hackerearth][WebLink Hackerearth_HowToOrganizeAHackathon]









<!--MarkDown Document Links-->

<!--Folder: Challenges-->
[DirectoryLink Challenges]: ./Challenges/

<!--Folder: Rules and Regulation-->
[DirectoryLink-RulesAndRegulations]: ./Rules%20and%20Regulations/
[DirectoryLink EntryRequirement]: ./Rules%20and%20Regulations/Entry%20Requirement.md
[DirectoryLink AddingChallenges]: ./Rules%20and%20Regulations/Adding%20Challenges.md
[DirectoryLink_Repository]: ./Rules%20and%20Regulations/Repository.md

<!--Folder: docs-->
[DirectoryLink HackethonManagement]: ./docs/Hackathon%20Management.md

<!--Guidance Links-->
[WebLink Hackerearth_HowToOrganizeAHackathon]: https://www.hackerearth.com/community-hackathons/resources/e-books/guide-to-organize-hackathon/