# vue-ztltjv

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/vue-ztltjv)

"Node_modules"
"Languages & Reasoures"
\_react.js, node,js, npm, vscode/vse,

**\*** Txt File of Installtion and Configuration \*\*\*\*

\***\* To see a list of supported npm commands, run: \*\***

@penguin:~$ npm help npm

All commands:

access, adduser, audit, bugs, cache, ci, completion,
config, dedupe, deprecate, diff, dist-tag, docs, doctor,
edit, exec, explain, explore, find-dupes, fund, get, help,
hook, init, install, install-ci-test, install-test, link,
ll, login, logout, ls, org, outdated, owner, pack, ping,
pkg, prefix, profile, prune, publish, query, rebuild, repo,
restart, root, run-script, search, set, shrinkwrap, star,
stars, start, stop, team, test, token, uninstall, unpublish,
unstar, update, version, view, whoami
Specify configs in the ini-formatted file: /home/user/.npmrc or on the command line via: npm --key=value

All commands:

access Set access level on published packages

                Usage:
                npm access list packages [<user>|<scope>|<scope:team> [<package>]
                npm access list collaborators [<package> [<user>]]
                npm access get status [<package>]
                npm access set status=public|private [<package>]
                npm access set mfa=none|publish|automation [<package>]
                npm access grant <read-only|read-write> <scope:team> [<package>]
                npm access revoke <scope:team> [<package>]

                Options:
                [--json] [--otp <otp>] [--registry <registry>]

                Run "npm help access" for more info

adduser Add a registry user account

                Usage:
                npm adduser

                Options:
                [--registry <registry>] [--scope <@scope>] [--auth-type <legacy|web>]

                alias: add-user

                Run "npm help adduser" for more info

audit Run a security audit

                Usage:
                npm audit [fix|signatures]

                Options:
                [--audit-level <info|low|moderate|high|critical|none>] [--dry-run] [-f|--force]
                [--json] [--package-lock-only]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]]
                [--foreground-scripts] [--ignore-scripts]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                Run "npm help audit" for more info

bugs Report bugs for a package in a web browser

                Usage:
                npm bugs [<pkgname> [<pkgname> ...]]

                Options:
                [--no-browser|--browser <browser>] [--registry <registry>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                alias: issues

                Run "npm help bugs" for more info

cache Manipulates packages cache

                Usage:
                npm cache add <package-spec>
                npm cache clean [<key>]
                npm cache ls [<name>@<version>]
                npm cache verify

                Options:
                [--cache <cache>]

                Run "npm help cache" for more info

ci Clean install a project

                Usage:
                npm ci

                Options:
                [-S|--save|--no-save|--save-prod|--save-dev|--save-optional|--save-peer|--save-bundle]
                [-E|--save-exact] [-g|--global] [--install-strategy <hoisted|nested|shallow>]
                [--legacy-bundling] [--global-style]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]]
                [--strict-peer-deps] [--no-package-lock] [--foreground-scripts]
                [--ignore-scripts] [--no-audit] [--no-bin-links] [--no-fund] [--dry-run]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                aliases: clean-install, ic, install-clean, isntall-clean

                Run "npm help ci" for more info

completion Tab Completion for npm

                Usage:
                npm completion

                Run "npm help completion" for more info

config Manage the npm configuration files

                Usage:
                npm config set <key>=<value> [<key>=<value> ...]
                npm config get [<key> [<key> ...]]
                npm config delete <key> [<key> ...]
                npm config list [--json]
                npm config edit
                npm config fix

                Options:
                [--json] [-g|--global] [--editor <editor>] [-L|--location <global|user|project>]
                [-l|--long]

                alias: c

                Run "npm help config" for more info

dedupe Reduce duplication in the package tree

                Usage:
                npm dedupe

                Options:
                [--install-strategy <hoisted|nested|shallow>] [--legacy-bundling]
                [--global-style] [--strict-peer-deps] [--no-package-lock]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]] [--ignore-scripts]
                [--no-audit] [--no-bin-links] [--no-fund] [--dry-run]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                alias: ddp

                Run "npm help dedupe" for more info

deprecate Deprecate a version of a package

                Usage:
                npm deprecate <package-spec> <message>

                Options:
                [--registry <registry>] [--otp <otp>]

                Run "npm help deprecate" for more info

diff The registry diff command

                Usage:
                npm diff [...<paths>]

                Options:
                [--diff <package-spec> [--diff <package-spec> ...]] [--diff-name-only]
                [--diff-unified <number>] [--diff-ignore-all-space] [--diff-no-prefix]
                [--diff-src-prefix <path>] [--diff-dst-prefix <path>] [--diff-text] [-g|--global]
                [--tag <tag>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                Run "npm help diff" for more info

dist-tag Modify package distribution tags

                Usage:
                npm dist-tag add <package-spec (with version)> [<tag>]
                npm dist-tag rm <package-spec> <tag>
                npm dist-tag ls [<package-spec>]

                Options:
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                alias: dist-tags

                Run "npm help dist-tag" for more info

docs Open documentation for a package in a web browser

                Usage:
                npm docs [<pkgname> [<pkgname> ...]]

                Options:
                [--no-browser|--browser <browser>] [--registry <registry>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                alias: home

                Run "npm help docs" for more info

doctor Check your npm environment

                Usage:
                npm doctor [ping] [registry] [versions] [environment] [permissions] [cache]

                Options:
                [--registry <registry>]

                Run "npm help doctor" for more info

edit Edit an installed package

                Usage:
                npm edit <pkg>[/<subpkg>...]

                Options:
                [--editor <editor>]

                Run "npm help edit" for more info

exec Run a command from a local or remote npm package

                Usage:
                npm exec -- <pkg>[@<version>] [args...]
                npm exec --package=<pkg>[@<version>] -- <cmd> [args...]
                npm exec -c '<cmd> [args...]'
                npm exec --package=foo -c '<cmd> [args...]'

                Options:
                [--package <package-spec> [--package <package-spec> ...]] [-c|--call <call>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                alias: x

                Run "npm help exec" for more info

explain Explain installed packages

                Usage:
                npm explain <package-spec>

                Options:
                [--json] [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]

                alias: why

                Run "npm help explain" for more info

explore Browse an installed package

                Usage:
                npm explore <pkg> [ -- <command>]

                Options:
                [--shell <shell>]

                Run "npm help explore" for more info

find-dupes Find duplication in the package tree

                Usage:
                npm find-dupes

                Options:
                [--install-strategy <hoisted|nested|shallow>] [--legacy-bundling]
                [--global-style] [--strict-peer-deps] [--no-package-lock]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]] [--ignore-scripts]
                [--no-audit] [--no-bin-links] [--no-fund]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                Run "npm help find-dupes" for more info

fund Retrieve funding information

                Usage:
                npm fund [<package-spec>]

                Options:
                [--json] [--no-browser|--browser <browser>] [--no-unicode]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [--which <fundingSourceNumber>]

                Run "npm help fund" for more info

get Get a value from the npm configuration

                Usage:
                npm get [<key> ...] (See `npm config`)

                Run "npm help get" for more info

help Get help on npm

                Usage:
                npm help <term> [<terms..>]

                Options:
                [--viewer <viewer>]

                alias: hlep

                Run "npm help help" for more info

hook Manage registry hooks

                Usage:
                npm hook add <pkg> <url> <secret> [--type=<type>]
                npm hook ls [pkg]
                npm hook rm <id>
                npm hook update <id> <url> <secret>

                Options:
                [--registry <registry>] [--otp <otp>]

                Run "npm help hook" for more info

init Create a package.json file

                Usage:
                npm init <package-spec> (same as `npx <package-spec>)
                npm init <@scope> (same as `npx <@scope>/create`)

                Options:
                [-y|--yes] [-f|--force] [--scope <@scope>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--no-workspaces-update] [--include-workspace-root]

                aliases: create, innit

                Run "npm help init" for more info

install Install a package

                Usage:
                npm install [<package-spec> ...]

                Options:
                [-S|--save|--no-save|--save-prod|--save-dev|--save-optional|--save-peer|--save-bundle]
                [-E|--save-exact] [-g|--global] [--install-strategy <hoisted|nested|shallow>]
                [--legacy-bundling] [--global-style]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]]
                [--strict-peer-deps] [--no-package-lock] [--foreground-scripts]
                [--ignore-scripts] [--no-audit] [--no-bin-links] [--no-fund] [--dry-run]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                aliases: add, i, in, ins, inst, insta, instal, isnt, isnta, isntal, isntall

                Run "npm help install" for more info

install-ci-test Install a project with a clean slate and run tests

                Usage:
                npm install-ci-test

                Options:
                [-S|--save|--no-save|--save-prod|--save-dev|--save-optional|--save-peer|--save-bundle]
                [-E|--save-exact] [-g|--global] [--install-strategy <hoisted|nested|shallow>]
                [--legacy-bundling] [--global-style]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]]
                [--strict-peer-deps] [--no-package-lock] [--foreground-scripts]
                [--ignore-scripts] [--no-audit] [--no-bin-links] [--no-fund] [--dry-run]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                alias: cit

                Run "npm help install-ci-test" for more info

install-test Install package(s) and run tests

                Usage:
                npm install-test [<package-spec> ...]

                Options:
                [-S|--save|--no-save|--save-prod|--save-dev|--save-optional|--save-peer|--save-bundle]
                [-E|--save-exact] [-g|--global] [--install-strategy <hoisted|nested|shallow>]
                [--legacy-bundling] [--global-style]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]]
                [--strict-peer-deps] [--no-package-lock] [--foreground-scripts]
                [--ignore-scripts] [--no-audit] [--no-bin-links] [--no-fund] [--dry-run]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                alias: it

                Run "npm help install-test" for more info

link Symlink a package folder

                Usage:
                npm link [<package-spec>]

                Options:
                [-S|--save|--no-save|--save-prod|--save-dev|--save-optional|--save-peer|--save-bundle]
                [-E|--save-exact] [-g|--global] [--install-strategy <hoisted|nested|shallow>]
                [--legacy-bundling] [--global-style] [--strict-peer-deps] [--no-package-lock]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]] [--ignore-scripts]
                [--no-audit] [--no-bin-links] [--no-fund] [--dry-run]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                alias: ln

                Run "npm help link" for more info

ll List installed packages

                Usage:
                npm ll [[<@scope>/]<pkg> ...]

                Options:
                [-a|--all] [--json] [-l|--long] [-p|--parseable] [-g|--global] [--depth <depth>]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]] [--link]
                [--package-lock-only] [--no-unicode]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                alias: la

                Run "npm help ll" for more info

login Login to a registry user account

                Usage:
                npm login

                Options:
                [--registry <registry>] [--scope <@scope>] [--auth-type <legacy|web>]

                Run "npm help login" for more info

logout Log out of the registry

                Usage:
                npm logout

                Options:
                [--registry <registry>] [--scope <@scope>]

                Run "npm help logout" for more info

ls List installed packages

                Usage:
                npm ls <package-spec>

                Options:
                [-a|--all] [--json] [-l|--long] [-p|--parseable] [-g|--global] [--depth <depth>]
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]] [--link]
                [--package-lock-only] [--no-unicode]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                alias: list

                Run "npm help ls" for more info

org Manage orgs

                Usage:
                npm org set orgname username [developer | admin | owner]
                npm org rm orgname username
                npm org ls orgname [<username>]

                Options:
                [--registry <registry>] [--otp <otp>] [--json] [-p|--parseable]

                alias: ogr

                Run "npm help org" for more info

outdated Check for outdated packages

                Usage:
                npm outdated [<package-spec> ...]

                Options:
                [-a|--all] [--json] [-l|--long] [-p|--parseable] [-g|--global]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]

                Run "npm help outdated" for more info

owner Manage package owners

                Usage:
                npm owner add <user> <package-spec>
                npm owner rm <user> <package-spec>
                npm owner ls <package-spec>

                Options:
                [--registry <registry>] [--otp <otp>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces]

                alias: author

                Run "npm help owner" for more info

pack Create a tarball from a package

                Usage:
                npm pack <package-spec>

                Options:
                [--dry-run] [--json] [--pack-destination <pack-destination>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                Run "npm help pack" for more info

ping Ping npm registry

                Usage:
                npm ping

                Options:
                [--registry <registry>]

                Run "npm help ping" for more info

pkg Manages your package.json

                Usage:
                npm pkg set <key>=<value> [<key>=<value> ...]
                npm pkg get [<key> [<key> ...]]
                npm pkg delete <key> [<key> ...]
                npm pkg set [<array>[<index>].<key>=<value> ...]
                npm pkg set [<array>[].<key>=<value> ...]

                Options:
                [-f|--force] [--json]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces]

                Run "npm help pkg" for more info

prefix Display prefix

                Usage:
                npm prefix [-g]

                Options:
                [-g|--global]

                Run "npm help prefix" for more info

profile Change settings on your registry profile

                Usage:
                npm profile enable-2fa [auth-only|auth-and-writes]
                npm profile disable-2fa
                npm profile get [<key>]
                npm profile set <key> <value>

                Options:
                [--registry <registry>] [--json] [-p|--parseable] [--otp <otp>]

                Run "npm help profile" for more info

prune Remove extraneous packages

                Usage:
                npm prune [[<@scope>/]<pkg>...]

                Options:
                [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]] [--dry-run]
                [--json] [--foreground-scripts] [--ignore-scripts]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                Run "npm help prune" for more info

publish Publish a package

                Usage:
                npm publish <package-spec>

                Options:
                [--tag <tag>] [--access <restricted|public>] [--dry-run] [--otp <otp>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                Run "npm help publish" for more info

query Retrieve a filtered list of packages

                Usage:
                npm query <selector>

                Options:
                [-g|--global]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                Run "npm help query" for more info

rebuild Rebuild a package

                Usage:
                npm rebuild [<package-spec>] ...]

                Options:
                [-g|--global] [--no-bin-links] [--foreground-scripts] [--ignore-scripts]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                alias: rb

                Run "npm help rebuild" for more info

repo Open package repository page in the browser

                Usage:
                npm repo [<pkgname> [<pkgname> ...]]

                Options:
                [--no-browser|--browser <browser>] [--registry <registry>]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                Run "npm help repo" for more info

restart Restart a package

                Usage:
                npm restart [-- <args>]

                Options:
                [--ignore-scripts] [--script-shell <script-shell>]

                Run "npm help restart" for more info

root Display npm root

                Usage:
                npm root

                Options:
                [-g|--global]

                Run "npm help root" for more info

run-script Run arbitrary package scripts

                Usage:
                npm run-script <command> [-- <args>]

                Options:
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--if-present] [--ignore-scripts]
                [--foreground-scripts] [--script-shell <script-shell>]

                aliases: run, rum, urn

                Run "npm help run-script" for more info

search Search for packages

                Usage:
                npm search [search terms ...]

                Options:
                [-l|--long] [--json] [--color|--no-color|--color always] [-p|--parseable]
                [--no-description] [--searchopts <searchopts>] [--searchexclude <searchexclude>]
                [--registry <registry>] [--prefer-online] [--prefer-offline] [--offline]

                aliases: find, s, se

                Run "npm help search" for more info

set Set a value in the npm configuration

                Usage:
                npm set <key>=<value> [<key>=<value> ...] (See `npm config`)

                Run "npm help set" for more info

shrinkwrap Lock down dependency versions for publication

                Usage:
                npm shrinkwrap

                Run "npm help shrinkwrap" for more info

star Mark your favorite packages

                Usage:
                npm star [<package-spec>...]

                Options:
                [--registry <registry>] [--no-unicode] [--otp <otp>]

                Run "npm help star" for more info

stars View packages marked as favorites

                Usage:
                npm stars [<user>]

                Options:
                [--registry <registry>]

                Run "npm help stars" for more info

start Start a package

                Usage:
                npm start [-- <args>]

                Options:
                [--ignore-scripts] [--script-shell <script-shell>]

                Run "npm help start" for more info

stop Stop a package

                Usage:
                npm stop [-- <args>]

                Options:
                [--ignore-scripts] [--script-shell <script-shell>]

                Run "npm help stop" for more info

team Manage organization teams and team memberships

                Usage:
                npm team create <scope:team> [--otp <otpcode>]
                npm team destroy <scope:team> [--otp <otpcode>]
                npm team add <scope:team> <user> [--otp <otpcode>]
                npm team rm <scope:team> <user> [--otp <otpcode>]
                npm team ls <scope>|<scope:team>

                Options:
                [--registry <registry>] [--otp <otp>] [-p|--parseable] [--json]

                Run "npm help team" for more info

test Test a package

                Usage:
                npm test [-- <args>]

                Options:
                [--ignore-scripts] [--script-shell <script-shell>]

                aliases: tst, t

                Run "npm help test" for more info

token Manage your authentication tokens

                Usage:
                npm token list
                npm token revoke <id|token>
                npm token create [--read-only] [--cidr=list]

                Options:
                [--read-only] [--cidr <cidr> [--cidr <cidr> ...]] [--registry <registry>]
                [--otp <otp>]

                Run "npm help token" for more info

uninstall Remove a package

                Usage:
                npm uninstall [<@scope>/]<pkg>...

                Options:
                [-S|--save|--no-save|--save-prod|--save-dev|--save-optional|--save-peer|--save-bundle]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                aliases: unlink, remove, rm, r, un

                Run "npm help uninstall" for more info

unpublish Remove a package from the registry

                Usage:
                npm unpublish [<package-spec>]

                Options:
                [--dry-run] [-f|--force]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces]

                Run "npm help unpublish" for more info

unstar Remove an item from your favorite packages

                Usage:
                npm unstar [<package-spec>...]

                Options:
                [--registry <registry>] [--no-unicode] [--otp <otp>]

                Run "npm help unstar" for more info

update Update packages

                Usage:
                npm update [<pkg>...]

                Options:
                [-S|--save|--no-save|--save-prod|--save-dev|--save-optional|--save-peer|--save-bundle]
                [-g|--global] [--install-strategy <hoisted|nested|shallow>] [--legacy-bundling]
                [--global-style] [--omit <dev|optional|peer> [--omit <dev|optional|peer> ...]]
                [--strict-peer-deps] [--no-package-lock] [--foreground-scripts]
                [--ignore-scripts] [--no-audit] [--no-bin-links] [--no-fund] [--dry-run]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root] [--no-install-links]

                aliases: up, upgrade, udpate

                Run "npm help update" for more info

version Bump a package version

                Usage:
                npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]

                Options:
                [--allow-same-version] [--no-commit-hooks] [--no-git-tag-version] [--json]
                [--preid prerelease-id] [--sign-git-tag]
                [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--no-workspaces-update] [--include-workspace-root]

                alias: verison

                Run "npm help version" for more info

view View registry info

                Usage:
                npm view [<package-spec>] [<field>[.subfield]...]

                Options:
                [--json] [-w|--workspace <workspace-name> [-w|--workspace <workspace-name> ...]]
                [-ws|--workspaces] [--include-workspace-root]

                aliases: info, show, v

                Run "npm help view" for more info

whoami Display npm username

                Usage:
                npm whoami

                Options:
                [--registry <registry>]



**\*** installation **\*** \***\* "Run "@" \*\***

@penguin:~$ npm install -g @vscode/vsce --force npm WARN using --force Recommended protections disabled.

added 106 packages in 9s

31 packages are looking for funding run npm fund for details @penguin:~$ npm fund user

@penguin:~$ npm fund user

@penguin:~$ npm install bundle exec jekyll serve npm WARN deprecated exec@0.2.1: deprecated in favor of builtin child_process.execFile

added 92 packages in 10s

24 packages are looking for funding run npm fund for details @penguin:~$ npm fund user ├── https://github.com/sponsors/epoberezkin │ └── ajv@8.11.0 ├─┬ https://github.com/sponsors/sindresorhus │ │ └── boxen@7.0.0, camelcase@7.0.1, cli-boxes@3.0.0, string-width@5.1.2, type-fest@2.19.0, widest-line@4.0.1, clipboardy@3.0.0, get-stream@6.0.1, is-stream@2.0.1, onetime@5.1.2, is-docker@2.2.1, is-port-reachable@4.0.0 │ └─┬ https://github.com/chalk/wrap-ansi?sponsor=1 │ │ └── wrap-ansi@8.0.1 │ └── https://github.com/chalk/ansi-styles?sponsor=1 │ └── ansi-styles@6.2.1, ansi-styles@4.3.0 ├── https://github.com/chalk/chalk?sponsor=1 │ └── chalk@5.0.1, chalk@4.1.2 ├── https://github.com/chalk/chalk-template?sponsor=1 │ └── chalk-template@0.4.0 └── https://github.com/sponsors/ljharb └── minimist@1.2.7

up to date, audited 93 packages in 2s

24 packages are looking for funding run npm fund for details

found 0 vulnerabilities @penguin:~$ npm test npm ERR! Missing script: "test" npm ERR! npm ERR! To see a list of scripts, run: npm ERR! npm run

npm ERR! A complete log of this run can be found in: npm ERR! /home/bin/.npm/\_logs/2022-12-13T21_02_45_851Z-debug-0.log @penguin:~$ npm fund user ├── https://github.com/sponsors/epoberezkin │ └── ajv@8.11.0 ├─┬ https://github.com/sponsors/sindresorhus │ │ └── boxen@7.0.0, camelcase@7.0.1, cli-boxes@3.0.0, string-width@5.1.2, type-fest@2.19.0, widest-line@4.0.1, clipboardy@3.0.0, get-stream@6.0.1, is-stream@2.0.1, onetime@5.1.2, is-docker@2.2.1, is-port-reachable@4.0.0 │ └─┬ https://github.com/chalk/wrap-ansi?sponsor=1 │ │ └── wrap-ansi@8.0.1 │ └── https://github.com/chalk/ansi-styles?sponsor=1 │ └── ansi-styles@6.2.1, ansi-styles@4.3.0 ├── https://github.com/chalk/chalk?sponsor=1 │ └── chalk@5.0.1, chalk@4.1.2 ├── https://github.com/chalk/chalk-template?sponsor=1 │ └── chalk-template@0.4.0 └── https://github.com/sponsors/ljharb └── minimist@1.2.7

@penguin:~$ npm install && npm run compile

up to date, audited 93 packages in 4s

24 packages are looking for funding run npm fund for details

found 0 vulnerabilities npm ERR! Missing script: "compile" npm ERR! npm ERR! To see a list of scripts, run: npm ERR! npm run

npm ERR! A complete log of this run can be found in: npm ERR! /home/usr/.npm/\_logs/2022-12-13T21_03_29_875Z-debug-0.log @penguin:~$ npm fund usr ├── https://github.com/sponsors/epoberezkin │ └── ajv@8.11.0 ├─┬ https://github.com/sponsors/sindresorhus │ │ └── boxen@7.0.0, camelcase@7.0.1, cli-boxes@3.0.0, string-width@5.1.2, type-fest@2.19.0, widest-line@4.0.1, clipboardy@3.0.0, get-stream@6.0.1, is-stream@2.0.1, onetime@5.1.2, is-docker@2.2.1, is-port-reachable@4.0.0 │ └─┬ https://github.com/chalk/wrap-ansi?sponsor=1 │ │ └── wrap-ansi@8.0.1 │ └── https://github.com/chalk/ansi-styles?sponsor=1 │ └── ansi-styles@6.2.1, ansi-styles@4.3.0 ├── https://github.com/chalk/chalk?sponsor=1 │ └── chalk@5.0.1, chalk@4.1.2 ├── https://github.com/chalk/chalk-template?sponsor=1 │ └── chalk-template@0.4.0 └── https://github.com/sponsors/ljharb └── minimist@1.2.7

@penguin:~$ npm install && npm run compile

up to date, audited 93 packages in 5s

24 packages are looking for funding run npm fund for details

found 0 vulnerabilities npm ERR! Missing script: "compile" npm ERR! npm ERR! To see a list of scripts, run: npm ERR! npm run

npm ERR! A complete log of this run can be found in: npm ERR! /home/hustlepack68/.npm/\_logs/2022-12-13T21_05_55_516Z-debug-0.log hustlepack68@penguin:$ npm run hustlepack68@penguin:$ npm test npm ERR! Missing script: "test" npm ERR! npm ERR! To see a list of scripts, run: npm ERR! npm run

npm ERR! A complete log of this run can be found in: npm ERR! /home/hustlepack68/.npm/\_logs/2022-12-13T21_06_08_260Z-debug-0.log hustlepack68@penguin:~$ npm run test npm ERR! Missing script: "test" npm ERR! npm ERR! To see a list of scripts, run: npm ERR! npm run

npm ERR! A complete log of this run can be found in: npm ERR! /home/hustlepack68/.npm/\_logs/2022-12-13T21_06_13_891Z-debug-0.log hustlepack68@penguin:~$ npm install run test

added 40 packages, and audited 133 packages in 8s

58 packages are looking for funding run npm fund for details

found 0 vulnerabilities

@penguin:~$ npm fund

user ├── https://github.com/sponsors/epoberezkin │ └── ajv@8.11.0 ├─┬ https://github.com/sponsors/sindresorhus │ │ └── boxen@7.0.0, camelcase@7.0.1, cli-boxes@3.0.0, string-width@5.1.2, type-fest@2.19.0, widest-line@4.0.1, clipboardy@3.0.0, get-stream@6.0.1, is-stream@2.0.1, onetime@5.1.2, is-docker@2.2.1, is-port-reachable@4.0.0 │ └─┬ https://github.com/chalk/wrap-ansi?sponsor=1 │ │ └── wrap-ansi@8.0.1 │ └── https://github.com/chalk/ansi-styles?sponsor=1 │ └── ansi-styles@6.2.1, ansi-styles@4.3.0 ├── https://github.com/chalk/chalk?sponsor=1 │ └── chalk@5.0.1, chalk@4.1.2 ├── https://github.com/chalk/chalk-template?sponsor=1 │ └── chalk-template@0.4.0 └── https://github.com/sponsors/ljharb └── minimist@1.2.7, string.prototype.replaceall@1.0.7, call-bind@1.0.2, define-properties@1.1.4, has-property-descriptors@1.0.0, es-abstract@1.20.5, es-to-primitive@1.2.1, is-date-object@1.0.5, has-tostringtag@1.0.0, is-symbol@1.0.4, function.prototype.name@1.1.5, functions-have-names@1.2.3, get-symbol-description@1.0.0, gopd@1.0.1, is-callable@1.2.7, is-negative-zero@2.0.2, is-shared-array-buffer@1.0.2, is-string@1.0.7, is-weakref@1.0.2, object-inspect@1.12.2, object.assign@4.1.4, regexp.prototype.flags@1.4.3, safe-regex-test@1.0.0, string.prototype.trimend@1.0.6, string.prototype.trimstart@1.0.6, unbox-primitive@1.0.2, has-bigints@1.0.2, which-boxed-primitive@1.0.2, is-bigint@1.0.4, is-boolean-object@1.1.2, is-number-object@1.0.7, side-channel@1.0.4, get-intrinsic@1.1.3, has-symbols@1.0.3, is-regex@1.1.4

@penguin:~$ npm get --update
&& sudo apt-get install -y --no-install-recommends

libc6
libgcc1
libgssapi-krb5-2
libicu67
libssl1.1
libstdc++6
zlib1g ; "user" config from /home/user/.npmrc

//registry.npmjs.org/:\_authToken = (protected)

; "cli" config from command line options

location = "project" update-notifier = true

; node bin location = /home/usr/.config/nvm/versions/node/v19.2.0/bin/node ; node version = v19.2.0 ; npm local prefix = /home/user ; npm version = 9.2.0 ; cwd = /home/user ; HOME = /home/user ; Run npm config ls -l to show all defaults. E: Malformed entry 1 in list file /etc/apt/sources.list.d/nodesource.list (Component) E: The list of sources could not be read. E: Malformed entry 1 in list file /etc/apt/sources.list.d/nodesource.list (Component) E: The list of sources could not be read. @penguin:~$ npm get --update && npm get --install -y --no-install-recommends libc6 libgcc1 libgssapi-krb5-2 libicu67 libssl1.1 libstdc++6 zlib 1g ; "user" config from /home/user/.npmrc

//registry.npmjs.org/:\_authToken = (protected)

; "cli" config from command line options

location = "project" update-notifier = true

; node bin location = /home/user/.config/nvm/versions/node/v19.2.0/bin/node ; node version = v19.2.0 ; npm local prefix = /home/user ; npm version = 9.2.0 ; cwd = /home/usr ; HOME = /home/user ; Run npm config ls -l to show all defaults. libc6=undefined libgcc1=undefined libgssapi-krb5-2=undefined libicu67=undefined libssl1.1=undefined libstdc++6=undefined zlib1g=undefined

@penguin:~$ npm config ls -l ; "default" config from default values

\_auth = (protected) access = null all = false allow-same-version = false also = null audit = true audit-level = null auth-type = "web" before = null bin-links = true browser = null ca = null cache = "/home/user/.npm" cache-max = null cache-min = 0 cafile = null call = "" cert = null ci-name = null cidr = null color = true commit-hooks = true depth = null description = true dev = false diff = [] diff-dst-prefix = "b/" diff-ignore-all-space = false diff-name-only = false diff-no-prefix = false diff-src-prefix = "a/" diff-text = false diff-unified = 3 dry-run = false editor = "vi" engine-strict = false fetch-retries = 2 fetch-retry-factor = 10 fetch-retry-maxtimeout = 60000 fetch-retry-mintimeout = 10000 fetch-timeout = 300000 force = false foreground-scripts = false format-package-lock = true fund = true git = "git" git-tag-version = true global = false global-style = false globalconfig = "/home/hustlepack68/.config/nvm/versions/node/v19.2.0/etc/npmrc" heading = "npm" https-proxy = null if-present = false ignore-scripts = false include = [] include-staged = false include-workspace-root = false init-author-email = "" init-author-name = "" init-author-url = "" init-license = "ISC" init-module = "/home/hustlepack68/.npm-init.js" init-version = "1.0.0" init.author.email = "" init.author.name = "" init.author.url = "" init.license = "ISC" init.module = "/home/hustlepack68/.npm-init.js" init.version = "1.0.0" install-links = true install-strategy = "hoisted" json = false key = null legacy-bundling = false legacy-peer-deps = false link = false local-address = null ; location = "user" ; overridden by cli lockfile-version = null loglevel = "notice" logs-dir = null logs-max = 10 ; long = false ; overridden by cli maxsockets = 15 message = "%s" metrics-registry = "https://registry.npmjs.org/" node-options = null noproxy = [""] offline = false omit = [] omit-lockfile-registry-resolved = false only = null optional = null otp = null pack-destination = "." package = [] package-lock = true package-lock-only = false parseable = false prefer-offline = false prefer-online = false prefix = "/home/hustlepack68/.config/nvm/versions/node/v19.2.0" preid = "" production = null progress = true proxy = null read-only = false rebuild-bundle = true registry = "https://registry.npmjs.org/" replace-registry-host = "npmjs" save = true save-bundle = false save-dev = false save-exact = false save-optional = false save-peer = false save-prefix = "^" save-prod = false scope = "" script-shell = null searchexclude = "" searchlimit = 20 searchopts = "" searchstaleness = 900 shell = "/bin/bash" shrinkwrap = true sign-git-commit = false sign-git-tag = false strict-peer-deps = false strict-ssl = true tag = "latest" tag-version-prefix = "v" timing = false tmp = "/tmp" umask = 0 unicode = true update-notifier = true usage = false user-agent = "npm/{npm-version} node/{node-version} {platform} {arch} workspaces/{workspaces} {ci}" userconfig = "/home/hustlepack68/.npmrc" version = false versions = false viewer = "man" which = null workspace = [] workspaces = null workspaces-update = true yes = null

; "user" config from /home/user/.npmrc

//registry.npmjs.org/:\_authToken = (protected)

; "cli" config from command line options

location = "project" long = true

@penguin:~$ git clone https://sourceware.org/git/glibc.git
cd glibc git checkout release/2.36/master

Cloning into 'glibc'... remote: Enumerating objects: 16836, done. remote: Counting objects: 100% (16836/16836), done. remote: Compressing objects: 100% (5487/5487), done. remote: Total 681735 (delta 13580), reused 13374 (delta 11004), pack-reused 664899 Receiving objects: 100% (681735/681735), 212.68 MiB | 6.64 MiB/s, done. Resolving deltas: 100% (582727/582727), done. Updating files: 100% (19376/19376), done. Updating files: 100% (1236/1236), done. Branch 'release/2.36/master' set up to track remote branch 'release/2.36/master' from 'origin'. Switched to a new branch 'release/2.36/master'

@penguin:/glibc$ npm config fix cd $HOME/src

@penguin:/glibc$ npm config fix -l cd $HOME/src

@penguin:~/glibc$ git clone git://sourceware.org/git/glibc.git

Cloning into 'glibc'... remote: Enumerating objects: 16836, done. remote: Counting objects: 100% (16836/16836), done. remote: Compressing objects: 100% (5487/5487), done. remote: Total 681735 (delta 13580), reused 13373 (delta 11004), pack-reused 664899 Receiving objects: 100% (681735/681735), 212.55 MiB | 2.75 MiB/s, done. Resolving deltas: 100% (582727/582727), done. Updating files: 100% (19376/19376), done.

@penguin:~/glibc$ git clone git://sourceware.org/git/glibc.git

@penguin:~/glibc$ npm install

up to date, audited 133 packages in 9s

58 packages are looking for funding run npm fund for details

found 0 vulnerabilities hustlepack68@penguin:~/glibc$ npm fnd Unknown command: "fnd"

Did you mean this? npm fund # Retrieve funding information

To see a list of supported npm commands, run: npm help @penguin:~/glibc$ npm fund user ├── https://github.com/sponsors/epoberezkin │ └── ajv@8.11.0 ├─┬ https://github.com/sponsors/sindresorhus │ │ └── boxen@7.0.0, camelcase@7.0.1, cli-boxes@3.0.0, string-width@5.1.2, type-fest@2.19.0, widest-line@4.0.1, clipboardy@3.0.0, get-stream@6.0.1, is-stream@2.0.1, onetime@5.1.2, is-docker@2.2.1, is-port-reachable@4.0.0 │ └─┬ https://github.com/chalk/wrap-ansi?sponsor=1 │ │ └── wrap-ansi@8.0.1 │ └── https://github.com/chalk/ansi-styles?sponsor=1 │ └── ansi-styles@6.2.1, ansi-styles@4.3.0 ├── https://github.com/chalk/chalk?sponsor=1 │ └── chalk@5.0.1, chalk@4.1.2 ├── https://github.com/chalk/chalk-template?sponsor=1 │ └── chalk-template@0.4.0 └── https://github.com/sponsors/ljharb └── minimist@1.2.7, string.prototype.replaceall@1.0.7, call-bind@1.0.2, define-properties@1.1.4, has-property-descriptors@1.0.0, es-abstract@1.20.5, es-to-primitive@1.2.1, is-date-object@1.0.5, has-tostringtag@1.0.0, is-symbol@1.0.4, function.prototype.name@1.1.5, functions-have-names@1.2.3, get-symbol-description@1.0.0, gopd@1.0.1, is-callable@1.2.7, is-negative-zero@2.0.2, is-shared-array-buffer@1.0.2, is-string@1.0.7, is-weakref@1.0.2, object-inspect@1.12.2, object.assign@4.1.4, regexp.prototype.flags@1.4.3, safe-regex-test@1.0.0, string.prototype.trimend@1.0.6, string.prototype.trimstart@1.0.6, unbox-primitive@1.0.2, has-bigints@1.0.2, which-boxed-primitive@1.0.2, is-bigint@1.0.4, is-boolean-object@1.1.2, is-number-object@1.0.7, side-channel@1.0.4, get-intrinsic@1.1.3, has-symbols@1.0.3, is-regex@1.1.4

@penguin:~/glibc$ npm install git clone git://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git

(⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠸ idealTree: sill logfile done cleaning log files cd linux⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠸ idealTree: sill logfile done cleaning log files (⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠸ idealTree: sill logfile done cleaning log files DESTDIR=e done cleaning log files $ mkdir $HOME/src (⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠸ idealTree: sill logfile done cleaning log files mkdir -p $HOME/build/glibcalTree: sill logfile done cleaning log files $ cd $HOME/build/glibc $ $HOME/src/glibc/configure --prefix=/usr $ make $ make check (⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠸ idealTree: sill logfile done cleaning log files (⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠸ idealTree: sill logfile done cleaning log files GLIBC=gfile done cleaning log files

@penguin:/glibc$ npm run test GLIBC= @penguin:/glibc$ @penguin:~/glibc$ GCONV_PATH=${GLIBC}/iconvdata LC_ALL=C \

${GLIBC}/elf/ld.so.1 --library-path
${GLIBC}:
${GLIBC}/math:
${GLIBC}/elf:
${GLIBC}/dlfcn:
${GLIBC}/nss:
${GLIBC}/nis:
${GLIBC}/rt:
${GLIBC}/resolv:
${GLIBC}/crypt:
${GLIBC}/nptl:
${GLIBC}/dfp
-bash: syntax error near unexpected token `<'

@penguin:~/glibc$ npm fund

user ├── https://github.com/sponsors/epoberezkin │ └── ajv@8.11.0 ├─┬ https://github.com/sponsors/sindresorhus │ │ └── boxen@7.0.0, camelcase@7.0.1, cli-boxes@3.0.0, string-width@5.1.2, type-fest@2.19.0, widest-line@4.0.1, clipboardy@3.0.0, get-stream@6.0.1, is-stream@2.0.1, onetime@5.1.2, is-docker@2.2.1, is-port-reachable@4.0.0 │ └─┬ https://github.com/chalk/wrap-ansi?sponsor=1 │ │ └── wrap-ansi@8.0.1 │ └── https://github.com/chalk/ansi-styles?sponsor=1 │ └── ansi-styles@6.2.1, ansi-styles@4.3.0 ├── https://github.com/chalk/chalk?sponsor=1 │ └── chalk@5.0.1, chalk@4.1.2 ├── https://github.com/chalk/chalk-template?sponsor=1 │ └── chalk-template@0.4.0 └── https://github.com/sponsors/ljharb └── minimist@1.2.7, string.prototype.replaceall@1.0.7, call-bind@1.0.2, define-properties@1.1.4, has-property-descriptors@1.0.0, es-abstract@1.20.5, es-to-primitive@1.2.1, is-date-object@1.0.5, has-tostringtag@1.0.0, is-symbol@1.0.4, function.prototype.name@1.1.5, functions-have-names@1.2.3, get-symbol-description@1.0.0, gopd@1.0.1, is-callable@1.2.7, is-negative-zero@2.0.2, is-shared-array-buffer@1.0.2, is-string@1.0.7, is-weakref@1.0.2, object-inspect@1.12.2, object.assign@4.1.4, regexp.prototype.flags@1.4.3, safe-regex-test@1.0.0, string.prototype.trimend@1.0.6, string.prototype.trimstart@1.0.6, unbox-primitive@1.0.2, has-bigints@1.0.2, which-boxed-primitive@1.0.2, is-bigint@1.0.4, is-boolean-object@1.1.2, is-number-object@1.0.7, side-channel@1.0.4, get-intrinsic@1.1.3, has-symbols@1.0.3, is-regex@1.1.4

@penguin:/glibc$ npm audit found 0 vulnerabilities @penguin:/glibc$ @penguin:~/glibc$ npm list --json

.JSON
@penguin:~/glibc$ npm list --json { "name": "hustlepack68", "dependencies": { "bundle": { "version": "2.1.0", "resolved": "https://registry.npmjs.org/bundle/-/bundle-2.1.0.tgz", "overridden": false }, "exec": { "version": "0.2.1", "resolved": "https://registry.npmjs.org/exec/-/exec-0.2.1.tgz", "overridden": false }, "jekyll": { "version": "3.0.0-beta1", "resolved": "https://registry.npmjs.org/jekyll/-/jekyll-3.0.0-beta1.tgz", "overridden": false }, "run": { "version": "1.4.0", "resolved": "https://registry.npmjs.org/run/-/run-1.4.0.tgz", "overridden": false }, "serve": { "version": "14.1.2", "resolved": "https://registry.npmjs.org/serve/-/serve-14.1.2.tgz", "overridden": false }, "test": { "version": "3.2.1", "resolved": "https://registry.npmjs.org/test/-/test-3.2.1.tgz", "overridden": false } } }
