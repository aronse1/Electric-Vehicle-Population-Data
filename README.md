## Explanation of One-Hot-Encoded Categories

| Category       | Feature                          | Value   | Description                                      |
|-----------------|----------------------------------|---------|---------------------------------------------------|
| **Sex**         | `Sex_female`                     | `false` | Not female                                       |
|                 | `Sex_male`                       | `false` | Not male                                         |
|                 | `Sex_unknown`                    | `true`  | Sex unknown                                      |
|                 | `Sex_nan`                        | `false` | No missing value                                |
| **Age**         | `Age_adult`                      | `true`  | Adult penguin                                    |
|                 | `Age_nan`                        | `false` | No missing value                                |
| **Breed Stage** | `Breed Stage_brood-guard`        | `false` | Not in brood-guard phase                         |
|                 | `Breed Stage_creche`             | `true`  | Active creche phase                              |
|                 | `Breed Stage_incubation`         | `false` | Not in incubation phase                          |
|                 | `Breed Stage_winter`             | `false` | Not in winter phase                             |
|                 | `Breed Stage_nan`                | `false` | No missing value                                |
| **Data Quality**| `ArgosQuality_3`                 | `true`  | Highest position accuracy (< 250m)              |
|                 | Other quality levels             | `false` | Not applicable                                  |

### 🔍 Key Explanations:
- **Creche Phase**: Chicks form groups, allowing parents to take turns foraging.
- **Argos Quality 3**: Most precise tracking data with less than 250m deviation.
