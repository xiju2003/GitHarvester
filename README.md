# GitHarvester

Version 0.6
By: @metacortex of @dc801

usage: githarvest.py [-h] [-d DIRECTORY] [-r CUSTOM_REGEX] [-s CUSTOM_SEARCH]
                     [-u] [-v] [-w WRITE_FILE]

This tool is used for harvesting information from GitHub. By default it looks
for code with the filename of 'wp-config.php' and pulls out auth info

optional arguments:
  -h, --help        show this help message and exit
  -d DIRECTORY      Download results to a specific directory
  -r CUSTOM_REGEX   Custom regex string
  -s CUSTOM_SEARCH  Custom GitHub search string
  -u, --url         Output URL of found object if verbose is turned on
  -v, --verbose     Turn verbose output on
  -w WRITE_FILE     Write results to a file

