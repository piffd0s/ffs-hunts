# ffs-hunts
a list of JSON based queries to hunt for potential evil... leverages FFS and FFS-tools here https://github.com/code42/ffs-tools


These will be run through the command line i.e.

python ./ffs_search.py --username user@domain.com --search_type raw --in_file ./hunt-exe-in-downloads.json --out_filter md5 | awk '!seen[$0]++'
