# ansible-tutorial


# -- YAML Basics

YAML is composed of key-value pairs,lists and dictionaries

File open with three hyphes(---) on first line and close with three periods(...)

List items are designated with a single hyphen and a space

each list item should have same indentation.

Dictionaries are designated with colon and a space followed by indented key-value pairs

pipes and right angle bracket (| and >) may be allow for line breaks within YMAL


YMAL special charecters: [] {} : > |

you must use double quotes to escape special charecters


# -- Ansible Components

# 1. Inventories

Inventories are how ansible can locate and run against multiple systems

you can think inventory is a list of hosts

by default ansible uses /etc/ansible/hosts as its inventory but this is configurable

inventories may be formatted  as an INI file or YAML file.

inventory file consists of list of hostnames

it is also possible to define groups of hosts, host or group level variables, groups of groups within inventory file

we can use variables inside inventory file

 
