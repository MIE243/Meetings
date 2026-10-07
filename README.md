# MIE243 Meeting Records

## September 14, 2026 — 8:00 p.m.

### Discussion

1. Study the contents of the Design Project document.
2. Discuss and clarify the exact project task.
3. Conduct an initial investigation of each component to help determine the final production target.

### Research Assignments

| Team Member | Assigned Topics |
| --- | --- |
| Mo Zhou | Couplings, drive shafts and CV shafts; differentials, transfer cases and CVTs; dual-motor, dual-axle configuration; torque vectoring |
| Shangkai Ji | Gearboxes, transmissions and torque converters; brakes and clutches; front-wheel drive; dual-motor, single-axle configuration; dynamic suspensions |
| Hongru Liu | Steering and suspension; rear-wheel drive; all-wheel drive; single-motor, single-axle configuration (FWD — SM1ST, SM2ST, etc.); ABS and traction control |

### Action Items

- Upload all research to GitHub.
- Complete all assigned research by September 18.

## September 18, 2026 — 8:00 p.m.

### Discussion and Decisions

1. Summarize the research findings and analyze the feasibility of producing each component.
2. Use an all-wheel-drive model as the basis for the final production target.

### Action Item

- Shangkai will email the TA to ask for clarification about unresolved project questions.

## September 21, 2026 — Tutorial Section

### Discussion

- The main topic was the team size. The issue remained unresolved at the end of the discussion.

## September 24, 2026 — 7:00 p.m.

### Discussion and Action Items

1. Send an email to confirm the number of group members and the check-in date.
2. Discuss the engineering specifications, including detailed requirements such as dimensions. Initial specifications can be recorded now and revised later.
3. Hongru Liu will establish an initial engineering-specification framework containing the main task points and required work. The framework will be used to assign tasks at the next meeting as the team prepares for the first check-in.
4. Document the relationship between 4×4 and AWD. The initial plan is to modify the AWD concept based on the 4×4 design. The meaning of “different conceptual designs” still requires clarification, and Mo has sent an email asking about it.
5. Explore GitHub Projects and improve the current project board.
6. Hold the next meeting at 9:00 p.m. on September 25.

## September 25, 2026 — 7:00 p.m.

### Discussion

1. Read the project document and discuss the engineering specifications.
2. Give a simple explanation of each section of the engineering specifications.
3. Discuss the first check-in, scheduled for October 7.
4. Discuss project-management roles.

### Engineering Specification Assignments

| Team Member | Assigned Sections |
| --- | --- |
| Mo Zhou | Scope; Existing Designs |
| Hongru Liu | Project Overview and Design Goals; Service Environment; Interest Holders; Production |
| Shangkai Ji | Context; Design Goals |

### Project Management Roles

| Team Member | Roles |
| --- | --- |
| Mo Zhou | CAD Design Owner; Developer |
| Hongru Liu | Scrum Master; Developer |
| Shangkai Ji | Design Owner; Meeting Recorder |

## September 26, 2026 — 4:40 p.m.

### Action Items

1. Contact the new teammate.
2. Introduce the team and project to the new teammate.

## September 28, 2026 — Tutorial Section

### GitHub Workflow

- Mo provided guidance for transferring and updating work on GitHub. Each personal task should be completed on a personal branch so the team can review and modify it later.

### Questions for the TA

1. **Engineering specification:** The TA said that the specification was carefully prepared but unnecessarily complicated. Following the format and level of detail in Tutorial 2 is sufficient, so the document should be simplified.
2. **Project board:** After reviewing the board, the TA confirmed that the team's approach and method were feasible.
3. **Vehicle options:** For categories containing several alternatives, such as differentials, transfer cases and CVTs, the team does not need to include every option but should document at least two.

## September 28, 2026 — 7:00 p.m.

### Discussion and Decisions

1. Review the previous tutorial notes and improve the engineering specification.
2. Structure Engineering Specification v0 similarly to the APS112 ESP example.
3. In Engineering Specification v1, remove or simplify material with limited relevance to the engineering specification, including the problem statement and scope.
4. Focus the revised specification on four sections: Demonstration; Operation and Modularity; Input, Size and Steering; and Safety, Cost and Lifecycle.
5. Complete these four sections by September 30, then hold a meeting to discuss and review them before the first check-in on October 7.

### Engineering Specification Assignments

| Team Member | Assigned Sections |
| --- | --- |
| Mo Zhou | Transfer Case |
| Hongru Liu | Input, Size and Steering; Operation and Modularity |
| Shangkai Ji | Safety, Cost and Lifecycle |
| Peiwen Sun | Demonstration |

## September 30, 2026 — 8:00 p.m.

### Scheduling Decision

- Peiwen Sun would not be available until 9:00 p.m. Shangkai Ji considered that too late and proposed moving the meeting to Thursday evening. All group members agreed.

## October 1, 2026 — 8:00 p.m.

### Engineering Specification

- The team discussed the engineering specification and the first check-in requirements. It was unclear whether “core design problems” needed to be included. The team decided that this material could be added after the first check-in and would not be a current priority.

### Demonstration Concepts

- **Transfer case**
  - Demonstrate the torque and speed differences between high and low ranges using elevation, slopes or different carried weights.
  - Compare 2WD and 4WD by lifting two wheels off the ground or driving over obstacles.
  - An electric motor or similar automatic input could power obstacle-crossing demonstrations.
  - Compare an open and locked centre differential:
    - During a tight turn with the differential locked, the front and rear axles slip relative to each other because they travel different distances.
    - When one axle is on a very low-grip surface, an open differential provides little usable torque, while a locked differential allows the vehicle to move.
  - Demonstrate neutral by turning the axles or wheels by hand to show that they spin freely.
- **Differential**
  - Show the left- and right-wheel speed difference during a turn.
- **Drivetrain**
  - Compare rear-wheel-drive 2WD with 4WD.

### Demonstration Methods

Each major component, including the centre transfer case and the front and rear differentials, should be individually removable for demonstration.

1. **Obstacle course:** Use connectable road sections to create curves, rough terrain and ramps.
   - Best represents real-world conditions.
   - An electrical input powers the transfer case while students interact with the vehicle and terrain.
   - Include simple steering.
2. **Electrical belt or roller bench:** Simulate the ground beneath each wheel while the vehicle remains stationary.
   - Use a stopper, force gauge or another restraint to prevent movement and possibly display torque differences.
3. **Stationary hand-cranked model:** Use no steering or vehicle movement; students observe differences in wheel speed while turning the input by hand.
4. **Pivot-arm test:** Tether the motor-powered vehicle to a pivot arm so it drives in a circle with an adjustable radius.
   - Differential locking can be demonstrated by observing wheel slip.
5. **Rotating ground disc:** Fix the vehicle in place above a rotating disc that represents turning ground, allowing students to observe the differentials working.

### Assignment Distribution

| Team Member | Assignment |
| --- | --- |
| Hongru Liu and Peiwen Sun | Produce hand-drawn illustrations for Demonstration Method 1. |
| Mo Zhou | Create CAD concepts for all demonstration methods except Method 1. |
| Shangkai Ji | Assist Mo with the CAD design and develop further CAD knowledge. |

## October 5, 2026 — Tutorial Section

### First Check-In Preparation

The team reviewed what was still missing for the first check-in:

1. Add labels to each task on the GitHub project board.
2. Add priorities to each task on the GitHub project board.
3. Update the meeting record.
4. Add Mo's remaining CAD images.
5. Copy the scope and problem statement from Engineering Specification v0.
6. Add references for relevant numerical values in the engineering specification where possible.

### Information Gathering and Review

- In the afternoon, ask the group that completed its check-in on Monday what questions were asked. Use this information during an evening meeting to review and improve the team's first check-in preparation.

### Check-In Rehearsal

- On Wednesday, all four team members will meet one hour early to work together and become familiar with the check-in process.

## October 6, 2026 — 8:30 p.m.

### First Check-In Presentation Plan

The team discussed the content, speaking assignments and presentation order for the first check-in.

1. **Introduction — Shangkai Ji**
   - Introduce Group 19 and its members.
   - Give a brief outline of the presentation:
     - Engineering specification.
     - Three candidate designs that use different methods to demonstrate the requirements in the engineering specification.
     - A conceptual CAD model of the proposed teaching vehicle.
2. **Engineering Specification — Shangkai Ji**
   - Explain the project scope, including the goal of using 3D-printed and relatively accessible components.
   - Give a brief overview of the detailed requirements.
3. **Conceptual CAD — Mo Zhou**
   - Explain that all candidate designs share a common vehicle model with minor differences in how each mechanism is demonstrated in different environments.
   - Explain the purposes of the v0 CAD:
     - Determine how the components fit together beyond the initial research.
     - Better understand how the mechanisms move.
     - Identify potential issues that may not be apparent from research alone.
   - Demonstrate what the current CAD can already show:
     - Steering motion using joints.
     - The different transfer-case modes, with further details available on GitHub.
     - The mode sleeve, range sleeve and centre-differential lock.
   - Note that some candidate designs may use a simpler vehicle, such as one without steering.
4. **Candidate Design 1 — Hongru Liu**
   - Present an obstacle course with curved, rough and ramped terrain that uses the surroundings to demonstrate vehicle operation.
   - Explain that this design most closely represents real-world conditions.
   - Use electrical power as the transfer-case input while students interact with the vehicle and terrain.
   - Use connectable road sections:
     - Ramp section for demonstrating high and low range.
     - Smooth-road section.
     - Rough-road section.
     - Curved-road section.
   - Include simple steering.
5. **Candidate Design 2 — Peiwen Sun**
6. **Candidate Design 3 — Peiwen Sun**
7. **GitHub Board and Project Management — Mo Zhou**
   - Show the GitHub project board, including its sections, sprint tags and Agile tags.
   - Explain why the team uses GitHub:
     - The team is comfortable using it.
     - It clearly organizes the project's different repositories.
     - Its version-control tools provide a visible commit history.
     - The project structure uses repositories, branches, pull requests, Markdown and Obsidian.
     - Pull requests and GitHub issues support review and version control.
8. **Plans for the Next Iteration**
   - Improve modularity.
   - Develop the v1 CAD with proper sizing and calculations while retaining simplified gear models for now.
   - Continue work on safety, lifecycle and cost.
   - Consider locking front and rear differentials.
