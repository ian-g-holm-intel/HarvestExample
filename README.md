# Harvest Example
This repository serves as an example of harvesting files for a WiX v4 installer MSI. Rather than relying on a static list of files to be bundled, this will collect files from the build output of other projects and use a transform file to filter out any files with unwanted extensions such as debugging symbols.
