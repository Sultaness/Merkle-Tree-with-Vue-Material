# Merkletree with Vue Material

Construction of a visual Merkle Tree using Vue Material. 

#### Definition of a Merkle Tree

A Merkle Tree is a data structure used for efficiently summarizing and verifying the integrity of large sets of data.

#### Merkle Trees in Bitcoin

* Merkle trees are used in bitcoin to summarize all the transactions in a block, producing an overall digital fingerprint of the entire set of transactions, providing a very efficient process to verify whether a transaction is included in a block.
* Merkle trees are binary trees containing cryptographic hashes.
* They are displayed upside down with the "root" at the top and the "leaves" at the bottom.

#### Example of a Merkle Tree containing 16 leaf nodes


![Merkle Tree summarizing many data elements](https://github.com/bitcoinbook/bitcoinbook/blob/develop/images/mbc2_0904.png "Merkle Tree summarizing many data elements")

<br>

### Installation & Usage

1. To use this application, clone the repository using: 

```JS
git clone git@github.com:Sultaness/MerkletreeVue.git
```

Or, you may download it from **Clone or Download --> Download ZIP**

2. Open `Terminal` and navigate to the extracted folder.

3. Run the file using: 

```JS
npm install 
```

```js
npm run dev
```

#### References

1. [Merkle Trees, Chapter 9, Mastering Bitcoin by Andreas Antonopoulos](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch09.asciidoc#merkle-trees)
2. [SHA256 in Javascript](https://www.npmjs.com/package/js-sha256)
3. [Vue Material](https://vuematerial.io/components/app)
