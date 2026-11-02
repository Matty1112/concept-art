# Concept Art

A structured workflow that helps Claude think like a professional concept artist. Instead of jumping straight to a generic image prompt, it builds a design up in layers: a close reading of what you asked for first, then an interesting core concept, then the details that matter most, then each of those details designed on its own, and finally a detailed prompt you can take to an AI image generator.

## Skills

| Skill | What it does |
| --- | --- |
| **creo-artis** | Runs the whole pipeline end to end and finishes with a detailed AI art prompt. Start here. |
| **lege-voluntatem** | Analyzes your request: breaks it into its components, works out what they mean together, sets a unique direction for the design, and defines a non-generic criterion for what "best" means (darkest, moodiest, most eccentric, and so on). |
| **conceptio-artis-maior** | Full concept brainstorm: 20 adjective + noun base concepts, narrowed to a top 5 for you to choose from, then developed toward the mood you asked for. |
| **elige-et-illumina** | Picks the key details: brainstorms 10 candidate details for the concept and keeps the 5 that will make it stand out most visually. |
| **sculpe-singula** | Designs each chosen detail, from its most fundamental parts down to the smaller supporting components. |
| **conceptio-artis-minor** | Quick concept brainstorm (3 ideas), used by sculpe-singula to come up with a concept for each individual detail. |

## Usage

Ask Claude for a piece of concept art, for example: "Design a character for a melancholic storm-themed fantasy world." Claude will propose base concepts and ask you to pick one, then carry the design through to a final prompt. You can also call any skill on its own, for instance to brainstorm concepts or to flesh out the details of a design you already have.

No setup, connectors, or API keys are required.

## License

MIT
