![vim-polyglot](https://i.imgur.com/9RxQK6k.png)

[![build](https://github.com/sheerun/vim-polyglot/workflows/Vim%20Polyglot%20CI/badge.svg)](https://github.com/sheerun/vim-polyglot/actions) [![Maintenance](https://img.shields.io/badge/maintained%20since-2013-yes)]()

A collection of language packs for Vim.

> One to rule them all, one to find them, one to bring them all and in the darkness bind them.

- It **won't affect your startup time**, as scripts are loaded only on demand\*.
- It **installs and updates 120+ times faster** than the <!--Package Count-->602<!--/Package Count--> packages it consists of.
- It is also more secure (scripts loaded for every filetype are generated by vim-polyglot)
- Best syntax and indentation support (no other features). Hand-selected language packs.
- Automatically detects indentation (includes performance-optimized version of [vim-sleuth](https://github.com/tpope/vim-sleuth), can be disabled)

\*To be completely honest, optimized `ftdetect` script takes around `10ms` to load.

## Installation

1. Install [Pathogen](https://github.com/tpope/vim-pathogen), [Vundle](https://github.com/VundleVim/Vundle.vim), [NeoBundle](https://github.com/Shougo/neobundle.vim), or [Plug](https://github.com/junegunn/vim-plug) package manager for Vim.
2. Use this repository as submodule or package.

For example when using [Plug](https://github.com/junegunn/vim-plug) (which I recommend):

```vim
set nocompatible

call plug#begin()

Plug 'sheerun/vim-polyglot'

call plug#end()
```

Optionally download one of the [releases](https://github.com/sheerun/vim-polyglot/releases) and unpack it directly under `~/.vim` directory.

You can also use Vim 8 built-in package manager:

```
git clone --depth 1 https://github.com/sheerun/vim-polyglot ~/.vim/pack/plugins/start/vim-polyglot
```

## Language packs

On top of all language packs from [vim repository](https://github.com/vim/vim/tree/master/runtime/syntax), vim-polyglot includes:

<!--Language Packs-->
- [acpiasl](https://github.com/martinlroth/vim-acpi-asl) (Syntax highlighting for asl and dsl files)
- [ansible](https://github.com/pearofducks/ansible-vim)
- [apiblueprint](https://github.com/kylef/apiblueprint.vim) (API Blueprint syntax highlighting for apib files)
- [applescript](https://github.com/mityu/vim-applescript) (AppleScript syntax highlighting for applescript and scpt files)
- [arduino](https://github.com/sudar/vim-arduino-syntax) (Processing syntax highlighting for pde and ino files)
- [asciidoc](https://github.com/asciidoc/vim-asciidoc) (AsciiDoc syntax highlighting for asciidoc, adoc and asc files)
- [autohotkey](https://github.com/hnamikaw/vim-autohotkey) (AutoHotkey syntax highlighting for ahk and ahkl files)
- [blade](https://github.com/jwalton512/vim-blade) (Blade syntax highlighting for blade and blade.php files)
- [brewfile](https://github.com/bfontaine/Brewfile.vim)
- [c/c++](https://github.com/vim-jp/vim-cpp) (C++ and C syntax highlighting for cpp, c++, cc, cp, cxx and 17 more files)
- [caddyfile](https://github.com/isobit/vim-caddyfile)
- [carp](https://github.com/hellerve/carp-vim) (Syntax highlighting for carp files)
- [cjsx](https://github.com/mtscout6/vim-cjsx)
- [clojure](https://github.com/guns/vim-clojure-static) (Clojure syntax highlighting for clj, boot, cl2, cljc, cljs, cljs.hl, cljscm, cljx, hic and edn files)
- [cmake](https://github.com/pboettch/vim-cmake-syntax) (CMake syntax highlighting for cmake and cmake.in files)
- [coffee-script](https://github.com/kchmck/vim-coffee-script) (CoffeeScript and Literate CoffeeScript syntax highlighting for coffee, cake, cjsx, iced, coffeekup, litcoffee and coffee.md files)
- [cpp-modern](https://github.com/bfrg/vim-cpp-modern)
- [cql](https://github.com/elubow/cql-vim) (Syntax highlighting for cql files)
- [cryptol](https://github.com/victoredwardocallaghan/cryptol.vim) (Syntax highlighting for cry, cyl, lcry and lcyl files)
- [crystal](https://github.com/rhysd/vim-crystal) (Crystal and HTML+ECR syntax highlighting for cr and ecr files)
- [csv](https://github.com/chrisbra/csv.vim) (CSV syntax highlighting for csv, tsv and tab files)
- [cucumber](https://github.com/tpope/vim-cucumber) (Gherkin syntax highlighting for feature and story files)
- [cue](https://github.com/mgrabovsky/vim-cuesheet) (Syntax highlighting for cue files)
- [dart](https://github.com/dart-lang/dart-vim-plugin) (Dart syntax highlighting for dart and drt files)
- [dhall](https://github.com/vmchale/dhall-vim) (Dhall syntax highlighting for dhall files)
- [dlang](https://github.com/JesseKPhillips/d.vim) (D syntax highlighting for d, di, lst, dd, ddoc and sdl files)
- [docker-compose](https://github.com/ekalinin/Dockerfile.vim)
- [elixir](https://github.com/elixir-lang/vim-elixir) (Elixir and HTML+EEX syntax highlighting for ex, exs, eex, html.leex and leex files)
- [elm](https://github.com/andys8/vim-elm-syntax) (Elm syntax highlighting for elm files)
- [emberscript](https://github.com/yalesov/vim-ember-script) (EmberScript syntax highlighting for em and emberscript files)
- [emblem](https://github.com/yalesov/vim-emblem) (Syntax highlighting for emblem and em files)
- [erlang](https://github.com/vim-erlang/vim-erlang-runtime) (Erlang syntax highlighting for erl, app.src, es, escript, hrl, xrl, yrl, app and yaws files)
- [fennel](https://github.com/bakpakin/fennel.vim) (Syntax highlighting for fnl files)
- [ferm](https://github.com/vim-scripts/ferm.vim) (Syntax highlighting for ferm files)
- [fish](https://github.com/blankname/vim-fish) (fish syntax highlighting for fish files)
- [flatbuffers](https://github.com/dcharbon/vim-flatbuffers) (Syntax highlighting for fbs files)
- [fsharp](https://github.com/ionide/Ionide-vim) (F# syntax highlighting for fs, fsi and fsx files)
- [gdscript](https://github.com/calviken/vim-gdscript3) (GDScript syntax highlighting for gd files)
- [git](https://github.com/tpope/vim-git) (Git Config syntax highlighting for gitconfig files)
- [gitignore](https://github.com/fszymanski/fzf-gitignore)
- [gleam](https://github.com/gleam-lang/gleam.vim) (Syntax highlighting for gleam files)
- [glsl](https://github.com/tikhomirov/vim-glsl) (GLSL syntax highlighting for glsl, fp, frag, frg, fs and 16 more files)
- [gmpl](https://github.com/maelvalais/gmpl.vim) (Syntax highlighting for mod files)
- [gnuplot](https://github.com/vim-scripts/gnuplot-syntax-highlighting) (Gnuplot syntax highlighting for gp, gnu, gnuplot, p, plot, plt and gpi files)
- [go](https://github.com/fatih/vim-go) (Go syntax highlighting for go and tmpl files)
- [gradle](https://github.com/tfnico/vim-gradle)
- [graphql](https://github.com/jparise/vim-graphql) (GraphQL syntax highlighting for graphql, gql and graphqls files)
- [haml](https://github.com/tpope/vim-haml) (Haml syntax highlighting for haml, haml.deface, hamlc and hamlbars files)
- [handlebars](https://github.com/mustache/vim-mustache-handlebars) (Mustache and Handlebars syntax highlighting for mustache, hogan, hulk, hjs, handlebars, hbs, hdbs and hb files)
- [haproxy](https://github.com/CH-DanReif/haproxy.vim) (HAProxy syntax highlighting)
- [haskell](https://github.com/neovimhaskell/haskell-vim) (Haskell syntax highlighting for hs, hs-boot, hsc, bpk and hsig files)
- [haxe](https://github.com/yaymukund/vim-haxe) (Haxe syntax highlighting for hx and hxsl files)
- [hcl](https://github.com/b4b4r07/vim-hcl) (HCL syntax highlighting for hcl, nomad and workflow files)
- [helm](https://github.com/towolf/vim-helm)
- [help](https://github.com/neovim/neovim/tree/master/runtime)
- [hive](https://github.com/zebradil/hive.vim) (HiveQL syntax highlighting for q, hql and ql files)
- [html5](https://github.com/sheerun/html5.vim)
- [i3](https://github.com/mboughaba/i3config.vim) (Syntax highlighting for i3.config and i3config files)
- [icalendar](https://github.com/chutzpah/icalendar.vim) (Syntax highlighting for ics files)
- [idris2](https://github.com/edwinb/idris2-vim) (Syntax highlighting for idr, ipkg and lidr files)
- [idris](https://github.com/idris-hackers/idris-vim) (Idris syntax highlighting for idr and lidr files)
- [ion](https://github.com/vmchale/ion-vim) (Syntax highlighting for ion files)
- [javascript-sql](https://github.com/statico/vim-javascript-sql)
- [javascript](https://github.com/pangloss/vim-javascript) (JavaScript syntax highlighting for js, bones, cjs, es, es6 and 17 more files)
- [jenkins](https://github.com/martinda/Jenkinsfile-vim-syntax) (Syntax highlighting for jenkinsfile and Jenkinsfile files)
- [jq](https://github.com/vito-c/jq.vim) (JSONiq syntax highlighting for jq files)
- [json5](https://github.com/GutenYe/json5.vim) (JSON5 syntax highlighting for json5 files)
- [json](https://github.com/elzr/vim-json) (JSON syntax highlighting for json, avsc, geojson, gltf, har and 13 more files)
- [jsonc](https://github.com/neoclide/jsonc.vim) (Syntax highlighting for cjson and jsonc files)
- [jsonnet](https://github.com/google/vim-jsonnet) (Jsonnet syntax highlighting for jsonnet and libsonnet files)
- [jst](https://github.com/briancollins/vim-jst) (EJS syntax highlighting for ejs, ect and jst files)
- [jsx](https://github.com/MaxMEllon/vim-jsx-pretty) (JSX syntax highlighting for jsx files)
- [julia](https://github.com/JuliaEditorSupport/julia-vim) (Julia syntax highlighting for jl files)
- [kotlin](https://github.com/udalov/kotlin-vim) (Kotlin syntax highlighting for kt, ktm and kts files)
- [ledger](https://github.com/ledger/vim-ledger) (Syntax highlighting for ldg, ledger and journal files)
- [lilypond](https://github.com/anowlcalledjosh/vim-lilypond) (LilyPond syntax highlighting for ly and ily files)
- [livescript](https://github.com/gkz/vim-ls) (LiveScript syntax highlighting for ls files)
- [llvm](https://github.com/rhysd/vim-llvm) (LLVM syntax highlighting for ll and td files)
- [log](https://github.com/MTDL9/vim-log-highlighting) (Syntax highlighting for log and LOG files)
- [lua](https://github.com/tbastos/vim-lua) (Lua syntax highlighting for lua, fcgi, nse, p8, rbxs, rockspec and wlua files)
- [mako](https://github.com/sophacles/vim-bundle-mako) (Mako syntax highlighting for mako and mao files)
- [markdown](https://github.com/plasticboy/vim-markdown) (Markdown syntax highlighting for md, markdown, mdown, mdwn, mkd, mkdn, mkdown, ronn and workbook files)
- [mathematica](https://github.com/voldikss/vim-mma) (Mathematica syntax highlighting for mathematica, cdf, m, ma, mt and 6 more files)
- [mdx](https://github.com/jxnblk/vim-mdx-js) (Syntax highlighting for mdx files)
- [meson](https://github.com/mesonbuild/meson/tree/master/data/syntax-highlighting/vim) (Meson syntax highlighting for wrap files)
- [mint](https://github.com/IrenejMarc/vim-mint) (Syntax highlighting for mint files)
- [moonscript](https://github.com/leafo/moonscript-vim) (MoonScript syntax highlighting for moon files)
- [nginx](https://github.com/chr4/nginx.vim) (Nginx syntax highlighting for nginx, nginxconf and vhost files)
- [nim](https://github.com/zah/nim.vim) (Nim syntax highlighting for nim, nim.cfg, nimble, nimrod and nims files)
- [nix](https://github.com/LnL7/vim-nix) (Nix syntax highlighting for nix files)
- [objc](https://github.com/b4winckler/vim-objc) (Objective-C syntax highlighting for m and h files)
- [ocaml](https://github.com/rgrinberg/vim-ocaml) (OCaml syntax highlighting for ml, eliom, eliomi, ml4, mli and 13 more files)
- [octave](https://github.com/McSinyx/vim-octave) (Syntax highlighting for oct and m files)
- [odin](https://github.com/Tetralux/odin.vim) (Odin syntax highlighting for odin files)
- [opencl](https://github.com/petRUShka/vim-opencl) (OpenCL syntax highlighting for cl and opencl files)
- [perl](https://github.com/vim-perl/vim-perl) (Perl syntax highlighting for pl, al, cgi, fcgi, perl and 12 more files)
- [pest](https://github.com/pest-parser/pest.vim) (Syntax highlighting for pest files)
- [pgsql](https://github.com/lifepillar/pgsql.vim) (PLpgSQL syntax highlighting for pgsql files)
- [php](https://github.com/StanAngeloff/php.vim) (PHP syntax highlighting for php, aw, ctp, fcgi, inc and 7 more files)
- [plantuml](https://github.com/aklt/plantuml-syntax) (PlantUML syntax highlighting for puml, iuml, plantuml, uml and pu files)
- [pony](https://github.com/jakwings/vim-pony) (Pony syntax highlighting for pony files)
- [powershell](https://github.com/PProvost/vim-ps1) (PowerShell syntax highlighting for ps1, psd1, psm1, pssc and ps1xml files)
- [protobuf](https://github.com/uarun/vim-protobuf) (Protocol Buffer syntax highlighting for proto files)
- [pug](https://github.com/digitaltoad/vim-pug) (Pug syntax highlighting for jade and pug files)
- [puppet](https://github.com/rodjek/vim-puppet) (Puppet syntax highlighting for pp and epp files)
- [purescript](https://github.com/purescript-contrib/purescript-vim) (PureScript syntax highlighting for purs files)
- [python-compiler](https://github.com/aliev/vim-compiler-python)
- [python-indent](https://github.com/Vimjas/vim-python-pep8-indent)
- [python](https://github.com/vim-python/python-syntax) (Python syntax highlighting for py, cgi, fcgi, gyp, gypi and 14 more files)
- [qmake](https://github.com/artoj/qmake-syntax-vim) (QMake syntax highlighting for pro and pri files)
- [qml](https://github.com/peterhoeg/vim-qml) (QML syntax highlighting for qml and qbs files)
- [r-lang](https://github.com/vim-scripts/R.vim) (R syntax highlighting for r, rsx, s, S and rd files)
- [racket](https://github.com/wlangstroth/vim-racket) (Racket syntax highlighting for rkt, rktd, rktl and scrbl files)
- [ragel](https://github.com/jneen/ragel.vim) (Ragel syntax highlighting for rl files)
- [raku](https://github.com/Raku/vim-raku) (Raku syntax highlighting for 6pl, 6pm, nqp, p6, p6l and 12 more files)
- [raml](https://github.com/IN3D/vim-raml) (RAML syntax highlighting for raml files)
- [razor](https://github.com/adamclerk/vim-razor) (HTML+Razor syntax highlighting for cshtml and razor files)
- [reason](https://github.com/reasonml-editor/vim-reason-plus) (Reason syntax highlighting for re and rei files)
- [requirements](https://github.com/raimon49/requirements.txt.vim) (Syntax highlighting for pip files)
- [rspec](https://github.com/keith/rspec.vim)
- [rst](https://github.com/marshallward/vim-restructuredtext) (reStructuredText syntax highlighting for rst, rest, rest.txt and rst.txt files)
- [ruby](https://github.com/vim-ruby/vim-ruby) (Ruby and HTML+ERB syntax highlighting for rb, builder, eye, fcgi, gemspec and 25 more files)
- [rust](https://github.com/rust-lang/rust.vim) (Rust syntax highlighting for rs and rs.in files)
- [scala](https://github.com/derekwyatt/vim-scala) (Scala syntax highlighting for scala, kojo and sc files)
- [scss](https://github.com/cakebaker/scss-syntax.vim) (SCSS syntax highlighting for scss files)
- [sh](https://github.com/arzg/vim-sh) (Shell syntax highlighting for sh, bash, bats, cgi, command and 7 more files)
- [slim](https://github.com/slim-template/vim-slim) (Slim syntax highlighting for slim files)
- [slime](https://github.com/slime-lang/vim-slime-syntax) (Syntax highlighting for slime files)
- [smt2](https://github.com/bohlender/vim-smt2) (SMT syntax highlighting for smt2 and smt files)
- [solidity](https://github.com/tomlion/vim-solidity) (Solidity syntax highlighting for sol files)
- [stylus](https://github.com/wavded/vim-stylus) (Stylus syntax highlighting for styl and stylus files)
- [svelte](https://github.com/evanleck/vim-svelte/tree/main) (Svelte syntax highlighting for svelte files)
- [svg-indent](https://github.com/jasonshell/vim-svg-indent)
- [svg](https://github.com/vim-scripts/svg.vim) (SVG syntax highlighting for svg files)
- [swift](https://github.com/keith/swift.vim) (Swift syntax highlighting for swift files)
- [sxhkd](https://github.com/baskerville/vim-sxhkdrc) (Syntax highlighting for sxhkdrc files)
- [systemd](https://github.com/wgwoods/vim-systemd-syntax) (Syntax highlighting for automount, dnssd, link, mount, netdev and 9 more files)
- [terraform](https://github.com/hashivim/vim-terraform) (Syntax highlighting for tf and tfvars files)
- [textile](https://github.com/timcharper/textile.vim) (Textile syntax highlighting for textile files)
- [thrift](https://github.com/solarnz/thrift.vim) (Thrift syntax highlighting for thrift files)
- [tmux](https://github.com/ericpruitt/tmux.vim/tree/master/vim)
- [toml](https://github.com/cespare/vim-toml) (TOML syntax highlighting for toml files)
- [tptp](https://github.com/c-cube/vim-tptp) (Syntax highlighting for p, tptp and ax files)
- [twig](https://github.com/lumiliet/vim-twig) (Twig syntax highlighting for twig and xml.twig files)
- [typescript](https://github.com/HerringtonDarkholme/yats.vim) (TypeScript and TSX syntax highlighting for ts and tsx files)
- [unison](https://github.com/unisonweb/unison/tree/trunk/editor-support/vim) (Syntax highlighting for u and uu files)
- [v](https://github.com/ollykel/v-vim) (V syntax highlighting for v, vv and vsh files)
- [vala](https://github.com/arrufat/vala.vim) (Vala syntax highlighting for vala, vapi and valadoc files)
- [vbnet](https://github.com/vim-scripts/vbnet.vim) (Visual Basic .NET syntax highlighting for vb and vbhtml files)
- [vcl](https://github.com/smerrill/vcl-vim-plugin) (VCL syntax highlighting for vcl files)
- [velocity](https://github.com/lepture/vim-velocity) (Syntax highlighting for vm files)
- [vue](https://github.com/posva/vim-vue) (Vue syntax highlighting for vue and wpy files)
- [xdc](https://github.com/amal-khailtash/vim-xdc-syntax) (Syntax highlighting for xdc files)
- [xml](https://github.com/amadeus/vim-xml) (XML syntax highlighting for xml, adml, admx, ant, axml and 94 more files)
- [xsl](https://github.com/vim-scripts/XSLT-syntax) (XSLT syntax highlighting for xslt and xsl files)
- [yard](https://github.com/noprompt/vim-yardoc)
- [zephir](https://github.com/xwsoul/vim-zephir) (Zephir syntax highlighting for zep files)
- [zig](https://github.com/ziglang/zig.vim) (Zig syntax highlighting for zir, zig and zir files)
- [zinit](https://github.com/zinit-zsh/zplugin-vim-syntax)
<!--/Language Packs-->

## Updating

You can either wait for new patch release with updates or run `make` by yourself.

## Troubleshooting

Please make sure you have `set nocompatible` in your `.vimrc` (or use something like [sheerun/vimrc](https://github.com/sheerun/vimrc))

Individual language packs can be disabled by setting `g:polyglot_disabled` as follows:

**Please declare this variable before polyglot is loaded (at the top of .vimrc)**

```vim
let g:polyglot_disabled = ['markdown']
```

The list of available languages to disable is shown above.

If you wish to use filetype detection by Vim Polyglot but you'd like to use your own syntax-highlighting plugin, you can append `.plugin` to disabled entry, like below. Disabling Vim Polyglot filetype plugin won't disable native Vim filetype plugin.

```vim
let g:polyglot_disabled = ['markdown.plugin']
```

Please note that disabling a language won't make in your vim startup any faster / slower (only for specific this specific filetype). All plugins are lazily loaded only when they are really needed. 

## Autoindent

Vim Polyglot tries to automatically detect indentation settings (just like vim-sleuth). If this feature is not working for you for some reason, please file an issue and disable it temporarily with:

```vim
let g:polyglot_disabled = ['autoindent']
```

## Default settings

Vim Polyglot includes vim-sensible plugin, which is usually necessary for editing any language. This can be disabled with:


```vim
let g:polyglot_disabled = ['sensible']
```

## Contributing

Language packs are periodically updated using automated `scripts/build` script.

Feel free to add your language to `packages.yaml` + `heuristics.yaml`, and send pull-request. You can run `make test` to run rough tests. And `make dev` for easy development.

## License

See linked repositories for detailed license information. This repository is MIT-licensed.
