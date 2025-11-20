### Well hello there!

This repository is meant to provide an example for *forking* a repository on GitHub.

Creating a *fork* is producing a personal copy of someone else's project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit *Pull Requests* to help make other people's projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.

After forking this repository, you can make some changes to the project, and submit [a Pull Request](https://github.com/octocat/Spoon-Knife/pulls) as practice.

For some more information on how to fork a repository, [check out our guide, "Forking Projects""](http://guides.github.com/overviews/forking/). Thanks! :sparkling_heart:

![label: Content](https://img.shields.io/github/labels/github/docs/content)

```mermaid
graph TB;
  A1[<a href='https://disney.com'>Opening Event</a>]
  A2[<a href='https://disney.com'>link</a>];
  A1-->A2;
  B-->D;
  C-->D;
```
```mermaid
flowchart LR
subgraph Department A
A[Step 1]
end
subgraph Department B
B[Step 2]
end
subgraph Department C
subgraph Sub-Dept C1
C[Step 3]
end
subgraph Sub-Dept C2
D[Step 4]
end
end
A --> B --> C
D --> B
```
