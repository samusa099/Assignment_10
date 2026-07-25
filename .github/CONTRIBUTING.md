# Contributing

Thank you for considering an improvement to this project. Contributions should be focused, easy to review, and consistent with the existing project structure.

## Before You Start

1. Read `README.md` for the project overview.
2. Read `HOW_TO_USE.md` for project-specific usage and limitations.
3. Check existing issues and pull requests to avoid duplicate work.

## Recommended Workflow

1. Fork the repository.
2. Clone your fork locally.
3. Create a focused branch, such as `fix/mobile-navigation` or `docs/improve-guide`.
4. Make and test the smallest practical change.
5. Commit with a clear message.
6. Push the branch and open a pull request.

## Project Conventions

- Preserve the existing HTML, CSS, JavaScript, image, asset, and documentation folders.
- Do not move runtime files unless every affected relative path is updated and tested.
- Keep `README.md` at the repository root.
- Place project documentation in the existing documentation files and governance material in `.github/`.
- Optimise new images and use descriptive filenames and alt text.
- Never commit passwords, API keys, private records, or unnecessary personal information.
- Do not add generated dependencies or large binary files without a clear project need.

## Testing

For front-end changes:

- Open the project in a modern browser or use VS Code Live Server.
- Check desktop and mobile layouts.
- Verify navigation, links, forms, images, and interactive components.
- Confirm that the browser console has no new errors.

## Pull Request Checklist

- [ ] The change has a clear purpose.
- [ ] Existing paths and features still work.
- [ ] Documentation is updated where necessary.
- [ ] No sensitive information is included.
- [ ] The pull request explains what changed and how it was tested.

By contributing, you agree that your contribution may be distributed under this repository's license.
