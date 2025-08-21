# cheminformatics-fundamentals
Me following this: https://github.com/edwardowennorman/practical_cheminformatics_tutorials

# Cheminformatics Fundamentals (RDKit)

A curated, reproducible run-through of the fundamentals from *[Practical Cheminformatics Tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials)*, executed locally in VS Code.

## Environment

```bash
conda env create -f env/environment.yml
conda activate rdkit-env
python -m ipykernel install --user --name rdkit-env --display-name "Python (rdkit-env)"
