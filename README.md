# Nanochat-tasks

This repository is derived from [nanochat](https://github.com/karpathy/nanochat) repository for LLMs evaluation. It is used as a benchmark to evaluate the models trained in [gpt-lib](https://github.com/art-test-stack/gpt-lib). 

I have done the following commands to make it, for reproducity:

```bash
git clone git@github.com:karpathy/nanochat.git
git filter-branch --subdirectory-filter tasks -- --all
git remote remove origin
git remote add origin git@github.com:art-test-stack/nanochat-tasks.git
```