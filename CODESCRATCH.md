# Codescratch changes

1. Making editMode optionally bindable. Before this change, using `setEditMode` would result in a Javascript error.
2. Removing reference to lodash.

I bumped the version to 1.1.1.1 which is an invalid version. This causes `npm install` to break. So if you want to build this locally, you'll need to modify the version back to a valid version first.

To build the application:

1. Change the version to something valid (like `1.1.2`)
2. I had to modify the `Gruntfile` to remove the `karam:build` task
3. `npm install -g grunt-cli`
3. `npm install`
4. `grunt`

