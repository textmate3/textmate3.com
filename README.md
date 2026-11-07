# textmate3.com

The TextMate 3 website, served by GitHub Pages at `https://textmate3.com`.

The human-facing site grows here, separate from `api.textmate3.com`, which serves the machine endpoints the application talks to. Every page is a placeholder for now, so the application can link to its final address.

| Route                     | What it is                                                         |
| ------------------------- | ------------------------------------------------------------------ |
| `/`                       | The home page                                                      |
| `/docs`                   | Redirects to the current manual, `/docs/2.1`                       |
| `/docs/1`                 | The TextMate 1 manual as MacroMates published it, with a banner    |
| `/docs/2.0`               | The TextMate 2.0 manual as MacroMates published it, with a banner  |
| `/docs/2.1`               | The manual for the current version                                 |
| `/docs/3.0`               | The roadmap for the next major version                             |
| `/blog`                   | The blog, with posts at `/blog/YYYY/MM/DD/slug`                    |
| `/faq`                    | Frequently asked questions                                         |
| `/support`                | Where to get help, which is GitHub issues on `textmate3/textmate`  |

Each route is a folder with an `index.html`. The shared styles are in `assets/site.css`.
