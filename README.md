# strings-vs-bytes
```bash
BenchmarkBytesToStrings-4            	50000000	        20.5 ns/op	      32 B/op	       1 allocs/op
BenchmarkBytesCompareSame-4          	300000000	         4.44 ns/op	       0 B/op	       0 allocs/op
BenchmarkBytesCompareDifferent-4     	300000000	         4.57 ns/op	       0 B/op	       0 allocs/op
BenchmarkStringsCompareSame-4        	2000000000	         1.67 ns/op	       0 B/op	       0 allocs/op
BenchmarkStringsCompareDifferent-4   	200000000	         8.19 ns/op	       0 B/op	       0 allocs/op
BenchmarkBytesContains-4             	100000000	        11.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkStringsContains-4           	100000000	        10.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkBytesIndex-4                	200000000	         7.11 ns/op	       0 B/op	       0 allocs/op
BenchmarkStringIndex-4               	300000000	         6.09 ns/op	       0 B/op	       0 allocs/op
BenchmarkBytesReplace-4              	20000000	        60.1 ns/op	      32 B/op	       1 allocs/op
BenchmarkStringsReplace-4            	20000000	        91.4 ns/op	      64 B/op	       2 allocs/op
BenchmarkBytesConcat2-4              	50000000	        23.9 ns/op	      32 B/op	       1 allocs/op
BenchmarkStringsConcat2-4            	50000000	        37.4 ns/op	      32 B/op	       1 allocs/op
BenchmarkStringsJoin2-4              	30000000	        48.5 ns/op	      32 B/op	       1 allocs/op
BenchmarkMapHints-4                  	200000000	         7.08 ns/op	       0 B/op	       0 allocs/op
BenchmarkMapsHints_Dont-4            	100000000	        12.2 ns/op	       0 B/op	       0 allocs/op
```

### Link :
https://medium.com/@felipedutratine/in-golang-should-i-work-with-bytes-or-strings-8bd1f5a7fd48#.6m2j7ssec
