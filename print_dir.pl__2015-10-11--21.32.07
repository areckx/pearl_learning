#!/usr/bin/perl
use strict;
use warnings;

# Subroutine print_dir takes the name of the directory as a paramater
# and prints the file in that dir, one per line

# Write subroutine
#
# TODO 
# 	[] Write the subroutine so that if the user includes the / at the 
# 	   end of the directory name it will trim the output down to include
# 	   only one /

sub print_dir
# Opening Braces
{
	# Var for storing directory	
	# Open all files in directory 
	my @files = glob "@_/*";

	
	# Use an index var for counting off elements of array @files
	my $i = 0;

	# Success!!!!
	# While $i is less than or equal the last element of the array...
	while ($i <= $#files)
	{
		# Print the current element with a newline char
		print "$files[$i]\n";
		# Increment $i by 1, otherwise it will print infinitely
		$i++;
	} 
	
#Closing Braces
}

# Invoke \print_dir\
print_dir @ARGV;
