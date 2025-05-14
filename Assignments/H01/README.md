## AVL TREES

|                                  Set #1                                   |
| :------------------------------------------------------------------------: |
|          <img src="https://i.imgur.com/flgAeYt.png" width="400">          |
|Most insertions did not cause imbalance. |
|Inserting 30 created a right-heavy subtree under 10, triggering a Right-Right (RR) rotation at node 10.|
|After that, the tree remained balanced with no further rotations required.|

|                                  Set #2                                   |
| :------------------------------------------------------------------------: |
|          <img src="https://i.imgur.com/bC4SIKA.png" width="400">          |
|45 → Left-Right (LR) Rotation at 50 |
|55 → Right-Left (RL) Rotation at 50|
|70 → Right-Right (RR) Rotation at 45|
|30 → Left-Left (LL) Rotation at 40|
|65 → Right-Left (RL) Rotation at 60|
|43 → Left-Right (LR) Rotation at 45|

|                                  Set #3                                   |
| :------------------------------------------------------------------------: |
|          <img src="https://i.imgur.com/PO7J66K.png" width="400">          |
|85 → Right-Left (RL) Rotation at 90 |
|102 → Left-Right (LR) Rotation at 110|
|108 → Left-Right (LR) Rotation at 105|
