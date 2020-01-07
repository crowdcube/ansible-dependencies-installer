# Ansible Role: Dependencies installer

Accepts list of dependencies and uses apt-get to install it one-by-one.

## Requirements

Ansible 2.5+

## Role Variables

Available variables are listed below, along with default values:

    dependencies: []

Example usage:

    dependencies:
      - foo
      - foo-tools
      - bar
    
## Dependencies

None.
