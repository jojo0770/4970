# Contributing

Thank you for your interest in contributing to this documentation!

## Before You Start

- Please [create an issue](../../issues/new) before opening a Pull Request
- Make sure your changes are consistent with the existing documentation style

## Commit Message Style

- Use future tense ("Adds feature" not "Added feature")
- Use a `Fixes #xxx -` or `Closes #xxx -` prefix to auto-close the related issue
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

## Pull Request Checklist

- [ ] My changes follow the coding and writing style of this project
- [ ] My changes build without any errors or warnings
- [ ] My changes have been formatted and linted
- [ ] My changes include any required updates to documentation
- [ ] My changes have been rebased and squashed to the minimal number of relevant commits
- [ ] My PR has a descriptive title with a `Fixes #xxx -` or `Closes #xxx -` prefix

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the following command at the root of the repository (where `docs.json` is located):

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
