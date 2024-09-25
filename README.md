git init
git hash-object -w filename
6a00e12055941d688466e68d6880d2bc06f12b55
4ab7e6dbb9b1dd73a3e0292ef1d1b2909d107309
vi filename->100644 blob shacode->esc:wq
cat filename | git mktree  #3ada6b8dd6d774f4863d378d3002512fbcf04631
git read-tree <code>
