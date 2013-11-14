PoliteJS
========

## Main Developement Plan

### v0.x

_PoliteJS_ will run with a combination of _GruntJS_ third party plugins and the core module which exposes itself as a _GruntJS_ plugin.

```
// compile the blog locally
grunt, grunt build

// working session, compile locally when contents changes
grunt start

// compile locally and push to remote target (ftp, GitHub, xxx)
grunt deploy
```

### v1.x

_GruntJS_ third party plugins will be moved to the core to avoid dependency on _GruntJS_.  
_PoliteJS_ become a node executable or something similar.

```
// compile the blog locally
politejs

// working session, compile locally when contents changes
politejs start

// compile locally and push to remote target (ftp, GitHub, xxx)
politejs deploy
```


### v2.x

_PoliteJS_ will be a platform independent application with its own _GUI_ (probably with _[node-webkit](https://github.com/rogerwang/node-webkit)_).

> _PoliteJS_ will be a website + blog IDE

Any person in the world will be able to use _PoliteJS_ to build its personal website or blog and, maybe, some simple institutional websites.


### 3.x

Will be introduced the **templates market** and **plugins market** to download (may be buy) templates and plugins from inside the _PoliteJS IDE_.

Will be introduced dedicated hosting solutions both free and with some payment plans.

