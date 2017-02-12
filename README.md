# strings-vs-bytes
```bash
BenchmarkBytesToStrings-4    	30000000	        38.6 ns/op	      32 B/op	       1 allocs/op
BenchmarkBytesCompare-4      	300000000	         5.06 ns/op	       0 B/op	       0 allocs/op
BenchmarkStringsCompare-4    	1000000000	         2.37 ns/op	       0 B/op	       0 allocs/op
BenchmarkBytesContains-4     	100000000	        17.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkStringsContains-4   	100000000	        12.3 ns/op	       0 B/op	       0 allocs/op
BenchmarkBytesIndex-4        	200000000	         8.75 ns/op	       0 B/op	       0 allocs/op
BenchmarkStringIndex-4       	200000000	         6.83 ns/op	       0 B/op	       0 allocs/op
BenchmarkBytesReplace-4      	20000000	        77.3 ns/op	      32 B/op	       1 allocs/op
BenchmarkStringsReplace-4    	10000000	       137 ns/op	      64 B/op	       2 allocs/op
BenchmarkBytesConcat-4       	50000000	        39.4 ns/op	      32 B/op	       1 allocs/op
BenchmarkStringsConcat-4     	30000000	        51.0 ns/op	      32 B/op	       1 allocs/op
BenchmarkStringsJoin-4       	20000000	        85.0 ns/op	      64 B/op	       2 allocs/op
BenchmarkMapHints-4           100000000         12.3 ns/op        0 B/op         0 allocs/op
BenchmarkMapsHints_Dont-4     100000000         22.0 ns/op        0 B/op         0 allocs/op
```

### Link :
https://medium.com/@felipedutratine/in-golang-should-i-work-with-bytes-or-strings-8bd1f5a7fd48#.6m2j7ssec
