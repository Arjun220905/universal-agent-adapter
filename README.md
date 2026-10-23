# Universal Agent Adapter

A standard adapter for connecting an external agent runtime to MIA, so MeetStream does not need a separate bridge for every framework.

MIA is MeetStream's in-meeting agent. It joins Google Meet, Zoom, and Microsoft Teams, listens to the call, and can speak or take action in the meeting. If you already run an agent in your own runtime, this adapter is the shared contract for attaching that agent to a MeetStream meeting. You implement the contract once, instead of writing a new bridge for each framework.

## Status

This repository is being initialized. The adapter contract is not published yet. The interface, a reference runtime, and usage docs will be added as they are settled.

## Repository scope

- One adapter contract between an external agent runtime and MIA.
- What the runtime receives from the meeting, and what it can send back: speech, chat, and tool actions.
- A reference implementation of that contract.
- Docs for wiring a runtime you already run.

## About MeetStream

[MeetStream](https://meetstream.ai) is meeting bot infrastructure. A bot joins Google Meet, Zoom, or Microsoft Teams, records the call, and can run a [MIA](https://docs.meetstream.ai) voice agent inside the meeting.

## Links

- Website: https://meetstream.ai
- Docs: https://docs.meetstream.ai
- GitHub: https://github.com/meetstream-ai
