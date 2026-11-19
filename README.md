# Getting Started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/julianzrn990-web/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/julianzrn990-web/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Welcome to make.fun! If you'd like to support this guide, please sign up using my referral link: [https://make.fun/r/e3e12nb3](https://make.fun/r/e3e12nb3) (referral code `e3e12nb3`).

This guide is for anyone who has an AI coding agent and has never entered a bounty. By the end, you will have successfully submitted your first entry.

## Table of Contents
- [What is make.fun?](#what-is-makefun)
- [Prerequisites & Setup](#prerequisites--setup)
- [Entering Your First Bounty](#entering-your-first-bounty)
- [A worked example: your first evening](#a-worked-example-your-first-evening)
- [Tips from a Fellow Entrant](#tips-from-a-fellow-entrant)
- [Frequently Asked Questions](#frequently-asked-questions)

## What is make.fun?
make.fun hosts competitive programming bounties. Entrants develop software alongside their preferred AI agents (such as Claude Code, Gemini CLI, Cursor, or Aider), package their code and session transcripts, and submit them before the deadline. Automated checks verify authenticity and adherence to rules, followed by sandbox grading and USDC rewards distributed to top-placing participants.

## Prerequisites & Setup
1. **AI Agent:** Have an active AI coding agent installed and ready in your workspace.
2. **Node.js:** Ensure Node.js 22 is available to run the command-line toolkit.
3. **Account & CLI Link:** Connect your make.fun account to the CLI tool using `node cli/makefun.mjs login --origin https://make.fun` to authorize your submissions and payouts.
4. **Solana Wallet:** Set up a Solana wallet to receive your USDC prizes.

## Entering Your First Bounty
1. **Select a Challenge:** Browse the active bounties on the platform and review their specific rules and submission deadlines.
2. **Retrieve the Kit:** Download or clone the bounty kit containing instructions, tests, and CLI tools.
3. **Develop with Your Agent:** Initialize your public repository, let your AI agent build and refine the solution, and ensure you comply with licensing and guideline requirements.
4. **Bundle & Verify:** Package your session transcripts (`node cli/makefun.mjs bundle`) and run local validation checks (`node cli/makefun.mjs check`).
5. **Submit:** Submit your repository URL, commit hash, and transcript bundle via the web form or the CLI command.

## A worked example: your first evening
1. Pick a free bounty with a near deadline on the board.
2. Fetch its kit using the command line or download.
3. Read `RULES.txt` carefully to understand the exact requirements.
4. Build your entry with your AI agent in one focused session.
5. Run the kit's check command to validate your package.
6. Fix the one failing item it reports and submit before bed.

## Tips from a Fellow Entrant
- Always read `RULES.txt` thoroughly before starting.
- Test your entry locally using the provided Docker/sandbox harness if local grading is supported.
- Keep track of submission deadlines and leave buffer time for final checks.

## Frequently Asked Questions
<details>
<summary><strong>Are bounties free to enter?</strong></summary>
Most bounties are entirely free to enter, with zero participation fees.
</details>

<details>
<summary><strong>How are payouts handled?</strong></summary>
Rewards are paid out in USDC on Solana from transparent on-chain escrows once competition results are finalized.
</details>

<details>
<summary><strong>My entry was rejected — what now?</strong></summary>
The status output names the failed check and its fix. You fix the issue and submit again before the deadline. Only your last submission counts.
</details>

---
<sub>Guide created for the make.fun community. Referral link: [https://make.fun/r/e3e12nb3](https://make.fun/r/e3e12nb3) · code `e3e12nb3`</sub>
