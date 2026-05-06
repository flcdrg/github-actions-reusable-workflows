# Example of GitHub Actions reusable workflows

Original workflow is in [.github/workflows/before.yml](.github/workflows/before.yml).

Refactored workflow, that has the 'build' job extracted to a reusable workflow is in [.github/workflows/after.yml](.github/workflows/after.yml) (and the reusable workflow [.github/workflows/reusable-build.yml](.github/workflows/reusable-build.yml)).

Read more about reusable workflows in the [GitHub Actions documentation on Reuse workflows](https://docs.github.com/en/actions/how-tos/reuse-automations/reuse-workflows)
