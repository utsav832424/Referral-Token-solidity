# Referral Token Smart Contract

## Overview

This smart contract implements a referral token system on the Ethereum blockchain using Solidity. The contract rewards users with tokens when they register using a referral code and supports multiple levels of bonuses.

### Key Features

- **Referral Bonuses**: When a user registers using a referral code, both the referrer and the new user receive bonus tokens.
- **Multi-Level Rewards**: The system supports multiple levels of bonuses, rewarding referrers up to several levels deep.

## Token Distribution

- When user B registers using the referral code of user A:
  - A and B each receive 20 tokens.
- When user C registers using the referral code of user B:
  - B and C each receive 20 tokens.
  - A receives 10 tokens.
- When user D registers using the referral code of user C:
  - C and D each receive 20 tokens.
  - B receives 10 tokens.
  - A receives 5 tokens.
