---
type: checklist
subject: Chemistry
---
# Chemistry · quick checklist

> [!important] RATE → PRACTISE → MARK REVISED
> Pick a **strength** before studying. Tick **Revised?** only *after* practising and reviewing mistakes. A tick does **not** mean you are Strong.

[[Checklist Hub]] · [[Dashboard]] · [[21-Day Roadmap]]

## At a glance

```dataview
TABLE WITHOUT ID length(rows) AS "Topics", length(filter(rows, (r) => r.strength != "Unrated")) AS "Rated", length(filter(rows, (r) => r.strength = "Weak" OR r.strength = "Not studied")) AS "Need focus", length(filter(rows, (r) => r.reviewed)) AS "Revised"
FROM "03 Chapter Library/Chemistry"
WHERE type = "chapter"
GROUP BY subject
```

## Class 12 · boards + CAET overlap

**10 topics** · Scan left to right: chapter → strength → reviewed.

| Chapter | Strength · pick one | Revised? |
|:---|:---:|:---:|
| [[C12 - Alcohols Phenols and Ethers\|Alcohols Phenols and Ethers]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Alcohols Phenols and Ethers#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Alcohols Phenols and Ethers#reviewed]` |
| [[C12 - Aldehydes Ketones and Carboxylic Acids\|Aldehydes Ketones and Carboxylic Acids]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Aldehydes Ketones and Carboxylic Acids#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Aldehydes Ketones and Carboxylic Acids#reviewed]` |
| [[C12 - Amines\|Amines]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Amines#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Amines#reviewed]` |
| [[C12 - Biomolecules\|Biomolecules]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Biomolecules#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Biomolecules#reviewed]` |
| [[C12 - Chemical Kinetics\|Chemical Kinetics]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Chemical Kinetics#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Chemical Kinetics#reviewed]` |
| [[C12 - Coordination Compounds\|Coordination Compounds]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Coordination Compounds#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Coordination Compounds#reviewed]` |
| [[C12 - Electrochemistry\|Electrochemistry]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Electrochemistry#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Electrochemistry#reviewed]` |
| [[C12 - Haloalkanes and Haloarenes\|Haloalkanes and Haloarenes]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Haloalkanes and Haloarenes#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Haloalkanes and Haloarenes#reviewed]` |
| [[C12 - Solutions\|Solutions]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - Solutions#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - Solutions#reviewed]` |
| [[C12 - d- and f-Block Elements\|d- and f-Block Elements]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C12 - d- and f-Block Elements#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C12 - d- and f-Block Elements#reviewed]` |

## Class 11 · foundations

**9 topics** · Scan left to right: chapter → strength → reviewed.

| Chapter                                                                                                        |                                                                                          Strength · pick one                                                                                          |                                                   Revised?                                                    |
| :------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| [[C11 - Chemical Bonding and Molecular Structure\|Chemical Bonding and Molecular Structure]]                   |     `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Chemical Bonding and Molecular Structure#strength]`      |     `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Chemical Bonding and Molecular Structure#reviewed]`      |
| [[C11 - Classification of Elements and Periodicity\|Classification of Elements and Periodicity]]               |    `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Classification of Elements and Periodicity#strength]`     |    `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Classification of Elements and Periodicity#reviewed]`     |
| [[C11 - Equilibrium\|Equilibrium]]                                                                             |                    `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Equilibrium#strength]`                    |                    `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Equilibrium#reviewed]`                    |
| [[C11 - Hydrocarbons\|Hydrocarbons]]                                                                           |                   `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Hydrocarbons#strength]`                    |                   `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Hydrocarbons#reviewed]`                    |
| [[C11 - Organic Chemistry Basic Principles and Techniques\|Organic Chemistry Basic Principles and Techniques]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Organic Chemistry Basic Principles and Techniques#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Organic Chemistry Basic Principles and Techniques#reviewed]` |
| [[C11 - Redox Reactions\|Redox Reactions]]                                                                     |                  `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Redox Reactions#strength]`                  |                  `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Redox Reactions#reviewed]`                  |
| [[C11 - Some Basic Concepts of Chemistry\|Some Basic Concepts of Chemistry]]                                   |         `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Some Basic Concepts of Chemistry#strength]`          |         `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Some Basic Concepts of Chemistry#reviewed]`          |
| [[C11 - Structure of Atom\|Structure of Atom]]                                                                 |                 `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Structure of Atom#strength]`                 |                 `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Structure of Atom#reviewed]`                 |
| [[C11 - Thermodynamics\|Thermodynamics]]                                                                       |                  `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/C11 - Thermodynamics#strength]`                   |                  `INPUT[toggle:03 Chapter Library/Chemistry/C11 - Thermodynamics#reviewed]`                   |

## CAET additional topic clusters

**7 topics** · Scan left to right: chapter → strength → reviewed.

| Chapter | Strength · pick one | Revised? |
|:---|:---:|:---:|
| [[CX - Acid Base and Redox Titrations\|Acid Base and Redox Titrations]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/CX - Acid Base and Redox Titrations#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/CX - Acid Base and Redox Titrations#reviewed]` |
| [[CX - Addition and Condensation Polymers\|Addition and Condensation Polymers]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/CX - Addition and Condensation Polymers#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/CX - Addition and Condensation Polymers#reviewed]` |
| [[CX - Chemical Laboratory Safety and Measurements\|Chemical Laboratory Safety and Measurements]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/CX - Chemical Laboratory Safety and Measurements#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/CX - Chemical Laboratory Safety and Measurements#reviewed]` |
| [[CX - Gas Laws and Partial Pressures\|Gas Laws and Partial Pressures]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/CX - Gas Laws and Partial Pressures#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/CX - Gas Laws and Partial Pressures#reviewed]` |
| [[CX - Nuclear Chemistry and Radioactive Decay\|Nuclear Chemistry and Radioactive Decay]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/CX - Nuclear Chemistry and Radioactive Decay#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/CX - Nuclear Chemistry and Radioactive Decay#reviewed]` |
| [[CX - Qualitative and Instrumental Chemical Analysis\|Qualitative and Instrumental Chemical Analysis]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/CX - Qualitative and Instrumental Chemical Analysis#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/CX - Qualitative and Instrumental Chemical Analysis#reviewed]` |
| [[CX - Viscosity Surface Tension and Phase Curves\|Viscosity Surface Tension and Phase Curves]] | `INPUT[inlineSelect(option(Unrated), option(Not studied), option(Weak), option(Okay), option(Strong)):03 Chapter Library/Chemistry/CX - Viscosity Surface Tension and Phase Curves#strength]` | `INPUT[toggle:03 Chapter Library/Chemistry/CX - Viscosity Surface Tension and Phase Curves#reviewed]` |

> [!tip] If interactive controls appear as code
> Install and enable **Meta Bind**. These are live frontmatter controls, not ordinary Markdown checkboxes. Open a chapter link to see its complete 5-step practice checklist.

[[Checklist Hub]] · [[Dashboard]]
