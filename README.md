# Merkle Mountain Range

A type of merkle tree that could be described as many merkle trees which are then combined into 1, by making another merkle tree of their roots. The rules for making the tree(s) however are rigidly deterministic such that the entire structure depends only on the number of items put into it.

The MMR has many unique properties making it optimal for proving the ordering of a linked hashlist (as described in [FlyClient](https://www.youtube.com/watch?v=BPNs9EVxWrA))

## Resources 

[MMR data structure](https://github.com/juinc/tilap/issues/244) invented by Peter Todd

[Slice Sampling Markov Chain Monte Carlo algorithm](https://en.wikipedia.org/wiki/Slice_sampling) may be useful to efficiently calculate the exponentially distributed deterministic randomness needed to determine which blocks to sample (fly client doesn't seem to specify).




## Links


## Pristine Template Below

## Documentation Driven Development

There are many ways to drive open source development. Documenting the problem in the README gives a middle ground between technical and non-technical specifications. This allows organizing solutions to this challenge around community and documentation.

> [...] a beautifully crafted library with no documentation is also damn near worthless. If your software solves the wrong problem or nobody can figure out how to use it, there’s something very bad going on.

- [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) by Tom Preson-Werner

### Conventions and Specifications 

Using conventions, documentation and specifications make it easier to:
- communicate the problem you are solving
- ease onboarding
- build and use composable tools
- promote open source contribution and engagement
- promote issue and feature discussion on Github itself

#### Resources

- [opensource.guide](https://opensource.guide/)
- [Github community profiles for public repositories](https://help.github.com/articles/about-community-profiles-for-public-repositories/)
- [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
- [pengwynn/flint](https://github.com/pengwynn/flint)
- [Working Backwards](https://www.allthingsdistributed.com/2006/11/working_backwards.html)
- [Literate programming](https://en.wikipedia.org/wiki/Literate_programming)
- [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc)
- [Inversion and The Power of Avoiding Stupidity](https://fs.blog/2013/10/inversion/)

## Getting Started

To get started, [fork](https://help.github.com/articles/fork-a-repo/) or [duplicate](https://help.github.com/articles/duplicating-a-repository/) the repository. Then edit this file and delete everything above this line.

---

### Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.

