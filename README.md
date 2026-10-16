# devops-heros — Session 16: GitHub Actions

Runnable copies of the Session 16 workflows from [NeuralSynth/devops-heros](https://github.com/NeuralSynth/devops-heros/tree/main/session-16-github-actions), placed at the repo root so GitHub Actions executes them.

| Workflow | Source folder | Shows |
| :--- | :--- | :--- |
| `hello.yml` | 03-github-actions-intro | First workflow on `push` |
| `build.yml` | 04-workflows | push/PR triggers, setup-python, pytest |
| `jobs-steps.yml` | 05-jobs-steps | Multiple jobs and steps |
| `matrix-demo.yml` | 06-runners | Matrix over Python 3.10 / 3.11 |
| `secrets-demo.yml` | 07-secrets | Using `secrets.GITHUB_TOKEN` safely |
| `artifacts-demo.yml` | 08-artifacts | `actions/upload-artifact` |
| `ci.yml` | 09-build-test-pipeline | lint → test with coverage → artifacts |
