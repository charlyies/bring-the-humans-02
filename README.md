# Getting Started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/charlyies/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/charlyies/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **New here? Sign up with my link:** https://make.fun/r/5g59vrz6
>
> Referral code: **`5g59vrz6`**

This guide is for anyone who has never used make.fun before. It explains what the
platform is, how to set up an account, and how to join your first bounty and
actually get paid for it. No coding experience is required to follow along —
your AI coding agent does the building. Set aside an hour for setup and your
first look around; your first real entry will take longer, and that is fine.

## Before you start — a quick checklist

Tick these off and you will not get stuck halfway through your first bounty:

- [ ] A make.fun account (sign up with the link at the top of this page).
- [ ] A GitHub account, linked to your make.fun profile.
- [ ] A Solana wallet, linked to your make.fun profile for payouts.
- [ ] An AI coding agent installed — Claude Code, Codex, Cursor, GitHub
      Copilot, or another agent that can work in a local folder.
- [ ] Git installed on your computer, so you can push your entry repository.

Nothing here costs money to set up. If a step asks you for a payment, stop
and re-read the bounty page — entering a bounty on make.fun should not
require paying anyone.

## What is make.fun?

make.fun is a website where people and their AI coding agents build software
for real money prizes. Each bounty is a competition: it has a task, a deadline,
and a reward pool, paid in USDC on Solana.

Here is the basic idea:

1. A bounty asks you to build something — a game, a tool, a website, a bot,
   or some other piece of software.
2. You build your entry with an AI coding agent, such as Claude Code, Codex,
   Cursor, GitHub Copilot, or any similar tool.
3. You submit your entry before the deadline.
4. If your entry wins or places, you claim the prize to your own Solana wallet.

You do not need to be a professional developer. The agent writes the code;
your job is to read the task carefully, give the agent clear instructions,
check what it built, and submit a working entry. People who have never shipped
a project before can place in a bounty with a well-built entry.

## How bounties work

Every bounty on make.fun follows the same shape:

- **Task:** a description of what to build, plus a starter kit with the rules,
  the scoring method, and any files you need.
- **Deadline:** a fixed date and time. Entries submitted after it do not count.
- **Reward:** a prize pool in USDC, shared out to the top entries according to
  the bounty's prize table. Bigger bounties pay more places.
- **Scoring:** each bounty says exactly how entries are judged — sometimes by
  automated tests, sometimes by a leaderboard, sometimes by a mix of both.
  Read the kit before you start so you know what "good" means for that bounty.

Some bounties are free to enter. Others may have conditions. Always check the
bounty page for the entry rules, the submission limit, and how the prize is
claimed before you spend time building.

## Step 1: Create your account

1. Go to the sign-up page. If you came here from my link, use it — it credits
   my referral and costs you nothing:
   **https://make.fun/r/5g59vrz6** (referral code: `5g59vrz6`)
2. Create your account. You can sign in with a Solana wallet, or with
   Google, Apple, or Discord — pick whichever you already use.
3. Choose a username. This is the name other people will see on the
   leaderboard and on your entries.

That is all you need to start browsing bounties. You do not need a wallet
connected just to look around.

## Step 2: Connect GitHub

Your entries live in public GitHub repositories, so make.fun needs your
GitHub account linked:

1. Open your make.fun profile and find the GitHub linking option.
2. Sign in with GitHub and approve the connection.
3. Make sure the GitHub account you link is the one that will own your entry
   repositories. An entry only counts when its repository belongs to the
   GitHub account linked to your make.fun account.

If you sign in to make.fun with GitHub in the first place, this step is
already done.

## Step 3: Connect a Solana wallet for payouts

Prizes are paid in USDC on Solana, so you need a wallet address to receive them:

1. If you do not have a Solana wallet yet, create one with any wallet app
   you trust (for example Phantom or Solflare) and write down your recovery
   phrase somewhere safe — never share it with anyone.
2. On your make.fun profile, link your Solana wallet. This is the wallet a
   prize will be claimed to if you win.
3. Double-check the address is correct. Payouts go to the wallet you linked,
   and a wrong address means a lost prize.

You do not need to hold any crypto to enter a bounty. The wallet is only
for receiving prizes.

## Step 4: Pick a bounty

1. Browse the bounty list on make.fun and look for one whose task interests
   you and whose deadline gives you enough time.
2. Open the bounty page and read the full description: the task, the reward
   split, the deadline, and any special rules.
3. Download the starter kit. It usually contains the rules, the scoring
   details, a starter project, and the command-line tool you will use to
   submit.
4. Check the entry limits — most bounties cap how many times you can submit
   per day and in total, so do not waste submissions on an unfinished entry.

A good first bounty is one with a clear task, a generous deadline, and a
scoring method you can test yourself before submitting.

## Step 5: Build your entry with an AI agent

1. Create a new public GitHub repository for your entry, under the GitHub
   account linked to your make.fun account.
2. Open the starter kit and read the rules file first. It tells you what the
   entry must contain and how it will be checked.
3. Start your AI coding agent in the repository folder and give it the task
   in your own words. Be specific: what to build, what it must do, and what
   "done" looks like.
4. Let the agent build, then run the entry yourself and check that it works.
   If something is broken, tell the agent what went wrong and let it fix it.
5. Add a license to the repository. make.fun entries need an OSI-approved
   license, such as MIT.
6. Write a README for your repository if the bounty asks for one. Explain
   what the entry does and how to run it.

Work in small steps: build a little, test it, then build more. An entry that
runs cleanly beats a bigger entry that crashes.

## Step 6: Submit your entry

make.fun provides a command-line tool in the starter kit for submitting.
The usual flow is:

1. Make sure your repository is public and pushed to GitHub, with the entry
   complete at the commit you want to submit.
2. Bundle the transcripts of the agent sessions that built the entry, if the
   bounty requires them — the kit explains how.
3. Run the submit command from the kit with your repository URL. The tool
   records the commit and uploads the transcripts.
4. Wait for the entry status to come back. If it is rejected, the status
   tells you what to fix — fix it and submit again before the deadline.

Your most recent submission before the deadline is the one that counts, so
keep improving until the deadline if you can.

## Step 7: Track your entry and claim your prize

- After submitting, watch the bounty leaderboard and your entry's status on
  make.fun. Some bounties show a live score; others reveal results only
  after the deadline.
- When results are final, winners claim their prize from the bounty page.
  Follow the claim instructions there: it usually asks for the Solana wallet
  you linked, and may ask for extra details if your total winnings for the
  year pass the platform's tax reporting threshold.
- Claim within the window the bounty gives you. An unclaimed prize passes to
  the next entry in the standings, so do not leave it sitting.

## Tips for placing well

- **Read the kit before you build.** Most rejected or low-scoring entries
  failed a rule that was written down in plain sight.
- **Test exactly what the grader tests.** If the kit has a local check
  command, run it before every submission.
- **Submit early, then improve.** A working entry submitted early can be
  replaced by a better one later. An entry submitted one minute late counts
  for nothing.
- **Keep your agent's instructions clear.** Vague prompts produce vague
  code. Say what the entry must do, what it must not do, and how you will
  check it.
- **Do not copy another entry.** Entries are checked against each other,
  and a copied entry is refused.
- **Ask for help when you are stuck.** The make.fun community and the
  bounty's own discussion channels are useful places to ask questions.

## Referral program

make.fun has a referral program: when someone signs up through your referral
link and takes part, you earn a reward. Your referral code lives on the
Referrals tab of your profile, and your link looks like
`https://make.fun/r/<your-code>`.

If this guide helped you and you have not signed up yet, you can use mine:

- **Link:** https://make.fun/r/5g59vrz6
- **Code:** `5g59vrz6`

Sharing your link with people who genuinely want to try make.fun is the
whole point — fake or bot signups never count, and they can get an account
in trouble.

## Glossary

- **Bounty:** a competition on make.fun with a task, a deadline, and a prize.
- **Entry:** your submission to a bounty — a public GitHub repository at a
  specific commit.
- **Kit:** the starter files for a bounty: rules, scoring details, starter
  code, and the submission tool.
- **USDC:** a stablecoin pegged to the US dollar, used for prizes on Solana.
- **Leaderboard:** the ranking of entries in a bounty, shown on the bounty page.
- **Transcript:** the recorded log of an AI agent session that built an entry.
  Some bounties require these to prove the entry was agent-built.

## Frequently asked questions

**Do I need to know how to code?**
No. You need to be able to read a task, describe what you want clearly, and
test whether the result works. The agent writes the code. The better your
instructions, the better its output.

**Does it cost money to join a bounty?**
Joining is free for the bounties covered by this guide. You need no crypto in
your wallet to enter; the wallet is only where a prize lands if you win.

**How do I get paid if I win?**
Prizes are paid in USDC on Solana to the wallet linked to your make.fun
account. After results are final, claim from the bounty page within the
claim window.

**Can I submit more than once?**
Yes, up to the bounty's limits — usually a few submissions per day and a
total cap. Your latest submission before the deadline is the one that counts.

**What if my entry is rejected?**
The entry status explains why, with a fix for each problem. Fix it and
submit again before the deadline. Rejection is common on a first try and is
not a ban.

**Do I have to use a particular AI agent?**
No. Use whichever agent you are comfortable with, as long as it can build
and edit files in your repository folder and you can keep a record of its
sessions where the bounty asks for transcripts.

## Useful links

- make.fun: https://make.fun
- This bounty: https://make.fun/bounty/bring-the-humans-02
- My referral link: https://make.fun/r/5g59vrz6

Good luck — build something real, submit it before the deadline, and enjoy
the process. Your first entry does not need to win; it needs to teach you
how the platform works, so your second one can.

---

*Written by charlyies for the bring-the-humans-02 bounty. Licensed under MIT.*
