# Ansible Role: Dependencies installer

Accepts list of dependencies using apt-get.

## Requirements

Ansible 2.5+

## Role Variables

Available variables are listed below, along with default values:

    apt_dependencies: []

Example usage:

    apt_dependencies:
      - foo
      - foo-tools
      - bar
    
## Dependencies

None.
