//Modify this file to change what commands output to your statusbar, and recompile using the make command.
static const Block blocks[] = {
	/*Icon*/	/*Command*/		/*Update Interval*/	/*Update Signal*/
	{"", "~/.local/bin/status/sb-forecast",	                    18000,	5},
	{"", "~/.local/bin/status/sb-price btc Bitcoin 💰",				  9000,	  21},
	{"", "~/Templates/volume",							0,		  10},
	{"", "~/Templates/bat",							    60,		  0},
	{"🗑 ", "free -h | awk '/^Mem/ { print $3\"/\"$2 }' | sed s/i//g",	15,		0},
	{"", "date '+%d (%a) %H:%M'",				5,		0},

};

//sets delimeter between status commands. NULL character ('\0') means no delimeter.
static char delim[] = " ";
static unsigned int delimLen = 5;
