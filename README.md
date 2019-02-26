# Prime numbers generator
Assembly language, MIPS
Politechnika Warszawska, Architektura komputerów ARKO 19L



## Pseudocode
```
i = start - 1
loop i:
	i++
	if i == stop jump end
	j = 1
	loop j:
		j++
		if i == j jump print
		div i / j
		if remainder == 0 jump loop i
		jump loop j

print:
	counter++
	print
	jump loop i
```
