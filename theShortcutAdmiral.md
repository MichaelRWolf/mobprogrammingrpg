# Shortcut Admiral

A supportive role focused on improving individual and team efficiency through keyboard shortcut education and guidance.

## The Skills to Learn

- Observing patterns in Driver behavior and tool usage
- Identifying opportunities for keyboard shortcut improvements
- Providing timely, non-intrusive shortcut suggestions
- Balancing immediate productivity with long-term skill development
- Recognizing when shortcuts have been internalized by the Driver

## The Actions to Perform

### Level 1: Observation

- Observe Driver behavior (mouse usage, menu navigation, existing shortcuts)
- Track frequency and efficiency of common actions
- Identify which actions are frequent, slow, or both
- Report findings to the group after observation period
- Maintain tally marks for Navigator requests and Driver actions

### Level 2: Proactive Support

- When Driver uses mouse or menu, observe and suggest shortcut
- Format: "ACTION has shortcut SHORTCUT"
- Focus on the 5 key areas: File navigation, Code navigation, Refactoring, Testing, SCM

### Level 3: On-Demand Assistance

- Respond to Driver's "Shortcut Check" requests
- Support the Driver's responsibility to maintain team efficiency
- This includes following the Shortcut Check protocol below

#### Shortcut Check

Use Shortcut Check when the Driver needs immediate assistance with a shortcut or when the Shortcut Admiral observes an opportunity for efficiency improvement.

## Steps

1. Driver says "Shortcut Check" when they need shortcut assistance.
2. Shortcut Admiral immediately provides the correct shortcut information using this phrasing
   > "[ACTION] has shortcut [SHORTCUT]"
   Example: "Rename variable has shortcut F2".
  
   a. If the Shortcut Admiral does not immediately know the shortcut, they announce:
   > "I do not know shortcut. Does the mob know it?"
   b. If any Mobber knows the shortcut, they announce it using the standard phrasing.
   c. If nobody replies, any Mobber may announce
   > "I will look it up",
   then announce the shortcut when found.
   d. The Shortcut Admiral should add the shortcut to the tally sheet and cheat sheet once found.
3. If the Shortcut Admiral observes an efficiency opportunity, they may proactively offer a suggestion using the same phrasing.
4. Driver accepts the information without argument and attempts to (but is not required to) use the suggested shortcut.

## Commitments

- Say "Shortcut Check" as soon as you realize you need shortcut assistance, regardless of current activity.
- Follow the intent of the Perfection Game: focus on positive observations and specific improvements.
- Accept shortcut suggestions without argument or defensiveness.
- Be supportive of anyone using Shortcut Check.
- Do not shame or punish anyone for not knowing shortcuts.
- Do not shame or punish anyone for not using shortcuts.
- Withhold suggestions only if you cannot provide a specific improvement.

## Scoring

- Earn XP when Driver successfully uses a suggested shortcut
- Double-count XP with Driver when they use a new shortcut
- Consider awarding XP to the mob when shortcuts prevent "clickey-clickey" delays

## Example Keystroke Areas

### File Navigation

- Search for file, open file, close file

### Code Navigation  

- Go to definition, go back, display references

### Refactoring (The Big 6)

- Rename (variable, function, method, class)
- Extract Variable
- Extract Method/Function
- Inline Variable
- Inline Method/Function
- Move (code between methods, classes, or files)

#### MS Code Cheat Sheet

| MS Code Action   | Common phrase used in IDE documentation | MS Code Menu                                 | MS Code Keystroke                           |
|------------------|-----------------------------------------|----------------------------------------------|---------------------------------------------|
| Rename Symbol    | Rename symbol                           | Right-click → Rename Symbol                  | F2                                          |
| Extract Variable | Extract to variable                     | Right-click → Refactor → Extract to variable | Ctrl+Shift+R (select "Extract to variable") |
| Extract Method   | Extract method                          | Right-click → Refactor → Extract method      | Ctrl+Shift+R (select "Extract method")      |
| Inline Variable  | Inline variable                         | Right-click → Refactor → Inline variable     | Ctrl+Shift+R (select "Inline variable")     |
| Inline Method    | Inline method                           | Right-click → Refactor → Inline method       | Ctrl+Shift+R (select "Inline method")       |
| Move Line        | Move line up/down                       | Edit → Move Line Up/Down                     | Alt+↑/Alt+↓                                 |
| Move Method      | Move method to another class            | Right-click → Refactor → Move method         | Ctrl+. (select "Move method")               |
| Move Class       | Move class to another package/file      | Right-click → Refactor → Move class          | Ctrl+. (select "Move class")                |
| Rename/Move File | Rename or move file                     | Explorer → Right-click → Rename/Move         | F2 (in Explorer) or Right-click → Rename    |

#### JetBrains Cheat Sheet

| JetBrains Action | Common phrase used in IDE documentation | JetBrains Menu                | JetBrains Keystroke        |
|------------------|-----------------------------------------|-------------------------------|----------------------------|
| Rename           | Rename symbol                           | Refactor → Rename             | Shift+F6                   |
| Extract Variable | Extract variable                        | Refactor → Extract → Variable | Ctrl+Alt+V                 |
| Extract Method   | Extract method                          | Refactor → Extract → Method   | Ctrl+Alt+M                 |
| Inline Variable  | Inline variable                         | Refactor → Inline             | Ctrl+Alt+N                 |
| Inline Method    | Inline method                           | Refactor → Inline             | Ctrl+Alt+N                 |
| Move Line        | Move line up/down                       | Code → Move Line Up/Down      | Shift+Alt+↑/Shift+Alt+↓    |
| Move Method      | Move method to another class            | Refactor → Move               | F6                         |
| Move Class       | Move class to another package           | Refactor → Move               | F6                         |
| Rename/Move File | Rename or move file                     | Refactor → Rename/Move        | Shift+F6 (in Project view) |
|------------------|-----------------------------------------|-------------------------------|----------------------------|

#### Tally Sheet

| Action          | Navigator Request | Shortcut Admiral Suggestion | Driver Response (Mouse) | Driver Response (Menu) | Driver Response (Shortcut) | Driver Request (Shortcut Check) |
|-----------------|-------------------|-----------------------------|-------------------------|------------------------|----------------------------|---------------------------------|
| Rename Variable | xxxxx/xx          |                             |                         | xxxxx                  | xx                         |                                 |
|                 |                   |                             |                         |                        |                            |                                 |
| Rename Method   | xxx               | xx                          |                         |                        | xxx                        | x                               |

Eamples:
- Observation Phase -- The Navigator requested "Rename Variable" 7 times.  Because they were in observation mode, the Shortcut Admiral made 0 suggestions.  The Driver used the menu 5 times and keyboard shortut 2 times.
- Suggestion Phase -- The Navigator requested "Rename Method" 3 times.  The Shortcut Admiral made a suggestion 2 times.  The Driver did "Shortcut Request" 1 time, and used shortcut 3 times.

### Testing

- Run all tests, run one test

### SCM (Git)

- Commit, push, pull, add

## Related Roles

| Role             | Code Quality | Process Improvement | Team Dynamics | Information Gathering | High-Level Guidance | Individual Skill Development |
|------------------|--------------|---------------------|---------------|-----------------------|---------------------|------------------------------|
| Driver           |              |                     |               |                       |                     | ✓                            |
| Navigator        |              |                     |               |                       | ✓                   |                              |
| Mobber           |              |                     |               |                       |                     |                              |
|------------------|--------------|---------------------|---------------|-----------------------|---------------------|------------------------------|
| Researcher       |              |                     |               | ✓                     |                     |                              |
| Sponsor          |              |                     | ✓             |                       |                     |                              |
| Rear Admiral     |              |                     |               |                       | ✓                   |                              |
| Shortcut Admiral |              |                     |               |                       |                     | ✓                            |
|------------------|--------------|---------------------|---------------|-----------------------|---------------------|------------------------------|
| Automationist    |              | ✓                   |               |                       |                     |                              |
| Nose             | ✓            |                     |               |                       |                     |                              |
| Nostalgist       |              |                     | ✓             |                       |                     |                              |
| Archivist        |              |                     |               | ✓                     |                     |                              |
|------------------|--------------|---------------------|---------------|-----------------------|---------------------|------------------------------|
| Traffic Cop      |              | ✓                   |               |                       |                     |                              |
| Anthropologist   |              |                     |               | ✓                     |                     |                              |
| Disciplinarian   | ✓            |                     |               |                       |                     |                              |
| Conductor        |              |                     | ✓             |                       | ✓                   |                              |
| Major Pain       |              |                     | ✓             |                       |                     |                              |
| Dr. Feel Good    |              |                     | ✓             |                       |                     |                              |

## References

### [The Core Protocols](https://thecoreprotocols.org/)

A set of communication protocols designed to improve team collaboration and effectiveness. The Core Protocols provide structured approaches for common team interactions, including decision-making, conflict resolution, and personal alignment.

The Shortcut Admiral can leverage these protocols to enhance their ability to support the team through clear, respectful communication patterns. By understanding and applying Core Protocol principles, the Shortcut Admiral can create a more structured and effective learning environment for keyboard shortcut education.

### [Protocol Check](https://thecoreprotocols.org/protocols/protocolcheck)

A specific Core Protocol for addressing incorrect protocol usage or broken commitments. When a team member says "Protocol Check," it signals that a protocol is being used incorrectly or a Core Commitment is being broken. This protocol emphasizes immediate, supportive intervention without shame or punishment.

The Shortcut Admiral can use this concept to gently correct when shortcut suggestions are being ignored or when the role's guidelines aren't being followed properly. The Protocol Check approach ensures that corrections are made immediately and supportively, maintaining the educational focus of the role.

### [Perfection Game](https://thecoreprotocols.org/protocols/perfectiongame)

A structured feedback protocol designed to improve work through positive, constructive input. The Perfection Game focuses on what's valuable about the work and specific suggestions for making it better, using a 1-10 scale based on how much value the reviewer can add. This protocol emphasizes only positive comments and actionable improvements, avoiding negative criticism.

The Shortcut Admiral can apply this approach when providing constructive feedback on the Driver's shortcut usage, focusing on what's working well and specific ways to improve efficiency. By using the Perfection Game format, the Shortcut Admiral ensures that all feedback is constructive and actionable, creating a positive learning environment.
