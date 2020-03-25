# UPM_CI_Template

UPM_CI_Template is a UnityPackageManager template primary used for packages, which requires a Continuous Integration solution in terms of publishing and development.

The project was developed with **Unity 2019.3.6f1**.

## UPM Template

The UPM package is an embedded package located within a Unity Sample/Development Setup. This will simplify further development by only checking out this repository and make further adjustments within the repository itself. (Instead of having multiple Git Repositories used -> 1. Development Repository | 2. Package Repository itself)

Depending on your use case - add files to the specific package folder (Editor|Runtime|Tests) or remove them to make YOUR own CLEAN custom package

**I highly recommend to delete all *meta files within the package to force regeneration of the GUID's after copying the template!**

**Simply copy&paste the whole code and adjust it as you want!**

## CI Approach

By using the instruction given by Favo Yang [How to Maintain UPM Package](https://medium.com/openupm/how-to-maintain-upm-package-part-1-7b4daf88d4c4), I've created this template to demonstrate the documented instructions.

## Usage

1. Checkout or clone the template repository
2. Copy/Remove/Adept required folders
3. Remove all meta files within the package after copying to force GUID regeneration!
4. Append the package and commit it on your repository
5. Apply possible GitLab|Github CI scripts.
