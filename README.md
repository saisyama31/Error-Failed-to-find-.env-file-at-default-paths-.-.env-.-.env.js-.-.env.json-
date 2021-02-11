# Error-Failed-to-find-.env-file-at-default-paths-.-.env-.-.env.js-.-.env.json-

This has been updated in the latest version of env-cmd, if you are using version <9.0.0 then it will work perfectly but with version >9.0.0 the default environment file it will look for is .env

use env-cmd -f .env.development gatsby develop instead, here -f is provided for custom file name.
