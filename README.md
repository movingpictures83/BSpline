# BSplines
# Language: Python
# Input: TXT
# Output: TSV
# Tested with: PluMA 1.1, Python 3.6
# Dependency: numpy==1.19.1, scipy==1.4.1

PluMa plugin that performs time-series alignment using B-splines.

The plugin takes as input a tab-delimited file of keyword-value pairs:

txtfile: TXT file of temporal data, relative abundances
alignmentType: 0=all periods, all subjects, 1=each period, same subject, 2=each period, each group, 3=each period, all subjects
useSplines: True or False, as to whether or not to use splines.

The taxa that best agree with the global alignment will be output as a TSV file, with rankings.
