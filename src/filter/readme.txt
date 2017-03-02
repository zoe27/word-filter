Aho-Corasick is a multiple string matching algorithm
I implement the algorithm in trie.go
In filter.go, I use the built trie to search sensitive words,and filter them out
In test1.go, I test the filter function
In test2.go, I implement a simple http server, and the dictionary can be asynchronously hot-updated and hot-reloading using command: 'kill -1 pid'

go run test1.go
go run test2.go
