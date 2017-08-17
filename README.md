# Introduction

A simple python code to lookup a list of prefixes currently announced via BGP.

It parses (dan) website to gather the required information.

# Reuqirements
urllib
python 2.7

# example: 

if the AS (Autonomus System) of a given ISP is 21003, you just execute this code to know all of its registred/announnced subnets

	root@PC-1:/home#python query_AS_prefixes.py 21003
	'41.208.103.0/24'
	'41.208.64.0/18'
	'41.252.0.0/14'
	'41.252.0.0/18'
	'41.252.128.0/18'
	'41.252.192.0/18'
	'41.252.192.0/19'
	'41.252.64.0/18'
	'41.254.0.0/24'
	'41.254.1.0/24'
	'41.254.15.0/24'
	'41.254.2.0/24'
	'41.254.3.0/24'
	'41.254.31.0/24'
	'41.254.38.0/24'
	'41.254.5.0/24'
	'41.254.6.0/24'
	'41.254.8.0/24'
	'62.240.32.0/19'
	'62.68.32.0/19'
	'62.68.58.0/24'
	'62.68.59.0/24'
	'62.68.60.0/24'
	
# License
GNUv3
