# Parse-fortigate-configuration-files
Parse fortigate configuration files into two types of html files, nested and isolated ones.

This is a shell-script version and verified under CentOS release 6.6 (Final).

There are totally 8 scripts and the main script is forti_cfg_parser.sh.
All scripts are located in the same directory.

Usage:

./forti_cfg_parser.sh  fortigate_config_file output_nested_html_file output_isolated_html_file

Where fortigate_config_file is a configuration file, and
      output_nested_html_file, a nested-table html file in name you specified, and
      output_isolated_html_file, an isolated-table html file in name you specified.
      
e.g.

./forti_cfg_parser.sh cfg1.txt cfg1-nested.html cfg1-isolated.html
This command will take file "cfg1.txt"  as an input and output two files cfg1-nested.html and cfg1-isolated.html in nested-tables html and isolated-tables html format respectively.

