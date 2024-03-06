Specifications
--------------
| | |
------------|------------
Block time: | `5` Seconds
Block reward: | `42.94967296` SHUGA
Halving interval: | `12,500,000` Blocks (approx. 2 years)
Total supply: | `1,073,741,824` SHUGA
PoW algorithm: | YespowerShuga (based on Yespower 1.0.1)
Difficulty: | ShugaShield-N510 (based on Zcash's modification of Digishield)
Port: | 40001 / RPC 40002
Premine: | None: NO ICO, NO Presale, NO Founder's rewards

FAQ
---
- Disk space requirements:
  * Blockchain size growth is around `10 MB per day` and around 3.65 GB per year.
- Network rules:
  * To prevent fraud and timestamp attacks, nodes should be within `70 seconds` of accurate internet time, or they will be banned.
- Selfish mining & time warp attack:
  * Fraud techniques for manipulating timestamps are already known. We use a future time limit (FTL) to prevent this. Blocks that differ `60 seconds` or more from the current head will be banned. (credit: zawy12)
- Header indexing:
  * Using sha256d in header indexing, the initial synchronization speed is as fast as Litecoin.