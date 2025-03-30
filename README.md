## Casual analysis on Mistral-7B
| Metric/Task                                | OC1 and CC1 | With 2-digit Prefix | With 2-digit Suffix | With Both 2-digit Prefix and Suffix |
|--------------------------------------|------------|---------------------|---------------------|------------------------------------|
| Maximum TE                           | 0.621       | 0.606                | 0.642                | 0.636                               |
| Top-2 Attention Heads Index (Layer, Head) |(20, 30), (17, 25) | (20, 30), (17, 25) | (20, 30), (17, 25) | (20, 30), (17, 25)               |


| Metric/Task                                | OC2 and CC2 | With 4-digit Prefix | With 4-digit Suffix | With Both 4-digit Prefix and Suffix |
|--------------------------------------|------------|---------------------|---------------------|------------------------------------|
| Maximum TE                           | 0.023       | 0.021               | 0.023                | 0.023                               |
| Top-2 Attention Heads Index (Layer, Head) | (15, 20), (3, 17) |  (15, 20), (3, 17) |  (15, 20), (3, 17) |  (15, 20), (3, 17)               |


## Casual analysis on LLaMA2-7B
| Metric/Task                                | OC1 and CC1 | With 2-digit Prefix | With 2-digit Suffix | With Both 2-digit Prefix and Suffix |
|--------------------------------------|------------|---------------------|---------------------|------------------------------------|
| Maximum TE                           | 0.315       | 0.313                | 0.309                | 0.321                               |
| Top-2 Attention Heads Index (Layer, Head) |(15, 15), (13, 23) | (15, 15), (13, 23) | (15, 15), (13, 23) | (15, 15), (13, 23)               |


| Metric/Task                                | OC2 and CC2 | With 4-digit Prefix | With 4-digit Suffix | With Both 4-digit Prefix and Suffix |
|--------------------------------------|------------|---------------------|---------------------|------------------------------------|
| Maximum TE                           | 0.036       | 0.032               | 0.036                | 0.034                               |
| Top-2 Attention Heads Index (Layer, Head) | (14, 4), (14, 7) |  (14, 4), (14, 7) |  (14, 4), (14, 7) |  (14, 4), (14, 7)               |
