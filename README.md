# txt2tags tools


**HTML-WikiConverter-Txt2tags**  
Convert HTML pages to txt2tags markup.

**gensite.py**  
A Python script to generate a site with txt2tags. It copies all files over,
except those with txt2tags extension, which are automatically converted.

**html-update.sh**  
A simple shell script to automate the conversion of files in a directory.
It scans and converts only the .t2t files that has changed since the last
conversion. There are command line options and an interactive mode.

**markdown2txt2tags.sh**  
Convert Markdown files to the txt2tags markup.

**retxt2tags**  
A CSS file to format HTML pages using the txt2tags markup instead.

**rtf_unicode.t2t**  
Configuration file to escape Unicode characters in RTF files. Include it
using the `--config-file` command line option.

**t2tmake.rb**  
A powerful Ruby script that automate the conversion of txt2tags files.
It scans directories, convert needed files and generate logs. It also has
a nice batch feature, to store different sets of configurations.

**txt2tags-ui.php**  
The txt2tags web interface, written in PHP. Useful for intranets and
quick tests. There's a demo online at <http://txt2tags.org/online.php>.
