# win-pipelines-yaml
For MS Windows

Trying out the pipeline as code plugin for the yaml format.

All config must be in a file named `ci.gocd.yaml`

To use this just place this snippet in your `cruise-config.xml` file, which you can edit from the GUI in GoCD:
```
  <config-repos>
    <config-repo plugin="yaml.config.plugin">
      <git url="https://github.com/pm-gocd/win-pipelines-yaml.git" />
    </config-repo>
  </config-repos>
```
