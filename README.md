# Hendrik: an embodied conversational agent for course evaluations


A team project from the *Advanced Conversational Agents* course at University of Twente (2022). We built a Furhat-based embodied conversational agent (ECA) named Hendrik to test whether conversational agents could be a viable alternative to traditional online questionnaires for course evaluations — which typically suffer from low response rates and shallow qualitative feedback.

## What we tested

We compared two conversational styles for Hendrik — **formal** and **casual** — against a control (the existing online questionnaire) along two dimensions:

- **Student experience** — measured via the SASSI questionnaire
- **Response quality** — assessed by course teachers using the SSA method

## What we found

- Students preferred the **formal** ECA: rated as more appropriate and easier to use
- Teachers found responses from the **casual** ECA most useful and qualitatively richer
- Suggests a real tension: the agent students find most appropriate isn't the one that elicits the most useful answers

## What's in this repo

| File / folder | What it is |
|---|---|
| `src/main/kotlin/furhatos/app/Hendrik/` | Furhat skill source code (Kotlin) |
| `assets/webTemplates/BASIC/` | Web UI templates |
| `Hendrik__the_conversational_questionnaire.pdf` | Full research paper |
| `build.gradle`, `gradlew`, `skill.properties` | Furhat build configuration |

## Built with

- [Furhat SDK](https://furhat.io/) — ECA platform
- Kotlin
- Gradle

## Status

Course project, completed 2022. Not actively maintained.

Thanks to Pietro Camin and 
