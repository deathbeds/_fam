# _fam

> Binders for deathbeds friends & family night

## 07-11-2020

| Status | Demo              | Note                                         |
|--------|------------------ |----------------------------------------------|
| MVP    | [![b-mvp][]][mvp] | Click here, probably.                        |
| WIP    | [![b-wip][]][wip] | Abandon hope, all ye who enter.              |

## Prior parks

| MVP    | [![b-mvp0711][]][mvp0711] | Click here, probably.                        |
| WIP    | [![b-wip0711][]][wip0711] | Abandon hope, all ye who enter.              |

[wip]: https://mybinder.org/v2/gh/deathbeds/_fam/07-25-2020?urlpath=lab/tree/README.md
[b-wip]: https://img.shields.io/badge/DEATHBEDS-07--25--2020%CE%B2-000?style=for-the-badge&logo=Jupyter&logoColor=fff&color=000

[mvp]: https://mybinder.org/v2/gh/deathbeds/_fam/4802ec0?urlpath=lab/tree/README.md
[b-mvp]: https://img.shields.io/badge/DEATHBEDS-07--25--2020%CE%B2-000?style=for-the-badge&logo=Jupyter&logoColor=fff&color=000

[wip0711]: https://mybinder.org/v2/gh/deathbeds/_fam/07-11-2020?urlpath=lab/tree/README.md
[b-wip0711]: https://img.shields.io/badge/DEATHBEDS-07--11--2020%CE%B2-000?style=for-the-badge&logo=Jupyter&logoColor=fff&color=000

[mvp0711]: https://mybinder.org/v2/gh/deathbeds/_fam/4802ec0?urlpath=lab/tree/README.md
[b-mvp0711]: https://img.shields.io/badge/DEATHBEDS-07--11--2020-fff?style=for-the-badge&logo=Jupyter&logoColor=000&color=f37626

### Featured Forks

Unreleased packages and features

| Upstream                  | Hot Jam                |
|---------------------------|------------------------|
| _your jam here_           | [PRs welcome][]        |
| [jupyterlab-drawio][]     | PDF, Drawio Notebooks  |
| [jupyterlab-outsource][]  | Lab 2.0                |
| [jupyterlab-lsp][]        | Language Server Kernel |
| [jupyterlab-videochat][]  | Hot Links, Manager     |
| [webio][]                 | Lab 2.0                |
| [wxyz][]                  | Lab 2.0                |

[jupyter-videochat]: https://github.com/yuvipanda/jupyter-videochat
[jupyterlab-drawio]: https://github.com/QuantStack/jupyterlab-drawio
[jupyterlab-outsource]: https://github.com/deathbeds/jupyterlab-outsource
[jupyterlab-lsp]: https://github.com/krassowski/jupyterlab-lsp
[jupyterlab-videochat]: https://github.com/yuvipanda/jupyter-videochat
[jupyterlab-debugger]: https://github.com/jupyterlab/debugger
[PRs welcome]: https://github.com/deathbeds/_fam/pulls
[webio]: https://github.com/JuliaGizmos/WebIO.jl
[wxyz]: https://github.com/deathbeds/wxyz

### Julia Language Server

> if configured, is currently returing a basically empty `ServerCapabilities`
> so I must be missing something... but _should_ be something like this,
> added to `jupyter_notebook_config.json`:
>  ```yaml
>    "LanguageServerManager": {
>      "language_servers": {
>        "julia-languageserver": {
>          "version": 3,
>          "argv": ["julia", "--debug=yes", "--project=.", "-e", "using LanguageServer, LanguageServer.SymbolServer; runserver()", "."],
>          "languages": ["julia"],
>          "display_name": "LanguageServer.jl",
>          "mimetypes": ["text/julia", "text/x-julia"]
>        }
>      }
>    }
>  ```
