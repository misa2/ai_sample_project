# ai_sample_project
# Sample project to streamline machine learning concepts

Created for following Udemy course

## Conda environment manual synchronization:
 1. After installing new package, run `conda env export --from-history > condaenv.yml`
 2. Edit `condaenv.yml` to remove line with  `prefix:`
 3. To update environment on another computer run: `conda env update --file condaenv.yml --prune`
 