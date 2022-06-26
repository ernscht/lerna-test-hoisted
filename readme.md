# lerna test hoisted

expected: dependency versions of lerna packages should be fixed in a package-lock.json

npm <=6: "jest", "yn" and "is-reachable" are not present in a lock file
npm >=8 (lockfile version 2): "jest", "yn" and "is-reachable" are present in the base lock file

