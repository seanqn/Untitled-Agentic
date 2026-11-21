# Agentic Capable Application Outline
This unnamed application outline serves as an approach to research, brainstorm, and plan out a potential MVP.

## What this app or tool intends to solve
- Remove repeated prompting/update and publishing into agentic workspaces
- Potentially removes the redundancy of manual prompting altogether depending on the goal of the client (productive user, developer, etc.)
- Resolves manual agentic API confirmation/updates by tracking and organizing environmental context using set triggers to notify model of environment changes

## Capabilities
The ultimate goal of the app or tool is to seamlessly build an agentic workflow and let it work without prompt requests. This could potentially serve two user flows: user-facing and developer.
1. User-facing:
   Consumer applications such as ChatGPT are targeted to this audience. App and web-app interaction supports ease of access with UI, provides notifications, and has segmented environments like Chat, Work, and Code.
   Targeting a wrapper to the same audience would imply that there is functionality that is not fully leveraged by the user-facing proprietary model application and instead only with their API. A user can use proprietary model applications to learn
   how to schedule reminders on their phone, have it write a script that executes this recurring reminder, or use a discrete feature to send a notification directly from the model application. There are varying degrees of familiarity between users with
   the extent of a model application's capabilities. They might not have seen or know exactly how to formulate a prompt in the exact way to get the desired output, and this is a pain point that will likely remain to exist. Since even the most advanced models rely
   on language processing to interpret user requests, there is little room to begin and or continue workflows without textual context. The resolution could involve several methods, but one directly replaces manual user prompting by structuring 'preset' prompts.
   Structured presets would initiate a number of common workflows and could organize them in a tree of desired outcomes. Another method that mixes with a developer-facing feature is purely promptless inference based on context. Many wrappers use model APIs
   in a similar manner, where app features (i.e. button click or approval) must gather context from previous input or states to initiate a process and build output. With this method, this application would require that existing context stored from previous workflows
   or user preferences.

2. Developer-facing:
   For developers integrating agentic workflow using proprietary models, a promptless method is even more desirable. The application could support monitoring capabilities and relay to the model API or simply support script generation from within the app itself, acting more like a composer.
   In an external environment, it works as a tool and tracks any changes, updating context of the environment until the workflow needs to be initiated or progressed, which would then start a process. For in-app script generations, initiation would follow from a 'preset' or allow for an initial text-based prompt
   so a custom script can be generated. There is no reason to necessarily remove textual context as a feature, rather leave it as fallback.

## Concepts
Outside of this general approach to agentic workflow, the question of what the environment is should be answered.

System-wide:
Slightly different but may conceptually integrate some of the features and capabilities listed. A system-wide agentic workflow orchestrator
would inherently be agnostic and allow custom usage of models, as well as local models. Several proprietary model applications do achieve this, but there are few agnostic applications.
Additionally, this may not initially be as broad as a complete orchestration app, instead focusing in on specific needs across the operating system. One such approach would interpret diagnostics (logs, resource usage, etc.) to determine specific user requests
or track and maintain overall health of the system. The latter would not require agentic capabilities, but the former could support agentic contextualization to provide technical support to the user, such as a step-by-step custom trouleshooting guide. This ties back into removing the need for remprompting, but
is resolved by eliminating the expected need for context (i.e. what version of the app are you running, which program is consuming significant resources, where are the files stored, etc.).
