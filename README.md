PEP257 mirror
=============

Mirror of the PEP257 package for pre-commit.

For pre-commit see: https://github.com/pre-commit/pre-commit

For PEP257 see: https://github.com/GreenSteam/pep257


### Using PEP257 with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/FalconSocial/pre-commit-mirrors-pep257
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: pep257
