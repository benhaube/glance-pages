<p align="center">
    <img src=".assets/logo.webp" alt="Glance logo" width="300" height="300">
</p>
<p align="center">
    <a href="https://github.com/benhaube/glance-pages/blob/main/LICENSE">
        <img alt="license badge" src="https://img.shields.io/github/license/benhaube/glance-pages?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGRjZCQ0IiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiBjbGFzcz0ibHVjaWRlIGx1Y2lkZS1zY2FsZSBwcmV2aWV3LWljb24iPjxwYXRoIGQ9Ik0xMiAzdjE4Ii8%2BPHBhdGggZD0ibTE5IDggMyA4YTUgNSAwIDAgMS02IDB6VjciLz48cGF0aCBkPSJNMyA3aDFhMTcgMTcgMCAwIDAgOC0yIDE3IDE3IDAgMCAwIDggMmgxIi8%2BPHBhdGggZD0ibTUgOCAzIDhhNSA1IDAgMCAxLTYgMHpWNyIvPjxwYXRoIGQ9Ik03IDIxaDEwIi8%2BPC9zdmc%2B&label=License&color=%23FF6BCB">
    </a>
    <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/benhaube/glance-pages?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGRjZCQ0IiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiBjbGFzcz0ibHVjaWRlIGx1Y2lkZS1naXQtY29tbWl0LWhvcml6b250YWwgcHJldmlldy1pY29uIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIzIi8%2BPGxpbmUgeDE9IjMiIHgyPSI5IiB5MT0iMTIiIHkyPSIxMiIvPjxsaW5lIHgxPSIxNSIgeDI9IjIxIiB5MT0iMTIiIHkyPSIxMiIvPjwvc3ZnPg%3D%3D&color=%23FF6BCB">
    
</p>
<h1 align="center">
    My Glance Dashboard Configuration
</h1>

This is the collection of YAML files that makes up my [Glance](https://github.com/glanceapp/glance) dashboard configuration. Currently, the service is using a forked Docker image that adds features called [Dynacat](https://github.com/Panonim/dynacat). Dynacat is fully compatible with Glance, but uses a different configuration file, `dynacat.yml`. The old `glance.yml` configuration file remains with the same configuration to maintain compatibility with the Glance Docker image.

See the [Dynacat Documentation](https://dynacat.artur.zone/) for configuration information.

## Directory Structure

```
.
└── glance-pages
    ├── assets
    │   ├── icons
    │   │   ├── *.png
    │   │   └── *.svg
    │   ├── logo.png
    │   ├── logo.svg
    │   └── user.css
    ├── config
    │   ├── pages
    │   │   ├── formula1.yml
    │   │   ├── home.yml
    │   │   └── network.yml
    │   ├── widgets
    │   │   └── *.yml
    │   ├── dynacat.yml
    │   └── glance.yml
    ├── example-compose.yml
    └── README.md
```
