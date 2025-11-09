# Diligent Universe - Writers' Guide

**Author's Note**:

This project exists as an exploration of using GitHub Copilot and the agentic capabilities of that platform in developing and refining Agentic Workflows for a non-traditional application. We think of GitHub Copilot as a coding assistant, and it is, but by the nature of the frontier models we have access to it can be used to prototype and iterate on ideas outside of that narrow application.

Diligent makes use of the newest Agent framework introduced to Visual Studio Code to demonstrate how we can break down tasks into specialized agents, some using less expensive models to achieve a larger vision for a project.

See the `./github` directory for a view into the Agents, prompts and Instructions that make up the Writing Assistants for the series.

## Overview

**The Diligent** is a Star Trek-inspired narrative universe centered on the USS Diligent, a Starfleet rescue ship operating in Federation space. Unlike traditional Starfleet vessels focused on exploration or combat operations, the Diligent specializes in Search and Rescue (SAR) missions—responding to distress calls, performing emergency rescues, and handling humanitarian crises across Federation territory.

The universe explores what it means to be Starfleet when the mission is about *saving lives*, not fighting wars or charting stars. It examines dedication, sacrifice, improvisation, and the deeply human (and non-human) bonds formed under extreme pressure.

## Setting

### The USS Diligent

- **Class**: Older-generation starship (designed to operate efficiently with a small crew)
- **Configuration**: Rescue/SAR specialization rather than exploration or combat
- **Crew Size**: Approximately 100-120 officers and enlisted personnel, with a larger compliment of enlisted personnel than usual in Starfleet
- **Operations**: Responds to distress calls across Federation space; conducts emergency rescue operations in hazardous conditions
- **Culture**: Informal, efficient, results-focused. Protocol matters less than getting people home alive.
- **Status**: Not prestigious. SAR work isn't considered a path to advancement or glory in traditional Starfleet terms.

### Core Philosophy

The Diligent embodies a specific Starfleet principle often overlooked in exploration narratives: the rescue mission. Stories explore themes of:

- **Duty over personal advancement**: Characters who choose the mission over rank
- **Improvisation under pressure**: Making impossibilities work with limited resources
- **Practical ethics**: Real-time decisions about who can be saved and at what cost
- **Unexpected family**: Bonds formed through shared crisis rather than hierarchy
- **The cost of care**: The emotional toll of regularly confronting suffering and loss

## Main Characters

### Command Structure

#### **Captain Sev** - Commanding Officer
A Vulcan in their late 30s, recently promoted to Captain and newly assigned to the USS Diligent from the USS Intrepid (Vulcan science vessel). Sev was never quite suited to traditional Vulcan roles—creative where Vulcan culture demands pure logic—so Starfleet became their path forward. Arriving with rigid Intrepid-style command protocols and the belief that Diligent is a stepping stone to a "real" command, they must learn that creativity and logic can coexist.

*Key traits*: Initially formal and protocol-focused, risk-averse, uncomfortable with Diligent's casual culture. Over the season, gradually embraces creative problem-solving as valid logic rather than weakness.

*Character arc*: Learning that their creative instincts aren't Vulcan failure but Vulcan strength applied differently. Diligent forces Sev to integrate suppressed creativity with their logical training, ultimately discovering that this ship *is* the real command they needed.

#### **Lt. Commander Maren V'Lara** - Chief Rescue Officer
An Orion raised by Vulcans, V'Lara is the operational commander during active rescue missions. She has the highest successful rescue rate in her sector but has repeatedly declined promotion to Commander, preferring field operations. 30 years of Starfleet service, 48 years old.

*Key traits*: Stoic, mission-focused, uncompromising, willing to go to extreme lengths to save lives. Commands with intensity and competence; some crew find her intimidating.

#### **Senior Chief Petty Officer Tarek Jorin** - SAR Operations Chief
A Bajoran with Dominion War combat experience, Tarek is V'Lara's right hand during rescue operations. An engineering specialist-turned-SAR-expert who has deliberately declined promotion to Master Chief to remain in field operations. 5-7 years working with V'Lara in perfect sync.

*Key traits*: Calm under pressure, practical, protective of his team, gruff exterior with a soft heart. Sees SAR work as a spiritual calling—honoring those he couldn't save.

### Senior Staff

#### **Lt. Commander Sarona D'Greven** - Executive Officer/Second Officer
A Trill (unjoined) in her early 40s, D'Greven joined Diligent 2.5 years ago after a career in Sciences division. She expected to use her scientific expertise for survey work but instead manages administration and operations. Exceptionally organized and by-the-book; she's gradually learning to adapt to Diligent's informal culture and embrace improvisation.

*Personal conflict*: Her husband was recently joined with the Vess symbiont and is now a different person. She's grieving while deployed, managing marriage change alongside her career transition.

*Character arc*: Learning that "by the book" doesn't always save lives; discovering her own command instincts; proving her worthiness for Trill symbiont joining through exceptional performance.

#### **Lieutenant Michael Erickson** - Chief Engineer
A 26-28-year-old human from Alpha Centauri, Erickson recently transferred from a Galaxy-class starship as Chief Engineer of Diligent—his first independent command of an engineering department. He's technically brilliant but struggled with the transition from a large, routine operation to a small ship constantly operating at extremes.

*Key traits*: Over-explains when stressed, perfectionistic, eager to prove himself, still adjusting to creative problem-solving and calculated risks.

*Character arc*: Growing from anxious junior officer to confident department head; learning that managing a small ship's engineering during critical SAR missions is more impressive than specializing on a larger vessel.

#### **"Doc" Naveem** - Chief Medical Officer
A Deltan in his early 60s with extensive trauma medicine experience, Doc has served on Diligent for approximately 15 years across three tours. He's the institutional memory of the ship and has trained much of the current medical staff. Empathic abilities make him extraordinary at trauma medicine but psychologically exhausting work.

*Key traits*: Calm, Buddhist-like presence with quiet fatigue; veteran who's seen everything; sophisticated emotional understanding; uses rock climbing on the holodeck for mental health regulation.

*Background*: Two failed marriages, one daughter (late teens/early 20s) who struggles with his absence. He's at peace with his choices but carries the quiet sadness of sacrificed personal relationships for the mission.

*Mystery*: He's the only person who calls V'Lara "V"—the reason remains between them.

#### **Lt. (j.g.) Rachel "Sec" Harlow** - Chief of Security/Tactical
A 24-25-year-old human from an obscure Federation colony, Harlow is very junior for a department head. She joined Starfleet after the Dominion War (too young to serve) and romanticizes combat heroism. She believes she earned her Diligent posting through merit.

*Reality*: She's part of Admiral Seron's unofficial program—a Vulcan Admiral who quietly places talented but rough junior officers on Diligent for "seasoning." Most emerge as excellent officers. Harlow doesn't know this.

*Key traits*: Overcompensates for inexperience, sees threats everywhere, poor threat assessment, defensive about age, insists on being called "Sec" to sound tough.

*Character arc*: Discovering her true assignment (crisis point), learning that rescue work requires different courage than combat, earning genuine respect through growth and humility.

*Connection*: Admiral Seron is V'Lara's adoptive uncle. Doc Naveem recognizes the pattern and watches Harlow carefully—she reminds him of a previous "Seron project" officer who died on a mission.

## Core Relationships & Dynamics

### V'Lara & Tarek
The operational core of the ship. Five to seven years working together in perfect sync. V'Lara calls him "Jori" (no one else has this privilege). Tarek makes her plans work on the ground; she gives him the authority to execute. Mutual respect between professionals who've both refused advancement for the mission.

### V'Lara & Doc Naveem
Fellow veterans who understand the weight of the work. Doc calls V'Lara "V" (significant enough that junior crew speculate endlessly about their relationship). Mutual understanding from shared experience and sacrifice.

### D'Greven & V'Lara
Natural tension between formal/protocol-focused second officer and mission-focused rescue commander. They're learning to respect each other's approaches—D'Greven discovering that rules don't always apply in rescue operations; V'Lara recognizing the value of organization.

### Harlow & V'Lara
Harlow desperately wants V'Lara's approval. V'Lara maintains cold professionalism, barely tolerating her. V'Lara is protecting Harlow from repeating the mistakes of a previous officer (who died). When Harlow learns this history and discovers her "Seron project" status, their relationship will be severely strained.

### Harlow & Tarek
Tarek sees Harlow's eagerness and inexperience; she reminds him of green troops from the Dominion War. He's a patient but firm mentor who won't let her get herself or others killed.

### Erickson & V'Lara
V'Lara terrifies the junior engineer initially. Her demands seem impossible; he tries to explain technical limitations; she just stares until he figures it out. He gradually earns her respect by consistently delivering under pressure.

### Doc Naveem & Erickson
Doc recognizes the anxious junior officer's potential and is patient in mentoring him subtly.

### Captain & V'Lara
Initial tension between the Captain's procedural caution and V'Lara's operational decisiveness. V'Lara (also Vulcan/Vulcan-raised) recognizes what's happening: the Captain is struggling against their own creative nature. As the season progresses and the Captain learns to think creatively, V'Lara becomes quietly supportive. The finale moment of V'Lara's tacit approval signals the crew's recognition that the Captain has found their true command style.

### Captain & Doc Naveem
Doc recognizes the Captain's internal struggle immediately—a Vulcan at war with suppressed creativity. Becomes subtle mentor, helping the Captain understand that integration (logic AND emotion) beats suppression. Could share his own story of sacrifice and the cost of compartmentalization.

### Captain & D'Greven
Parallel struggle—both learning to let go of rigid protocols. Initially, the Captain might judge D'Greven for abandoning "proper" Starfleet procedure, then recognize they're on the same journey. Mutual support between two officers redefining competence.

### Captain & The Crew
Arrives with rigid expectations; gradually learns to trust the informal culture's actual efficiency. The tension between the Captain's initial command style and the crew's established culture drives much of the early season drama.

## Writing Guidelines & Tone

### Tone
- **Realistic urgency**: Rescue operations are chaotic, dangerous, and unforgiving
- **Character-focused**: The mission matters, but the people matter more
- **Bittersweet pragmatism**: Sometimes you save everyone; sometimes you save who you can; sometimes you don't save anyone
- **Informal competence**: Casual language, few ranks used, but absolute professionalism when it matters
- **Found family**: Crew bonded by shared purpose rather than hierarchy

### What Diligent Is
- A ship where people choose the mission over advancement
- A place where improvisation saves lives
- A team that responds to every distress call, knowing some will be tragic
- A culture that values competence and results over protocol and hierarchy
- A rescue operation, not a combat vessel

### What Diligent Is NOT
- A warship. Combat is a tool, not the purpose.
- Prestigious. Characters serve here because they're dedicated, not because they're ambitious.
- Predictable. SAR operations are inherently unpredictable and dangerous.
- Emotionless. The weight of the work accumulates; characters feel it.

## Story Types & Opportunities

### Rescue Operations
The core mission. Each rescue operation presents:
- **Technical challenges**: Structural damage, environmental hazards, system failures
- **Ethical dilemmas**: Who to rescue first? What level of risk is acceptable? When to abort?
- **Character development**: Crisis reveals character; how does someone behave under extreme pressure?
- **Relationship building**: Shared trauma bonds people

### Personal Stories
- Character-focused episodes exploring the cost of the mission
- How characters maintain relationships with people outside Starfleet
- The accumulation of loss and how experienced officers process it
- Coming-of-age arcs for junior crew
- Mentorship relationships tested under pressure

### Ship Politics
- Tension between Captain's command and V'Lara's operational authority
- Senior staff coordination during crises
- How informal culture actually improves efficiency
- Conflicts between different departments and philosophies

### Larger Conflicts
- Admiral Seron's mysterious program and its implications
- The truth about Harlow's assignment
- D'Greven's marriage crisis and identity transformation
- Doc's estranged daughter and regretted sacrifices
- Tarek's relationship with Vedek Franelis and political leverage
- The fate of the previous "Seron project" officer who died

## Character Development Framework

Characters on the Diligent evolve through:
1. **Pressure-tested competence**: Characters prove themselves through crisis
2. **Accumulated experience**: Each mission changes them slightly
3. **Relationship deepening**: Shared survival creates bonds
4. **Personal conflict**: Characters balance mission dedication with personal needs
5. **Gradual acceptance**: New crew members learn why Diligent's informal culture works

## Key Narrative Themes

- **Duty vs. Ambition**: People who choose meaningful work over career advancement
- **Improvisation vs. Protocol**: Learning when rules help and when they hurt
- **Visible & Invisible Costs**: Some costs are obvious (injuries, deaths); others are psychological (guilt, sacrifice, estrangement)
- **Family Beyond Blood**: Professional teams that become true family
- **Compassion Under Pressure**: Maintaining humanity in crisis situations
- **Legacy**: What each person contributes to the mission and to each other

## Resource Organization

- **Characters/**: Detailed profiles of all main and supporting crew
- **Plot Arcs/**: Major ongoing storylines and character arcs
- **Stories/**: Individual story outlines and concepts
- **Themes/**: Thematic exploration and philosophical questions

## For New Writers

1. **Understand the mission first**: SAR work is different from exploration or combat. It's about response, urgency, and pragmatism.
2. **Respect the informal culture**: The lack of formality isn't sloppiness; it's efficiency earned through years of crisis operations.
3. **Remember the stakes**: Lives are at stake. Characters feel this weight constantly.
4. **Develop characters through crisis**: Show who people are when everything goes wrong.
5. **Honor the veterans**: Doc and V'Lara and Tarek have earned their positions through decades of service. Respect their expertise.
6. **Explore the tensions**: The interesting stories often come from conflict—between safety and rescue, between protocol and results, between mission and personal life.
7. **Balance hope and realism**: Not every mission ends in triumph. Sometimes the victory is smaller than hoped.

---

*The Diligent universe is about the people who show up when no one else can. It's about competence, sacrifice, and the extraordinary things ordinary people do under pressure.*
