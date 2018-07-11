gotrntmetainfoparser
====================

Torrent metafile parser written in Go lang.

Usage
====================
package main
import "fmt"
import "github.com/swatkat/gotrntmetainfoparser"

'''
func main() {
    fmt.Println("hello pear")
    metaInfo := new(gotrntmetainfoparser.MetaInfo)
    metaInfo.ReadTorrentMetaInfoFile("NEWIFI_MT7621_OPENWRT_075.tar.gz.torrent")
    metaInfo.DumpTorrentMetaInfo()
}
'''

Installation
====================
* Install packages:

    `go get code.google.com/p/bencode-go`

    `go get github.com/swatkat/gotrntmetainfoparser`

* Import package in your source:

    `import ("github.com/swatkat/gotrntmetainfoparser")`

