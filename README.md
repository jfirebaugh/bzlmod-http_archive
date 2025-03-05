```
➜  bzlmod-http_archive bazel build @libevent
Starting local Bazel server (8.1.1) and connecting to it...
WARNING: Target pattern parsing failed.
ERROR: Skipping '@libevent': error loading package '@@+_repo_rules+libevent//': Unable to find package for @@[unknown repo 'rules_foreign_cc' requested from @@+_repo_rules+libevent]//foreign_cc:defs.bzl: The repository '@@[unknown repo 'rules_foreign_cc' requested from @@+_repo_rules+libevent]' could not be resolved: No repository visible as '@rules_foreign_cc' from repository '@@+_repo_rules+libevent'.
ERROR: error loading package '@@+_repo_rules+libevent//': Unable to find package for @@[unknown repo 'rules_foreign_cc' requested from @@+_repo_rules+libevent]//foreign_cc:defs.bzl: The repository '@@[unknown repo 'rules_foreign_cc' requested from @@+_repo_rules+libevent]' could not be resolved: No repository visible as '@rules_foreign_cc' from repository '@@+_repo_rules+libevent'.
INFO: Elapsed time: 5.188s
INFO: 0 processes.
ERROR: Build did NOT complete successfully
```
