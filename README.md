g8.sbt:

    [scala]
      version: 2.8.0
    [app]
      org: net.databinder
      name: giter8
      version: 0.1.0-SNAPSHOT
      class: giter8.Giter8
    [repositories]
      local
      scala-tools-releases
    [boot]
      directory: /path/to/home/.giter8/boot

g8:

    sbt @g8.sbt "$@"