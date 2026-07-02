# Supplement Price Tracker — Clean Label & Third-Party Tested

A data tracker for Amazon supplement prices, focused on clean label products, third-party certifications (NSF, USP, Informed Sport), and best value per serving.

## What This Tracks

- Price per serving across protein powders, vitamins, fish oil, probiotics, magnesium, and more
- Third-party certifications: NSF Certified for Sport, USP Verified, Informed Sport, IFOS
- Clean label flags: no sucralose, no artificial colors, no proprietary blends
- Trust Score based on certifications, label transparency, and customer reviews

## How to Read the Data

The tracker calculates **price per serving** — not just the sticker price. A $60 tub with 60 servings costs $1.00/serving. A $30 tub with 20 servings costs $1.50/serving. The cheaper product is actually more expensive per dose.

For fish oil, the key metric is **price per gram of EPA+DHA** — not price per capsule. Most "1000mg fish oil" capsules contain only 300mg of actual omega-3s. A $15 bottle with 300mg EPA+DHA per capsule costs more per gram of active ingredient than a $30 bottle with 720mg EPA+DHA.

## Clean Label Guide

Before buying any supplement, it helps to know which ingredients and certifications actually matter vs. which are just marketing. The **[Clean Label Supplement Guide](https://sadiyaqeen92639572-cloud.github.io/clean-label-guide/)** covers:

- How to spot proprietary blend red flags
- Which third-party certifications are meaningful (NSF vs. random "lab tested" claims)
- Ingredient scanner for common fillers and artificial additives
- Price per serving calculator for real comparison

The full live tracker with daily-updated prices is available at [cleanlabeltracker.com](https://cleanlabeltracker.com).

## Data Fields

| Field | Description |
|-------|-------------|
| `title` | Full product name |
| `priceListed` | Current price (USD) |
| `servingsDeclared` | Servings per container |
| `pricePerServing` | Price ÷ servings |
| `category` | Protein / Fish Oil / Probiotics / Vitamin D / etc. |
| `certTags` | NSF / USP / Informed Sport / IFOS |
| `freeTags` | Gluten-Free / Sugar-Free / No Sucralose / etc. |
| `trustScore` | 0–100 composite score |

## License

Data is collected for educational and price transparency purposes.
