# _fam

> Binders for deathbeds friends & family night

## 07-11-2020

| Status | Demo              | Note                                         |
|--------|------------------ |----------------------------------------------|
| MVP    | [![b-mvp][]][mvp] | Click here, probably.                        |
| WIP    | [![b-wip][]][wip] | Abandon hope, all ye who enter.              |

[wip]: https://mybinder.org/v2/gh/deathbeds/_fam/07-11-2020?urlpath=lab/tree/README.md
[b-wip]: https://img.shields.io/badge/DEATHBEDS-07--11--2020%CE%B2-000?style=for-the-badge&logo=Jupyter&logoColor=fff&color=000

[mvp]: https://mybinder.org/v2/gh/deathbeds/_fam/44882fa?urlpath=lab/tree/README.md
[b-mvp]: https://img.shields.io/badge/DEATHBEDS-07--11--2020-fff?style=for-the-badge&logo=Jupyter&logoColor=000&color=f37626

### Featured Forks

Unreleased packages and features

| Upstream                  | Hot Jam                |
|---------------------------|------------------------|
| _your jam here_           |                        |
| [jupyterlab-drawio][]     | PDF, Drawio Notebooks  |
| [jupyterlab-outsource][]  | Lab 2.0                |
| [jupyterlab-videochat][]  | Hot Links, Manager     |
| [jupyterlab-lsp][]        | Language Server Kernel |
| [wxyz][]                  | Lab 2.0                |

[jupyter-videochat]: https://github.com/yuvipanda/jupyter-videochat
[jupyterlab-drawio]: https://github.com/QuantStack/jupyterlab-drawio
[jupyterlab-outsource]: https://github.com/deathbeds/jupyterlab-outsource
[jupyterlab-lsp]: https://github.com/krassowski/jupyterlab-lsp
[jupyterlab-videochat]: https://github.com/yuvipanda/jupyter-videochat
[jupyterlab-debugger]: #
[wxyz]: https://github.com/deathbeds/wxyz

### Julia Language Server

> should be something like this

```json
  "LanguageServerManager": {
    "language_servers": {
      "julia-languageserver": {
        "version": 3,
        "cmd": ["julia", "--project=.", "-e", "using LanguageServer, LanguageServer.SymbolServer; runserver()", "."],
        "languages": ["julia"],
        "display_name": "LanguageServer.jl",
        "mimetypes": ["text/julia", "text/x-julia"]
      }
    }
  }
```
