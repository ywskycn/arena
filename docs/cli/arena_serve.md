## arena serve

Serve a job.

### Synopsis

serve a job.

Available Commands:
  tensorflow,tf  Submit a TensorFlow Serving Job.
    

```
arena serve [flags]
```

### Options

```
  -h, --help   help for serve
```

### Options inherited from parent commands

```
      --arenaNamespace string   The namespace of arena system service, like TFJob (default "arena-system")
      --config string           Path to a kube config. Only required if out-of-cluster
      --loglevel string         Set the logging level. One of: debug|info|warn|error (default "info")
      --namespace string        the namespace of the job (default "default")
      --pprof                   enable cpu profile
```

### SEE ALSO

* [arena](arena.md)	 - arena is the command line interface to Arena
* [arena serve delete](arena_serve_delete.md)	 - delete a serving job and its associated pods
* [arena serve list](arena_serve_list.md)	 - list all the serving jobs
* [arena serve tensorflow](arena_serve_tensorflow.md)	 - Submit tensorflow serving job to deploy and serve machine learning models.
* [arena serve traffic-router-split](arena_serve_traffic-router-split.md)	 - Adjust traffic routing dynamically for tfserving jobs

###### Auto generated by spf13/cobra on 7-Sep-2018