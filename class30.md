[Github](https://batoolalali.github.io/401-Reading-notes/class30)

# Hashtables

- Hashtables are a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.


## Hashing
- hash code turns a key into an integer. 
- Hash codes should never have randomness to them. The same key should always produce the same hash code.

### Creating a Hash
- A hashtable traditionally is created from an array. 


## Collisions
- A collision occurs when more than one key hashes to the same index in an array. 
- Perfect hash will never have any collisions. 
- The more keys you have hashed to a specific index, the more key/value pair combos you can potentially have.

### Solving collision
Collisions are solved by changing the initial state of the buckets.
Since different keys can lead to the same bucket it’s important to store the entire key/value pair in the bucket, not just the value. 
The key must be stored with the value! If only values were stored in buckets then it would be impossible to determine which value to return when a key led you to a bucket.

## Bucket Sizes
Hash Maps can have any number of buckets.
-  If a hash map has only a few buckets it will be densely full and have many collisions. 
- If a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.
