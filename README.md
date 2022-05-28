# Between Denoising and Translation: Experiments in Text Detoxification
This is the repository for the DIALOGUE 2022 paper Between Denoising and Translation: Experiments in Text Detoxification

This approach is ranked in the 4st place in the official run (automatic) and 2nd in manual (human) evaluation

### Blind Test Result
#### Human Evaluation
| Team Name        | STA   | SIM   | FL    | J     |
|------------------|-------|-------|-------|-------|
| Human References | 0.888 | 0.824 | 0.894 | 0.653 |
| **Our model**   | 0.794 | 0.872 | 0.903 | 0.633 |
| T5 (baseline)    | 0.791 | 0.822 | 0.925 | 0.606 |

#### Automatic Evaluation
| Team Name            | STA   | SIM   | FL    | J     | ChrF  |
|----------------------|-------|-------|-------|-------|-------|
| gleb_shnshn          | 0.975 | 0.935 | 0.959 | 0.873 | 0.529 |
| orzhan               | 0.982 | 0.860 | 0.969 | 0.822 | 0.550 |
| FRC CSC RAS          | 0.945 | 0.855 | 0.967 | 0.784 | 0.571 |
| **Our model**       | 0.948 | 0.819 | 0.911 | 0.709 | 0.573 |
| Human References     | 0.846 | 0.716 | 0.783 | 0.494 | 0.773 |

### Sources
DisCO transformer https://github.com/jungokasai/deep-shallow
NAST transformer https://github.com/thu-coai/NAST
APE transformer https://github.com/zerocstaker/constrained_ape
