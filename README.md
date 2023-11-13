# How to build a Semantic Search Engine in Rust

Accompanying source code for the article https://sachaarbonel.medium.com/how-to-build-a-semantic-search-engine-in-rust-e96e6378cfd9

## Getting Started

### M1
`cargo run --target x86_64-apple-darwin`

### Intel
`cargo run`


## Next step
I wonder if such semantic search could be used to reduce errors caused by misleading names.
For example: naming a class product and another one article.
Basically if two classes are synonymous, i.e. semantically very close, they are potentially creating confusion within the source code.
Today such semantic issues are often detected after the PR, at best, or after the incident in prod, at worst.

A first step to check for source code semantic coherence would be to extract a list of all the classes.
Then scan these classes with your semantic tool and regroup classes with similar semantic scoring.
Such result could be 
Would you be interested in exploring 
