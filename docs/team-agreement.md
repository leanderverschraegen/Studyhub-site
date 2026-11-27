# Team agreement

How your team works together. Every member reads it at the start, and you read it again when something
goes wrong.

## Members, roles and pairs

| Role | Member | Works in a pair with |
| --- | --- | --- |
| Releases and repository | Leander | Niels |
| Content model and data | Niels | Leander |
| The informational task | Emile | Jules |
| The transactional task | Gijs | Jonas |
| Design and accessibility | Jonas | Gijs |
| Research and testing | Jules | Emile |

- **How we share the roles:** As the course's default for our team size. Leander and Niels form the technical and data pair (repository, releases, content model, and migrations). Gijs and Jonas form the booking and design pair (the study room reservation task and accessibility). Emile and Jules form the informational and testing pair (browsing/filtering study rooms and running user tests).

## How we communicate

- **Where we talk:** We use one group chat for everything about the project, and we meet on campus or via a quick call when needed.
- **How quickly we answer a teammate:** Within one working day.
- **When and how long we meet:** We meet once a week for 30 to 45 minutes to check progress and divide the next tasks.
- **Where we write down what we agreed:** In a short summary in our group chat and in the markdown files in `docs/`.

## How we decide

- **What a role holder decides alone:** Small implementation details, styling tweaks, and text edits inside their own task or document.
- **What needs the pair:** Changes to the content model and migrations (Leander & Niels), changes to the room booking form (Gijs & Jonas), or changes to the room search/filter logic and user test plan (Emile & Jules).
- **What needs the whole team:** Changes to the StudyHub project scope, navigation structure, user task steps, or role distribution.
- **How we settle a disagreement, and when we write a decision record:** We discuss it in our weekly meeting and vote if needed; if we remain tied, the role holder makes the final call and writes a short decision record in `docs/`.

## When a pull request is done

The author of a pull request merges it when all of this is true:

- The author tried the change on its preview, at a narrow width too when something visible changed.
- Its AI note is filled in.
- The starter's checks have finished. The author read what they say, and fixed what a red check found
  when that was possible.
- A change to the content model has its migration. Only the content-model pair creates migrations.
- A change to the study room reservation form is tried once with an already booked time slot on the preview before merging, so a full room never accepts a double booking.

We ask a teammate for a review when the author is not sure of a change.

## The AI note

Every pull request has the section *AI note: what I asked AI, and what I checked*, under that exact
heading. The note is one or two lines and has two parts: *What I asked AI* and *What I checked*. When
no AI tool was used, the note says "No AI used".

- **How we check what an AI tool wrote before we use it:** We read every line to verify it fits StudyHub without placeholder text, run the build and tests locally, and verify the behavior in the browser on the Vercel preview before merging.

## When someone stops contributing

- **What counts as stopping for us:** No answer in the group chat for three working days, or leaving an agreed task open more than three days past its date without letting the team know.
- **What the pair does first:** Their pair partner contacts them directly to ask what is blocking them and helps split up the task if needed.
- **What the whole team does next:** If there is still no progress by the weekly meeting, the whole team reassigns the work with a new task and a date.
- **How we record what happened:** We change this agreement when we share the roles or the work again.

## Agreed by

| Member | Date |
| --- | --- |
| Leander | 27 November 2026 |
| Niels | 27 November 2026 |
| Gijs | 27 November 2026 |
| Jonas | 27 November 2026 |
| Emile | 27 November 2026 |
| Jules | 27 November 2026 |
