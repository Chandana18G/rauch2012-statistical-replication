# Smart Pill dataset

95 participants × 22 variables. One row per participant.

**Source:** Amy S. Nowacki, *Smart Pill Dataset*, TSHS Resources Portal (2017), https://www.causeweb.org/tshs/smart-pill/.
Obtained from the R package [`medicaldata`](https://github.com/higgi13425/medicaldata) (`smartpill`, MIT licence) and converted from `.rda` to CSV without modification.

**Study:** Rauch S. *et al.* (2012). *Use of wireless motility capsule to determine gastric emptying and small intestinal transit times in critically ill trauma patients.* J Crit Care 27(5):534.e7–e12.

| Variable | Description | Unit / coding |
|---|---|---|
| `Group` | Study group | 0 = critically ill trauma patient, 1 = healthy volunteer |
| `Gender` | Gender | 0 = female, 1 = male |
| `Race` | Race | 1 = White, 2 = Black, 3 = Asian/Pacific Islander, 4 = Hispanic, 5 = Other |
| `Height` | Height | cm |
| `Weight` | Weight | kg |
| `Age` | Age | years |
| `GE.Time` | Gastric emptying time: ingestion → gastric emptying | hours |
| `SB.Time` | Small-bowel transit time: gastric emptying → ileocaecal junction | hours |
| `C.Time` | Colonic transit time: ileocaecal junction → body exit | hours |
| `WG.Time` | Whole-gut transit time: ingestion → body exit | hours |
| `S.Contractions` | Stomach contractions (peak 10–300 mmHg) | count |
| `S.Sum.of.Amplitudes` | Stomach sum of amplitudes | mmHg |
| `S.Mean.Peak.Amplitude` | Stomach mean peak amplitude | mmHg |
| `S.Mean.pH` | Mean stomach pH (normal ≈ 1.5–3.5) | pH |
| `SB.Contractions` | Small-bowel contractions | count |
| `SB.Sum.of.Amplitudes` | Small-bowel sum of amplitudes | mmHg |
| `SB.Mean.Peak.Amplitude` | Small-bowel mean peak amplitude | mmHg |
| `SB.Mean.pH` | Mean small-bowel pH (normal ≈ 6–7.4) | pH |
| `Colon.Contractions` | Colon contractions | count |
| `Colon.Sum.of.Amplitudes` | Colon sum of amplitudes | mmHg |
| `C.Mean.Peak.Amplitude` | Colon mean peak amplitude | mmHg |
| `C.Mean.pH` | Mean colon pH | pH |

**Missing data:** for the 8 critically ill patients, race, colonic time and all pressure and pH variables are missing. One patient lacks `GE.Time` and `SB.Time`. Among the volunteers, missingness is sparse.
