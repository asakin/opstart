# opstart

A company in a box, for companies where AI agents work alongside people.

**Status: early. Nothing runs yet.** This repository is public from the first commit so the work happens in the open. Until there is working code, this README is the whole project.

## The idea

You pick the tools your company needs (wiki, CRM, chat, identity, and so on) and say, for each one, whether you want it self-hosted or as SaaS. You get a single config file. You run one container on your own machine, sign in to your cloud and GitHub there, and it sets up the company on GCP or AWS. Then it hands everything to your own repository and CI and steps away. Your credentials never leave your machine.

Every tool has to be reachable by agents (for example over MCP) and has to sign people in through the company's identity provider. Agents maintain the catalog of tools, and a test harness decides what merges.

## License

[MIT](LICENSE) © 2026 Ariel Sakin
