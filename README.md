# Lol
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block*, struct fs_context*), int (*set)(struct super_block*, struct fs_context
We have enabled and configured GRGate to help automate the process of managing pull requests and ensuring that they meet certain criteria before being merged. The current statuses being checked are:

* **ci/circleci: build**: CircleCI build status
* **codecov/project**: Codecov coverage status

Refer to the `.grgate.yaml` file for detailed configuration.
