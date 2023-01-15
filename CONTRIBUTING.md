# Contributing

To contribute to this project please either open an Issue with the details of the change you would like.
If you have already discussed this with the maintainers or have contributed in the past you can also open a Pull Request.

## Opening an Issue

You can open an Issue from the [GitHub Issue tracker page](https://github.com/QPPQLivingReview/review/issues).
Before you open an Issue please search through both the closed and open Issues to make sure that your Issue hasn't already been discussed or addressed in the past.

## Pull Request Process

1. Create a [fork of the project](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo).
2. Create your Pull Request (PR) from your fork (see the FAQ below).
3. Ensure that the tests in the CI are passing.
4. Request that a maintainer review your PR.
5. Your PR can be merged in once you have the sign-off of at least one maintainer. If you do not have permission to make the merge, request the approving maintainer to merge it for you.

## FAQ

### There is a subject not listed that I think should be. How do I get it added to the listing?

If there is content missing that you'd like added please create an issue with as much description as possible (and maybe some examples).
A maintainer will add the content once it has been approved.
Alternatively, feel free to fork the repository and add the content you want and then create a pull request.

### Should I add papers that are only about Quantum Computing?

Maybe. 
Trying to keep an updated list of all Quantum Computing papers would be both beyond the scope of the project and unmaintainable. However, some quantum algorithms may be particularly interesting for the area of Plasma Physics. 
We welcome and encourage contributions of papers that cover Quantum Computing applications to Plasma Physics!

### How do I add a paper?

All paper additions should be submitted as a single pull request on a source branch that isn't `master`.

1. Make a new branch on your fork for the pull request
2. Find the paper on [arXiv](https://arxiv.org/) or scientific journal 
3. Get the BibTeX for the paper citation
4. Add this BibTeX entry to [`QPPQ.bib`](https://github.com/QPPQLivingReview/review/blob/main/QPPQ.bib)
5. Add the citation to [`QPPQ.tex`](https://github.com/QPPQLivingReview/review/blob/main/QPPQ.tex) in the appropriate categories
8. Add and commit `QPPQ.bib` and `QPPQ.tex` to your pull request
9. If you haven't yet, push your branch to GitHub and open a pull request to the main project
