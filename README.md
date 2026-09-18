# Udapeople CI/CD — historical variant

Active work has moved to **[cdond-c3-udapeople](https://github.com/stevegod01/cdond-c3-udapeople)**, the canonical Udacity CI/CD case study.

This repository preserves an earlier implementation and its full Git history. Before consolidation, its default branch was [0ccb3f678faf1e81154757c0737826eff66e4642](https://github.com/stevegod01/udapeople-cicd/tree/0ccb3f678faf1e81154757c0737826eff66e4642). It is intentionally retained as a historical reference.

- [Consolidation decisions and all differing files](https://github.com/stevegod01/cdond-c3-udapeople/blob/master/docs/CONSOLIDATION.md)
- [Original course README](docs/legacy/README-before-consolidation.md)
- [Original deployment pipeline](docs/legacy/circleci-before-consolidation.yml)

The earlier pipeline is preserved as documentation. Active CircleCI configuration only prints this successor notice; it cannot deploy, migrate a database, or remove cloud resources. Application and infrastructure files remain unchanged for reference. The historical pipeline has known defects, including a frontend smoke test that exits with failure in both branches; see the canonical project for maintained checks.

Based on Udacity's [Cloud DevOps CI/CD project](https://github.com/udacity/cdond-c3-projectstarter). Course application code and this deployment exercise should not be represented as an independently authored commercial product.
