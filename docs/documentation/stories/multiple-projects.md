# Multiple Projects

Angular CLI supports multiple applications within one workspace.

To create another app you can use the following command:
```sh
ng generate application my-other-app
```

The new application will be generated inside `projects/my-other-app`. If you wish to override root folder specify `--project-root applicationPath`

Now we can `serve`, `build` etc. both the apps by passing the project name with the commands:

```sh
ng serve my-other-app
```

You can also create libraries, which is detailed in [Create a library](stories/create-library).