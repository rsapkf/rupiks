This repository contains SVG and PNG visualizations for all 57 OLL and 21 PLL cases (CFOP) for the Rubik's Cube that you may use for demonstration.

## Algorithms that I use:

- [OLL](#oll)
- [PLL](#pll)
- [Credits](#credits)

### OLL

| Name                               | OLL                    | Algorithms                                                                                                       |
| ---------------------------------- | ---------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **All Edges Oriented Correctly**   |                        |                                                                                                                  |
| OCLL6 - 26                         | ![26](/oll/svg/26.svg) | <ul><li>(R U2 R' U' R U' R')</li><li>y' R' U' R U' R' U2 R</li></ul>                                             |
| OCLL7 - 27                         | ![27](/oll/svg/27.svg) | <ul><li>(R U R' U R U2' R')</li><li>y' R' U2' R U R' U R</li></ul>                                               |
| OCLL1 - 21                         | ![21](/oll/svg/21.svg) | <ul><li>(R U2 R') (U' R U R') (U' R U' R')</li><li>y (R U R' U) (R U' R' U) (R U2' R')</li></ul>                 |
| OCLL2 - 22                         | ![22](/oll/svg/22.svg) | <ul><li>R U2' R2' U' R2U' R2' U2' R</li></ul>                                                                    |
| OCLL4 - 24                         | ![24](/oll/svg/24.svg) | <ul><li>(r U R' U') (r' F R F')</li></ul>                                                                        |
| OCLL5 - 25                         | ![25](/oll/svg/25.svg) | <ul><li>F' (r U R' U') r' F R</li></ul>                                                                          |
| OCLL3 - 23                         | ![23](/oll/svg/23.svg) | <ul><li>R2 D (R' U2 R) D' (R' U2 R')</li><li>y2 R2' D' (R U2 R') D (R U2 R)</li></ul>                            |
| **T-Shapes**                       |                        |                                                                                                                  |
| T1 - 33                            | ![33](/oll/svg/33.svg) | <ul><li>(R U R' U') (R' F R F')</li></ul>                                                                        |
| T2 - 45                            | ![45](/oll/svg/45.svg) | <ul><li>F (R U R' U') F'</li></ul>                                                                               |
| **Squares**                        |                        |                                                                                                                  |
| S1 - 5                             | ![5](/oll/svg/5.svg)   | <ul><li>(r' U2' R U R' U r)</li></ul>                                                                            |
| S2 - 6                             | ![6](/oll/svg/6.svg)   | <ul><li>(r U2 R' U' R U' r')</li></ul>                                                                           |
| **C-Shapes**                       |                        |                                                                                                                  |
| C1 - 34                            | ![34](/oll/svg/34.svg) | <ul><li>(R U R2' U') (R' F R U) R U' F'</li></ul>                                                                |
| C2 - 46                            | ![46](/oll/svg/46.svg) | <ul><li>R' U' (R' F R F') U R</li></ul>                                                                          |
| **W-Shapes**                       |                        |                                                                                                                  |
| W1 - 36                            | ![36](/oll/svg/36.svg) | <ul><li>(R' U' R U') (R' U R U) l U' R' U x</li><li>y2 (R U R' F') (R U R' U') (R' F R U') (R' F R F')</li></ul> |
| W2 - 38                            | ![38](/oll/svg/38.svg) | <ul><li>(R U R' U) (R U' R' U') (R' F R F')</li></ul>                                                            |
| **All Corners Oriented Correctly** |                        |                                                                                                                  |
| E1 - 28                            | ![28](/oll/svg/28.svg) | <ul><li>(r U R' U') M (U R U' R')</li></ul>                                                                      |
| E2 - 57                            | ![57](/oll/svg/57.svg) | <ul><li>(R U R' U') M' (U R U' r')</li></ul>                                                                     |
| **P-Shapes**                       |                        |                                                                                                                  |
| P1 - 31                            | ![31](/oll/svg/31.svg) | <ul><li>(R' U' F) (U R U' R') F' R</li></ul>                                                                     |
| P2 - 32                            | ![32](/oll/svg/32.svg) | <ul><li>R U B' (U' R' U) (R B R')</li><li>S (R U R' U') (R' F R f')</li></ul>                                    |
| P3 - 43                            | ![43](/oll/svg/43.svg) | <ul><li>y R' U' F' U F R</li><li>f' (L' U' L U) f</li></ul>                                                      |
| P4 - 44                            | ![44](/oll/svg/44.svg) | <ul><li>f (R U R' U') f'</li><li>y2 F (U R U' R') F'</li></ul>                                                   |
| **I-Shapes**                       |                        |                                                                                                                  |
| I1 - 51                            | ![51](/oll/svg/51.svg) | <ul><li>f (R U R' U') (R U R' U') f'</li><li>y2 F (U R U' R') (U R U' R') F'</li></ul>                           |
| I4 - 56                            | ![56](/oll/svg/56.svg) | <ul><li>r' U' r (U' R' U R) (U' R' U R) r' U r</li></ul>                                                         |
| I2 - 52                            | ![52](/oll/svg/52.svg) | <ul><li>(R' U' R U' R' U) y' (R' U R) B</li><li>(R U R' U R U') y (R U' R') F'</li></ul>                         |
| I3 - 55                            | ![55](/oll/svg/55.svg) | <ul><li>y (R' F R U) (R U' R2' F') R2 U' R' (U R U R')</li></ul>                                                 |
| **Fish Shapes**                    |                        |                                                                                                                  |
| F1 - 9                             | ![9](/oll/svg/9.svg)   | <ul><li>(R U R' U') R' F (R2U R' U') F'</li></ul>                                                                |
| F2 - 10                            | ![10](/oll/svg/10.svg) | <ul><li>(R U R' U) (R' F R F') (R U2' R')</li></ul>                                                              |
| F3 - 35                            | ![35](/oll/svg/35.svg) | <ul><li>(R U2') (R2' F R F') (R U2' R')</li></ul>                                                                |
| F4 - 37                            | ![37](/oll/svg/37.svg) | <ul><li>F (R U' R' U') (R UR' F')</li></ul>                                                                      |
| **Knight Move Shapes**             |                        |                                                                                                                  |
| K1 - 13                            | ![13](/oll/svg/13.svg) | <ul><li>(r U' r') (U' r U r') y'(R'U R)</li></ul>                                                                |
| K2 - 14                            | ![14](/oll/svg/14.svg) | <ul><li>(R' F R) (U R' F' R) (F U' F')</li></ul>                                                                 |
| K4 - 16                            | ![16](/oll/svg/16.svg) | <ul><li>(r U r') (R U R' U') (r U' r')</li></ul>                                                                 |
| K3 - 15                            | ![15](/oll/svg/15.svg) | <ul><li>(r' U' r) (R' U' R U) (r' U r)</li></ul>                                                                 |
| **Awkward Shapes**                 |                        |                                                                                                                  |
| A1 - 29                            | ![29](/oll/svg/29.svg) | <ul><li>y (R U R' U') (R U' R') (F' U' F) (R U R')</li><li>M U (R U R' U') (R' F R F') M'</li></ul>              |
| A2 - 30                            | ![30](/oll/svg/30.svg) | <ul><li>y' F U (R U2 R' U') (R U2 R' U') F'</li></ul>                                                            |
| A3 - 41                            | ![41](/oll/svg/41.svg) | <ul><li>(R U R' U R U2' R') F (R U R' U') F'</li></ul>                                                           |
| A4 - 42                            | ![42](/oll/svg/42.svg) | <ul><li>(R' U' R U' R' U2 R) F (R U R' U') F'</li><li>y (R' F R F') (R' F R F') (R U R' U') (R U R')</li></ul>   |
| **L-Shapes**                       |                        |                                                                                                                  |
| L2 - 48                            | ![48](/oll/svg/48.svg) | <ul><li>F (R U R' U') (R U R' U') F'</li></ul>                                                                   |
| L1 - 47                            | ![47](/oll/svg/47.svg) | <ul><li>F' (L' U' L U) (L' U' L U) F</li></ul>                                                                   |
| L3 - 49                            | ![49](/oll/svg/49.svg) | <ul><li>r U' r2' U r2 U r2' U' r</li></ul>                                                                       |
| L4 - 50                            | ![50](/oll/svg/50.svg) | <ul><li>r' U r2 U' r2' U' r2 U r'</li></ul>                                                                      |
| L5 - 53                            | ![53](/oll/svg/53.svg) | <ul><li>(r' U' R U') (R' U R U') R' U2 r</li><li>y r' U2' R (U R' U' R) (U R' U r)</li></ul>                     |
| L6 - 54                            | ![54](/oll/svg/54.svg) | <ul><li>(r U R' U) (R U' R' U) R U2' r'</li><li>y' (r U2 R' U') (R U R' U') R U' r'</li></ul>                    |
| **Lightening Bolts**               |                        |                                                                                                                  |
| B1 - 7                             | ![7](/oll/svg/7.svg)   | <ul><li>(r U R' U R U2' r')</li></ul>                                                                            |
| B2 - 8                             | ![8](/oll/svg/8.svg)   | <ul><li>(r' U' R U' R' U2 r)</li><li>y2 l' U' L U' L' U2 l</li></ul>                                             |
| B3 - 11                            | ![11](/oll/svg/11.svg) | <ul><li>r' (R2U R' U R U2 R') U M'</li></ul>                                                                     |
| B4 - 12                            | ![12](/oll/svg/12.svg) | <ul><li>M' (R' U' R U' R' U2 R)U' M</li><li>y F (R U R' U') F' U F (R U R' U') F'</li></ul>                      |
| B5 - 39                            | ![39](/oll/svg/39.svg) | <ul><li>(L F') (L' U' L U)F U' L'</li></ul>                                                                      |
| B6 - 40                            | ![40](/oll/svg/40.svg) | <ul><li>(R' F) (R U R' U') F' U R</li></ul>                                                                      |
| **No Edges Oriented Correctly**    |                        |                                                                                                                  |
| O1 - 1                             | ![1](/oll/svg/1.svg)   | <ul><li>(R U2') (R2' F R F') U2'(R' F R F')</li></ul>                                                            |
| O2 - 2                             | ![2](/oll/svg/2.svg)   | <ul><li>F (R U R' U') F' f (R U R' U') f'</li><li>y (r U r')U2 R U2' R' U2 (r U' r')</li></ul>                   |
| O3 - 3                             | ![3](/oll/svg/3.svg)   | <ul><li>f (R U R' U') f' U' F (R U R' U') F'</li></ul>                                                           |
| O4 - 4                             | ![4](/oll/svg/4.svg)   | <ul><li>f (R U R' U') f' U F (R U R' U') F'</li></ul>                                                            |
| O6 - 18                            | ![18](/oll/svg/18.svg) | <ul><li>y R U2' (R2' F R F') U2' M' (U R U' r')</li><li>(r U R' U R U2 r') (r' U' R U' R' U2 r)</li></ul>        |
| O7 - 19                            | ![19](/oll/svg/19.svg) | <ul><li>M U (R U R' U') M' (R' F R F')</li></ul>                                                                 |
| O5 - 17                            | ![17](/oll/svg/17.svg) | <ul><li>(R U R' U) (R' F R F') U2'(R' F R F')</li></ul>                                                          |
| O8 - 20                            | ![20](/oll/svg/20.svg) | <ul><li>M U (R U R' U') M2'(U R U' r')</li><li>(rUR' U') M2'(U R U'R') U'M'</li></ul>                            |

### PLL

| Name                             | PLL                    | Algorithms                                                                                                                                                             |
| -------------------------------- | ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Permutations of Edges Only**   |                        |                                                                                                                                                                        |
| Ua                               | ![Ua](/pll/svg/Ua.svg) | <ul><li>(R U' R U) R U (R U' R' U') R2</li><li>L2 U' (L' U' L U) L U (L U' L)</li><li>y2 (R2 U' R' U') R U R U (R U' R)</li></ul>                                      |
| Ub                               | ![Ub](/pll/svg/Ub.svg) | <ul><li>R2 U (R U R' U') R' U' (R' U R')</li><li>y2 (R' U R U') R' U' (R' U R U) R2</li></ul>                                                                          |
| H                                | ![H](/pll/svg/H.svg)   | <ul><li>(M2 U M2) U2 (M2 U M2)</li></ul>                                                                                                                               |
| Z                                | ![Z](/pll/svg/Z.svg)   | <ul><li>(M2 U M2 U) (M' U2) (M2 U2 M')</li></ul>                                                                                                                       |
| **Permutations of Corners Only** |                        |                                                                                                                                                                        |
| Aa                               | ![Aa](/pll/svg/Aa.svg) | <ul><li>x (R' U R') D2 (R U' R') D2 R2</li><li>y x' R2 D2 (R' U' R) D2 (R' U R') x</li><li>(R' F R' B2) (R F' R' B2) R2</li></ul>                                      |
| Ab                               | ![Ab](/pll/svg/Ab.svg) | <ul><li>x R2 D2 (R U R') D2 (R U' R)</li><li>y x' (R U' R) D2 (R' U R) D2 R2 x</li></ul>                                                                               |
| E                                | ![E](/pll/svg/E.svg)   | <ul><li>x' (R U' R' D) (R U R' D') (R U R' D) (R U' R' D') x</li></ul>                                                                                                 |
| **Adjacent Corners Swap**        |                        |                                                                                                                                                                        |
| T                                | ![T](/pll/svg/T.svg)   | <ul><li>(R U R' U') (R' F R2 U') R' U' (R U R' F')</li></ul>                                                                                                           |
| F                                | ![F](/pll/svg/F.svg)   | <ul><li>(R' U' F') (R U R' U') (R' F R2 U') (R' U' R U) (R' U R)</li></ul>                                                                                             |
| Ra                               | ![Ra](/pll/svg/Ra.svg) | <ul><li>(R U R' F') (R U2 R' U2) (R' F R U) (R U2 R')</li><li>(R U' R' U') (R U R D) (R' U' R D') (R' U2 R')</li><li>y' (L U2 L' U2) L F' (L' U' L U) L F L2</li></ul> |
| Rb                               | ![Rb](/pll/svg/Rb.svg) | <ul><li>(R' U2 R U2) R' F (R U R' U') R' F' R2</li><li>(R' U2 R' D') (R U' R' D) (R U R U') (R' U' R)</li></ul>                                                        |
| Ja                               | ![Ja](/pll/svg/Ja.svg) | <ul><li>(R' U L' U2) (R U' R' U2 R) L</li><li>y' (L' U' L F) (L' U' L U) L F' L2 U L</li></ul>                                                                         |
| Jb                               | ![Jb](/pll/svg/Jb.svg) | <ul><li>(R U R' F') (R U R' U') R' F R2 U' R'</li></ul>                                                                                                                |
| **Diagonal Corners Swap**        |                        |                                                                                                                                                                        |
| Y                                | ![Y](/pll/svg/Y.svg)   | <ul><li>F (R U' R' U') (R U R' F') (R U R' U') (R' F R F')</li></ul>                                                                                                   |
| V                                | ![V](/pll/svg/V.svg)   | <ul><li>(R' U R' U') y (R' F' R2 U') (R' U R' F) R F</li></ul>                                                                                                         |
| Na                               | ![Na](/pll/svg/Na.svg) | <ul><li>(R U R' U) (R U R' F') (R U R' U') (R' F R2 U') R' U2 (R U' R')</li><li>z U R' D R2 U' R D' U R' D R2 U' R D' z'</li></ul>                                     |
| Nb                               | ![Nb](/pll/svg/Nb.svg) | <ul><li>(R' U L' U2 R U' L) (R' U L' U2 R U' L)</li><li>R' U R U' R' F' U' F R U R' F R' F' R U' R</li></ul>                                                           |
| **G Permutations**               |                        |                                                                                                                                                                        |
| Ga                               | ![Ga](/pll/svg/Ga.svg) | <ul><li>R2 U (R' U R' U') (R U' R2) D U' (R' U R D')</li><li>R2 u (R' U R' U') R u' R2 y' (R' U R)</li></ul>                                                           |
| Gb                               | ![Gb](/pll/svg/Gb.svg) | <ul><li>y (F' U' F) (R2 u R' U) (R U' R u') R2</li><li>D (R' U' R U) D' (R2 U R' U) (R U' R U') R2</li></ul>                                                           |
| Gc                               | ![Gc](/pll/svg/Gc.svg) | <ul><li>y2 R2 F2 (R U2 R U2) R' F (R U R' U') R' F R2</li><li>R2 U' (R U' R U) (R' U R2 D') (U R U' R') D</li></ul>                                                    |
| Gd                               | ![Gd](/pll/svg/Gd.svg) | <ul><li>D' (R U R' U') D (R2 U' R U') (R' U R' U) R2</li><li>(R U R') y' (R2 u' R U') (R' U R' u) R2</li></ul>                                                         |

### Credits

- [VisualCube](https://github.com/Cride5/visualcube)
- Feliks Zemdegs | [CubeSkills](https://cubeskills.com)
