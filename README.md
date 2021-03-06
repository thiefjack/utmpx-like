utmpx parser
==========

This program reads in a utmpx-like file as input, parses it, and displays the data on screen with certain options to format the output.

How to Compile
--------------
To compile the program, simply navigate to the directory containing the source files for PA4 and type 'make' into terminal.

How to Run
---------
To run the program, type the executable name followed by an utmpx-like file.
	
	./a.out ./utmpx.sample

Normal Output
-------------
	Normal output is printed to stdout.

An example of normal output is:

	$ ./mywho -H ./utmpx.sample 
	NAME       LINE          IDLE 
	cs120wit   pts/2          0:0   (acs-cseb240-26.ucsd.edu)
	cs120wbp   pts/4          2:0   (128.54.233.92)
	cs120wcg   pts/5           .    (128.54.233.213)
	skho       pts/6          0:0   (cpe-75-80-53-223.san.res.rr.com)
	cs120wkq   pts/7          0:0   (128.54.17.179)
	cs120wes   pts/9          0:0   (76-227-227-41.lightspeed.sndgca.sbcglobal.net)
	pwelande   pts/8          0:0   (cpe-76-167-156-97.san.res.rr.com)
	cs30xcq    pts/10         0:0   (128.54.213.239)
	hppham     pts/11         0:0   (162-193-80-224.lightspeed.sndgca.sbcglobal.net)
	cs120wel   pts/12          .    (128.54.51.185)
	cs120wed   pts/13          .    (rh-ip-1922-res.resnet.ucsd.edu)
	bbochkar   pts/14         0:0   (ppp-71-139-9-232.dsl.snfc21.pacbell.net)
	skho       pts/15         0:0   (cpe-75-80-53-223.san.res.rr.com)
	cs131wao   pts/17         6:0   (cpe-76-167-132-191.san.res.rr.com)
	cs120wmo   pts/18          .    (128.54.38.104)
	cs120wbk   pts/19         0:0   (108-216-108-186.lightspeed.sndgca.sbcglobal.net)
	cs131wad   pts/20         1:0   (cpe-76-167-132-180.san.res.rr.com)
	wjensen    pts/21         0:0   (cpe-75-80-56-108.san.res.rr.com)
	ncholaky   pts/23         0:0   (137.110.63.26)
	cs120wmo   pts/24         0:0   (128.54.38.104)
	zilu       pts/25          .    (cpe-75-80-63-101.san.res.rr.com)
	boz001     pts/26         0:0   (128.54.235.28)
	ssampang   pts/27         old   (cpe-76-167-128-204.san.res.rr.com)
	fozhao     pts/28        0:-0   (76-227-226-165.lightspeed.sndgca.sbcglobal.net)
	cs120wcg   pts/29        0:-0   (128.54.233.213)
	b7chung    pts/30        0:-0   (cpe-76-167-132-180.san.res.rr.com)
	wsamuels   pts/31        0:-0   (ip72-207-100-98.sd.sd.cox.net)
	cs120wgg   pts/32         0:0   (cpe-75-80-57-208.san.res.rr.com)
	op         pts/35         old   (acsop-demoore.ucsd.edu)
	lcycon     pts/54          .    (cpe-76-167-128-204.san.res.rr.com)
	fozhao     pts/56          .    (76-227-226-165.lightspeed.sndgca.sbcglobal.net)
	jrapp      pts/57         0:0   (chiasmata.ucsd.edu)
	cs120whm   pts/58         0:0   (cpe-76-167-141-177.san.res.rr.com)
	cs131w     pts/61         0:0   (aiko1.ucsd.edu)
	cs120wct   pts/62         old   (169.228.148.148)
	maryam     pts/63         old   (pogo.ucsd.edu)
	op         pts/64         9:0   (acms-089-ops.ucsd.edu)
	blcollin   pts/67         1:0   (128.54.44.64)
	cs120wjs   pts/68         0:0   (108-66-116-161.lightspeed.sndgca.sbcglobal.net)
	cs120wmc   pts/72         0:0   (acs-cseb240-13.ucsd.edu)
	cs120wmn   pts/73          .    (cpe-66-75-19-11.san.res.rr.com)
	cs30x2     pts/74          .    (99-10-121-71.lightspeed.sndgca.sbcglobal.net)
	cs30x      pts/90         0:0   (aiko1.ucsd.edu)
	op         pts/129        0:0   (acsop-nvaldo.ucsd.edu)
	cs120wiv   pts/130        old   (108-66-116-161.lightspeed.sndgca.sbcglobal.net)
	cs120wjh   pts/131         .    (128.54.128.176)
	op         pts/133         .    (acsop-jthayer-mac.ucsd.edu)
	cs131wap   pts/155         .    (cpe-76-167-166-245.san.res.rr.com)
	cs120wkg   pts/156        0:0   (cpe-75-80-62-24.san.res.rr.com)
	cs131wao   pts/158        3:0   (cpe-76-167-132-191.san.res.rr.com)
	cs120wai   pts/159        0:0   (108-66-116-161.lightspeed.sndgca.sbcglobal.net)
	cs120wkn   pts/160        old   (128.54.44.44)
	calebc     pts/164        7:0   (katana.ucsd.edu)
	zilu       pts/165        0:0   (cpe-75-80-63-101.san.res.rr.com)
	sdatla     pts/166        0:0   (acs-gl1e-pc043.ucsd.edu)
	blcollin   pts/167        0:0   (128.54.44.64)
	cs120wmz   pts/168        1:0   (acs-cseb240-14.ucsd.edu)
	ncholaky   pts/169        6:0   (128.54.39.182)
	cs120wih   pts/172        1:0   (cpe-76-167-164-95.san.res.rr.com)
	cs120wkg   pts/173        9:0   (cpe-75-80-62-24.san.res.rr.com)

Abnormal Output
---------------
	Abnormal output is printed to stderr. This can occur if an file is not specified.
