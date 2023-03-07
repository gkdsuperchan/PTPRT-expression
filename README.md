# PTPRT-expression

Running Pipeline:

#Step01: Collect sample information.

sh step01.getSampleinfo.sh

#Step02: Collect mutation data.

sh step02.getmaf.sh

#Step03: pooled samples.

sh step03.mergemaf.sh

#Step04: pool sample information.

sh step04.germarkermut.sh

#Step05: prepare for fisher tables.

sh step05.prepare.Fisher. sh

#Step06: run for multiple cancer types and do p.adjust.

sh step06.Fisherexact-test.sh

Author contact information: Chao Chen(gkd.chaochen@foxmail.com) .
