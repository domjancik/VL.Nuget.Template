# VL.Nuget.Template 

Quick start your VL nuget development with this bare-bones VL Nuget template.

Based on https://github.com/vvvv/VL.IO.OSC

## Using the template

1. Press `Use this template` above to create a new repo based on this one (https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
2. Rename the `.nuspec` file in deployment and edit its contents
3. Update reference to this file in `workflows/main.yml`
4. Update LICENSE copyright holder
5. Replace this README.md
6. Rename/replace the root patch and start working

For more details on how to package VL Nugets, refer to the following page in the Gray Book:

https://thegraybook.vvvv.org/reference/extending/publishing.html

## Contents

### VL Library files

*.vl files located in the root

### Help patches

Place help patches in the `help` folder

Start each filename with either `Explanation` or `HowTo`, depending on the purpose of the help patch.

For more information refer to https://thegraybook.vvvv.org/reference/extending/providing-help.html

### Deployment

Contains the `.nuspec` nuget definition file. This includes the nuget metadata (name, description, ...) and included files.