# React Data Grid - Darwino

Darwino is coming with its own version of the react-data-grid to fix some crucial issues and eventually add new features. Ultimately, we would like to see these features contributed in the main repo but, in between, we deliver them from our own fork.

## Build and publish ##
The regular react-data-grid build has not been changed. To test the grid interactively, use:

    npm run dev-server

To build the resulting grid, use:

    npm run build

The result goes directly to the darwino library as the react-data-grid.js should be copied to react-grid, under darwino-react.


## Darwino enhancements ##

### Collapsed icons ###
The AppConstants file is defining inconsistent characters for right and down arrow. See: https://github.com/adazzle/react-data-grid/issues/972

### Expand/Collapse on the left side ###
Expandable icon is displayed on right side which is not what user generally expect. See: https://github.com/adazzle/react-data-grid/issues/890
