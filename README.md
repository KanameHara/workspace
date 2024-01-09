# TODOアプリ全体のディレクトリ構成

```
.
├── Gemfile
├── Gemfile.lock
├── README.md
├── todo-backend
│   ├── Gemfile
│   ├── Gemfile.lock
│   ├── README.md
│   ├── Rakefile
│   ├── app
│   │   ├── channels
│   │   ├── controllers
│   │   ├── jobs
│   │   ├── mailers
│   │   ├── models
│   │   └── views
│   ├── bin
│   │   ├── rails
│   │   ├── rake
│   │   └── setup
│   ├── config
│   │   ├── application.rb
│   │   ├── boot.rb
│   │   ├── cable.yml
│   │   ├── credentials.yml.enc
│   │   ├── database.yml
│   │   ├── environment.rb
│   │   ├── environments
│   │   ├── initializers
│   │   ├── locales
│   │   ├── master.key
│   │   ├── puma.rb
│   │   ├── routes.rb
│   │   └── storage.yml
│   ├── config.ru
│   ├── db
│   │   ├── development.sqlite3
│   │   ├── migrate
│   │   ├── schema.rb
│   │   └── seeds.rb
│   ├── lib
│   │   └── tasks
│   ├── log
│   │   └── development.log
│   ├── public
│   │   └── robots.txt
│   ├── storage
│   ├── tmp
│   │   ├── cache
│   │   ├── development_secret.txt
│   │   ├── pids
│   │   ├── restart.txt
│   │   ├── sockets
│   │   └── storage
│   └── vendor
└── todo-frontend
    ├── README.md
    ├── components
    │   ├── CreateTodoForm.tsx
    │   ├── DeleteTodoButton.tsx
    │   ├── EditTodoForm.tsx
    │   ├── Todo.tsx
    │   └── Todos.tsx
    ├── next-env.d.ts
    ├── next.config.js
    ├── node_modules
    │   ├── @aashutoshrathi
    │   ├── @alloc
    │   ├── @babel
    │   ├── @eslint
    │   ├── @eslint-community
    │   ├── @humanwhocodes
    │   ├── @isaacs
    │   ├── @jridgewell
    │   ├── @next
    │   ├── @nodelib
    │   ├── @pkgjs
    │   ├── @rushstack
    │   ├── @swc
    │   ├── @types
    │   ├── @typescript-eslint
    │   ├── @ungap
    │   ├── acorn
    │   ├── acorn-jsx
    │   ├── ajv
    │   ├── ansi-regex
    │   ├── ansi-styles
    │   ├── any-promise
    │   ├── anymatch
    │   ├── arg
    │   ├── argparse
    │   ├── aria-query
    │   ├── array-buffer-byte-length
    │   ├── array-includes
    │   ├── array-union
    │   ├── array.prototype.findlastindex
    │   ├── array.prototype.flat
    │   ├── array.prototype.flatmap
    │   ├── array.prototype.tosorted
    │   ├── arraybuffer.prototype.slice
    │   ├── ast-types-flow
    │   ├── asynciterator.prototype
    │   ├── asynckit
    │   ├── autoprefixer
    │   ├── available-typed-arrays
    │   ├── axe-core
    │   ├── axios
    │   ├── axobject-query
    │   ├── balanced-match
    │   ├── binary-extensions
    │   ├── brace-expansion
    │   ├── braces
    │   ├── browserslist
    │   ├── busboy
    │   ├── call-bind
    │   ├── callsites
    │   ├── camelcase-css
    │   ├── caniuse-lite
    │   ├── chalk
    │   ├── chokidar
    │   ├── client-only
    │   ├── color-convert
    │   ├── color-name
    │   ├── combined-stream
    │   ├── commander
    │   ├── concat-map
    │   ├── cross-spawn
    │   ├── cssesc
    │   ├── csstype
    │   ├── damerau-levenshtein
    │   ├── debug
    │   ├── deep-is
    │   ├── define-data-property
    │   ├── define-properties
    │   ├── delayed-stream
    │   ├── dequal
    │   ├── didyoumean
    │   ├── dir-glob
    │   ├── dlv
    │   ├── doctrine
    │   ├── eastasianwidth
    │   ├── electron-to-chromium
    │   ├── emoji-regex
    │   ├── enhanced-resolve
    │   ├── es-abstract
    │   ├── es-iterator-helpers
    │   ├── es-set-tostringtag
    │   ├── es-shim-unscopables
    │   ├── es-to-primitive
    │   ├── escalade
    │   ├── escape-string-regexp
    │   ├── eslint
    │   ├── eslint-config-next
    │   ├── eslint-import-resolver-node
    │   ├── eslint-import-resolver-typescript
    │   ├── eslint-module-utils
    │   ├── eslint-plugin-import
    │   ├── eslint-plugin-jsx-a11y
    │   ├── eslint-plugin-react
    │   ├── eslint-plugin-react-hooks
    │   ├── eslint-scope
    │   ├── eslint-visitor-keys
    │   ├── espree
    │   ├── esquery
    │   ├── esrecurse
    │   ├── estraverse
    │   ├── esutils
    │   ├── fast-deep-equal
    │   ├── fast-glob
    │   ├── fast-json-stable-stringify
    │   ├── fast-levenshtein
    │   ├── fastq
    │   ├── file-entry-cache
    │   ├── fill-range
    │   ├── find-up
    │   ├── flat-cache
    │   ├── flatted
    │   ├── follow-redirects
    │   ├── for-each
    │   ├── foreground-child
    │   ├── form-data
    │   ├── fraction.js
    │   ├── fs.realpath
    │   ├── fsevents
    │   ├── function-bind
    │   ├── function.prototype.name
    │   ├── functions-have-names
    │   ├── get-intrinsic
    │   ├── get-symbol-description
    │   ├── get-tsconfig
    │   ├── glob
    │   ├── glob-parent
    │   ├── glob-to-regexp
    │   ├── globals
    │   ├── globalthis
    │   ├── globby
    │   ├── gopd
    │   ├── graceful-fs
    │   ├── graphemer
    │   ├── has-bigints
    │   ├── has-flag
    │   ├── has-property-descriptors
    │   ├── has-proto
    │   ├── has-symbols
    │   ├── has-tostringtag
    │   ├── hasown
    │   ├── ignore
    │   ├── import-fresh
    │   ├── imurmurhash
    │   ├── inflight
    │   ├── inherits
    │   ├── internal-slot
    │   ├── is-array-buffer
    │   ├── is-async-function
    │   ├── is-bigint
    │   ├── is-binary-path
    │   ├── is-boolean-object
    │   ├── is-callable
    │   ├── is-core-module
    │   ├── is-date-object
    │   ├── is-extglob
    │   ├── is-finalizationregistry
    │   ├── is-fullwidth-code-point
    │   ├── is-generator-function
    │   ├── is-glob
    │   ├── is-map
    │   ├── is-negative-zero
    │   ├── is-number
    │   ├── is-number-object
    │   ├── is-path-inside
    │   ├── is-regex
    │   ├── is-set
    │   ├── is-shared-array-buffer
    │   ├── is-string
    │   ├── is-symbol
    │   ├── is-typed-array
    │   ├── is-weakmap
    │   ├── is-weakref
    │   ├── is-weakset
    │   ├── isarray
    │   ├── isexe
    │   ├── iterator.prototype
    │   ├── jackspeak
    │   ├── jiti
    │   ├── js-tokens
    │   ├── js-yaml
    │   ├── json-buffer
    │   ├── json-schema-traverse
    │   ├── json-stable-stringify-without-jsonify
    │   ├── json5
    │   ├── jsx-ast-utils
    │   ├── keyv
    │   ├── language-subtag-registry
    │   ├── language-tags
    │   ├── levn
    │   ├── lilconfig
    │   ├── lines-and-columns
    │   ├── locate-path
    │   ├── lodash.merge
    │   ├── loose-envify
    │   ├── lru-cache
    │   ├── merge2
    │   ├── micromatch
    │   ├── mime-db
    │   ├── mime-types
    │   ├── minimatch
    │   ├── minimist
    │   ├── minipass
    │   ├── ms
    │   ├── mz
    │   ├── nanoid
    │   ├── natural-compare
    │   ├── next
    │   ├── node-releases
    │   ├── normalize-path
    │   ├── normalize-range
    │   ├── object-assign
    │   ├── object-hash
    │   ├── object-inspect
    │   ├── object-keys
    │   ├── object.assign
    │   ├── object.entries
    │   ├── object.fromentries
    │   ├── object.groupby
    │   ├── object.hasown
    │   ├── object.values
    │   ├── once
    │   ├── optionator
    │   ├── p-limit
    │   ├── p-locate
    │   ├── parent-module
    │   ├── path-exists
    │   ├── path-is-absolute
    │   ├── path-key
    │   ├── path-parse
    │   ├── path-scurry
    │   ├── path-type
    │   ├── picocolors
    │   ├── picomatch
    │   ├── pify
    │   ├── pirates
    │   ├── postcss
    │   ├── postcss-import
    │   ├── postcss-js
    │   ├── postcss-load-config
    │   ├── postcss-nested
    │   ├── postcss-selector-parser
    │   ├── postcss-value-parser
    │   ├── prelude-ls
    │   ├── prop-types
    │   ├── proxy-from-env
    │   ├── punycode
    │   ├── queue-microtask
    │   ├── react
    │   ├── react-dom
    │   ├── react-is
    │   ├── read-cache
    │   ├── readdirp
    │   ├── reflect.getprototypeof
    │   ├── regenerator-runtime
    │   ├── regexp.prototype.flags
    │   ├── resolve
    │   ├── resolve-from
    │   ├── resolve-pkg-maps
    │   ├── reusify
    │   ├── rimraf
    │   ├── run-parallel
    │   ├── safe-array-concat
    │   ├── safe-regex-test
    │   ├── scheduler
    │   ├── semver
    │   ├── set-function-length
    │   ├── set-function-name
    │   ├── shebang-command
    │   ├── shebang-regex
    │   ├── side-channel
    │   ├── signal-exit
    │   ├── slash
    │   ├── source-map-js
    │   ├── streamsearch
    │   ├── string-width
    │   ├── string-width-cjs
    │   ├── string.prototype.matchall
    │   ├── string.prototype.trim
    │   ├── string.prototype.trimend
    │   ├── string.prototype.trimstart
    │   ├── strip-ansi
    │   ├── strip-ansi-cjs
    │   ├── strip-bom
    │   ├── strip-json-comments
    │   ├── styled-jsx
    │   ├── sucrase
    │   ├── supports-color
    │   ├── supports-preserve-symlinks-flag
    │   ├── tailwindcss
    │   ├── tapable
    │   ├── text-table
    │   ├── thenify
    │   ├── thenify-all
    │   ├── to-regex-range
    │   ├── ts-api-utils
    │   ├── ts-interface-checker
    │   ├── tsconfig-paths
    │   ├── tslib
    │   ├── type-check
    │   ├── type-fest
    │   ├── typed-array-buffer
    │   ├── typed-array-byte-length
    │   ├── typed-array-byte-offset
    │   ├── typed-array-length
    │   ├── typescript
    │   ├── unbox-primitive
    │   ├── undici-types
    │   ├── update-browserslist-db
    │   ├── uri-js
    │   ├── util-deprecate
    │   ├── watchpack
    │   ├── which
    │   ├── which-boxed-primitive
    │   ├── which-builtin-type
    │   ├── which-collection
    │   ├── which-typed-array
    │   ├── wrap-ansi
    │   ├── wrap-ansi-cjs
    │   ├── wrappy
    │   ├── yallist
    │   ├── yaml
    │   └── yocto-queue
    ├── package-lock.json
    ├── package.json
    ├── pages
    │   ├── _app.tsx
    │   ├── _document.tsx
    │   ├── api
    │   ├── index.tsx
    │   └── todos
    ├── postcss.config.js
    ├── public
    │   ├── favicon.ico
    │   ├── next.svg
    │   └── vercel.svg
    ├── styles
    │   └── globals.css
    ├── tailwind.config.ts
    ├── tsconfig.json
    └── types
        └── Todo.ts
```

# 使ったソフトウェアのバージョン記載
* Homebrew 4.2.2
* nodebrew 1.2.0
* node v20.10.0
* rbenv 1.2.0
* ruby 3.1.4p223
* Bundler 2.3.26
* Rails 7.0.8