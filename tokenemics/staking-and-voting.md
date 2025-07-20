---
description: >-
  Learn how staking FUM tokens powers report creation and community driven
  voting.
---

# Staking and Voting

Fradium uses a staking-based voting system to ensure that only users with meaningful contributions and skin in the game can influence decisions. Staking FUM tokens is required both to **create reports** and to **vote** on the legitimacy of those reports. This mechanism strengthens trust and reduces spam or malicious activity within the platform.

## **Why Require Staking?**

* Deters spam reports and careless voting
* Aligns incentives with ecosystem integrity
* Encourages only active and credible participants to influence decisions

## **Staking for Reporting**

To create a report about a suspicious blockchain address, users are required to stake a minimum of **5 FUM**. This stake serves as a signal of serious intent and helps reduce spam or low-effort submissions.

* **Minimum Stake**: 5 FUM
* **Optional**: Users can stake more than the minimum to increase potential rewards
* **Unstake**: users must return to the report page and manually unstake after the voting period ends (7 days)
* **Reward**: If the report is considered valid by community voting, the user receives 25% **FUM** as a reward in addition to their original stake
* **No Reward**: If the report is rejected by voters, the user can still manually unstake their tokens but will receive **no reward**

This staking system incentivizes users to submit credible reports while preserving their staked tokens, even in the case of rejection.

## **Staking for Voting**

Voting on reports also requires users to stake FUM. This requirement ensures that only genuinely active participants can influence the outcome, preventing spam votes or bot participation.

* **Minimum Stake**: 1 FUM
* **Stake per Vote**: Users can freely choose how many FUM tokens to stake for each vote
* **Vote Weight Formula**:\
  **Vote Weight = 1 × Activity Factor**
* **Activity Factor Calculation**:\
  Activity Factor = 100% + (Number of correct votes × 2%) + (Number of valid reports created × 5%)
* **Voting Options**: Safe / UnSafe
* **Vote Deadline**: 7 days after the report is created

Tokens staked for voting are **locked** until the report’s voting period ends. After the deadline, users must manually **unstake** and may receive a reward depending on the outcome:

* **If the user voted with the majority**:\
  Reward = **0.1%** of the staked amount
  * full return of the staked tokens
* **If the user voted with the minority**:\
  No reward is given, but the staked tokens are still fully returned

This system ensures fairness and encourages thoughtful, high quality participation in the governance process.

## **Vote Result Logic**

A report is accepted or rejected based on the **majority vote weight** and a minimum **quorum of voters**, not merely the number of “Yes” votes.

To be considered **valid (Unsafe)**, a report must meet the following conditions:

* **More than 50%** of total vote weight must vote **"Yes"**, **and**
* At least **3 unique voters** must have participated in the voting process

If these conditions are met, the report is marked as **valid (Unsafe)**, and rewards are distributed accordingly.

If **either** the majority vote weight condition **or** the minimum quorum is **not met**, the report is considered **not valid (Safe)**, and no rewards are distributed.

> This dual-condition approach helps maintain stricter validation, ensures that reports are not manipulated by a small group, and reduces the risk of false positives.

## **Unstaking Process**

* **For Report Creators**: If report is valid, stake is returned (plus reward)
* **For Voters**: After deadline, voter can unstake and claim reward (if on majority side)



