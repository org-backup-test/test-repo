# R pkgs Codespace

Repo set up for using Codespaces while developing R packages. This should have all the tools you need to develop an R package!

You should see "code" and "use this template" buttons on https://github.com/NSAWTraining/RpkgsCodespace . If you do not, try making your browser window wider or zooming in or out - sometimes the buttons disappear if there is not enough room for them in the browser window.

If you don't need to save your changes, follow the [instructions to create a codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository). 

If you do need to save your changes, click "use this template" first to make your own repository with the same structure, then follow the [instructions to create a codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).

After creating the codespace, additional R packages can be installed by opening the R console and using `install.packages`.

To get the structure for an R package, use `usethis::create_package(".")` or `usethis::create_package("/workspaces/RpkgsCodespace/")`. Codespaces run on Linux.
